<template>
  <div class="van-swipe-cell">
    <div class="van-swipe-cell__wrapper"
         style="transform: translate3d(0px, 0px, 0px); transition-duration: 0.6s;">
      <div class="van-swipe-cell__left">left slot</div>
<!--      posa + t0 + h100p + l0-->
      default slot
      <div class="van-swipe-cell__right">right slot</div>
      <!--      posa + t0 + h100p + r0-->
    </div>
<!--    db + posr -->
  </div>
</template>

<script>
  export default {
    name: "SwipeCell.vue"
  }
</script>

<style scoped>

</style>
