<template>
  <div id="demo">
    <div class="van-overlay van-image-preview__overlay" style="z-index: 2005;"></div>
    <div class="van-image-preview" style="z-index: 2006;">
      <div class="van-swipe van-image-preview__swipe">
        <div class="van-swipe__track"
             style="transition-duration: 300ms; transform: translateX(0px); width: 750px;">
          <div class="van-swipe-item van-image-preview__swipe-item" style="width: 375px;">
            <div class="van-image van-image-preview__image" style="transition-duration: 0.3s;"><img
              src="https://img01.yzcdn.cn/vant/apple-1.jpg" class="van-image__img"
              style="object-fit: contain;"></div>
          </div>
          <div class="van-swipe-item van-image-preview__swipe-item" style="width: 375px;">
            <div class="van-image van-image-preview__image" style="transition-duration: 0.3s;"><img
              src="https://img01.yzcdn.cn/vant/apple-2.jpg" class="van-image__img"
              style="object-fit: contain;"></div>
          </div>
        </div>
      </div>
      <div class="van-image-preview__index">第0页</div>
<!--      posa + t16 + l50 + lh20px + trftlx-50p-->
      <div class="van-image-preview__cover">cover slot</div>
<!--      posa + t0 + l0-->
    </div>
<!--    posf-->
  </div>
</template>

<script>
  export default {
    name: "ImagePreview.vue"
  }
</script>

<style scoped>

</style>
