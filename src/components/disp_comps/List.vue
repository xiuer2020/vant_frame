<template>
  <div role="feed" class="van-list">
    <div class="van-cell">
      <div class="van-cell__title"><span>default slot</span>
        dib + lh24px + p(10px 0)
      </div>
    </div>
    <div class="van-cell">
      <div class="van-cell__title"><span>default slot</span></div>
    </div>
    <div class="van-list__loading">loading slot</div>
<!--    lh50px 即finished slot, loading slot, error slot-->
    <div class="van-list__placeholder"></div>
  </div>
</template>

<script>
  export default {
    name: "List.vue"
  }
</script>

<style scoped>

</style>
