<template>
  <div class="demo">
    <span class="van-popover__wrapper">reference slot</span>
<!--    dib-->
    <div class="van-popup van-popover van-popover--light"
         style="z-index: 2002; position: absolute; left: 149px; top: 76px; margin: 0px;"
         data-popper-placement="bottom">
      <div class="van-popover__arrow"></div>
      <div role="menu" class="van-popover__content">default slot</div>
<!--      dib-->
    </div>
<!--    posa + l149 + t576-->
  </div>

</template>

<script>
  export default {
    name: "Popover.vue"
  }
</script>

<style scoped>

</style>
