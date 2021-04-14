<template>
  <div id="app">
    <div class="van-overlay" style="z-index: 2001;"></div>
    <div
      class="van-popup van-popup--round van-popup--bottom van-popup--safe-area-inset-bottom van-action-sheet"
      style="z-index: 2002;">
      <div class="van-action-sheet__description">description slot</div>
<!--      p(20px 16px) + lh20px-->
      <div class="van-action-sheet__content">default slot</div>
<!--      fx(1 auto)-->
    </div>
  </div>
</template>

<script>
  export default {
    name: "ActionSheet.vue"
  }
</script>

<style scoped>

</style>
