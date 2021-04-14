<template>
  <div class="van-collapse van-hairline--top-bottom">
    <div class="van-collapse-item">
      <div role="button" tabindex="0" aria-expanded="true"
           class="van-cell van-cell--clickable van-collapse-item__title van-collapse-item__title--expanded">
        icon slot
        <div class="van-cell__title">title slot</div>
<!--        dib + fx1 + lh24px-->
        <div class="van-cell__value">value slot</div>
        <!--        dib + fx1 + lh24px-->
        right-icon slot
      </div>
<!--      posr + df + w100p + p(10px 16px) + lh24px-->

      <div class="van-collapse-item__wrapper">
        <div class="van-collapse-item__content">default slot</div>
<!--        p(12px 16px) + lh1.5-->
      </div>
    </div>
    <div class="van-collapse-item van-collapse-item--border">
      <div role="button" tabindex="0" aria-expanded="false"
           class="van-cell van-cell--clickable van-collapse-item__title">
        <div class="van-cell__title"><span>标题2</span></div>
        <i class="van-icon van-icon-arrow van-cell__right-icon"><!----></i></div>
    </div>
    <div class="van-collapse-item van-collapse-item--border">
      <div role="button" tabindex="0" aria-expanded="false"
           class="van-cell van-cell--clickable van-collapse-item__title">
        <div class="van-cell__title"><span>标题3</span></div>
        <i class="van-icon van-icon-arrow van-cell__right-icon"><!----></i></div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Collapse.vue"
  }
</script>

<style scoped>

</style>
