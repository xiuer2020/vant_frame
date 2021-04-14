<template>
  <div id="demo">
    <div class="van-overlay" style="z-index: 2001;"></div>
    <div
      class="van-popup van-popup--round van-popup--bottom van-popup--safe-area-inset-bottom van-share-sheet"
      style="z-index: 2002;">
      <div class="van-share-sheet__header"><h2 class="van-share-sheet__title">title slot</h2>
<!--        mt8 + lh20px-->
        <span
        class="van-share-sheet__description">description slot</span>
<!--        db + mt8 + lh16px-->
      </div>
      <div class="van-share-sheet__options">
        <div role="button" tabindex="0" class="van-share-sheet__option"><img
          src="https://img01.yzcdn.cn/vant/share-sheet-wechat.png"
          class="van-share-sheet__icon"><span class="van-share-sheet__name">微信</span></div>
        <div role="button" tabindex="0" class="van-share-sheet__option"><img
          src="https://img01.yzcdn.cn/vant/share-sheet-weibo.png"
          class="van-share-sheet__icon"><span class="van-share-sheet__name">微博</span></div>
        <div role="button" tabindex="0" class="van-share-sheet__option"><img
          src="https://img01.yzcdn.cn/vant/share-sheet-link.png" class="van-share-sheet__icon"><span
          class="van-share-sheet__name">复制链接</span></div>
        <div role="button" tabindex="0" class="van-share-sheet__option"><img
          src="https://img01.yzcdn.cn/vant/share-sheet-poster.png"
          class="van-share-sheet__icon"><span class="van-share-sheet__name">分享海报</span></div>
        <div role="button" tabindex="0" class="van-share-sheet__option"><img
          src="https://img01.yzcdn.cn/vant/share-sheet-qrcode.png"
          class="van-share-sheet__icon"><span class="van-share-sheet__name">二维码</span></div>
      </div>
      <button type="button" class="van-share-sheet__cancel">取消</button>
    </div>
  </div>
</template>

<script>
  export default {
    name: "ShareSheet.vue"
  }
</script>

<style scoped>

</style>
