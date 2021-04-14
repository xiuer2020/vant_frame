<template>
  <div class="van-steps van-steps--horizontal">
    <div class="van-steps__items">
      <div class="van-hairline van-step van-step--horizontal van-step--finish">
        <div class="van-step__title">default slot</div>
<!--        dib + fx1 + fl-->
        <div class="van-step__circle-container">finish-icon slot</div>
<!--        posa + t30 + l-8 + p(0 8px)-->
        <div class="van-step__line"></div>
      </div>
      <div class="van-hairline van-step van-step--horizontal van-step--process">
        <div class="van-step__title van-step__title--active">商家接单</div>
        <div class="van-step__circle-container"><i
          class="van-icon van-icon-checked van-step__icon van-step__icon--active"><!----></i></div>
        <div class="van-step__line"></div>
      </div>
      <div class="van-hairline van-step van-step--horizontal">
        <div class="van-step__title">买家提货</div>
        <div class="van-step__circle-container"><i class="van-step__circle"></i></div>
        <div class="van-step__line"></div>
      </div>
      <div class="van-hairline van-step van-step--horizontal">
        <div class="van-step__title">交易完成</div>
        <div class="van-step__circle-container"><i class="van-step__circle"></i></div>
        <div class="van-step__line"></div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Steps.vue"
  }
</script>

<style scoped>

</style>
