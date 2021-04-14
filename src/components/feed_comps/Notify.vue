<template>
  <div id="app">
    <button class="van-button van-button--primary van-button--normal">
      <div class="van-button__content"><span class="van-button__text">组件调用</span></div>
    </button>
    <div class="van-popup van-popup--top van-notify van-notify--success"
         style="transition-duration: 0.2s; z-index: 2001;"><i class="van-icon van-icon-bell"
                                                              style="margin-right: 4px;"><!----></i><span>通知内容</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Notify.vue"
  }
</script>

<style scoped>

</style>
