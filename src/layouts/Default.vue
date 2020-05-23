<template>
  <div class="page">
    <div class="page__header">
      <the-header />
    </div>
    <main class="page__main">
      <slot />
    </main>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader';
export default {
  name: 'Default',
  components: {
    TheHeader,
  },
};
</script>
