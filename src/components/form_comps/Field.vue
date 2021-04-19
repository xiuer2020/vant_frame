<template>
  <div class="van-cell van-field">
    <div class="van-field__left-icon">left-icon slot</div>
    <!--   dib + mr4-->
    <div class="van-cell__title van-field__label">label slot</div>
    <!--    dib + w6.2em + mr12 -->
    <div class="van-cell__value van-field__value">
      <div class="van-field__body">
        <div class="van-field__control van-field__control--custom">input slot</div>
        <!--        df + mih24 + w100p + dib + miw100p-->
        <div class="van-field__right-icon">right-icon slot</div>
        <!--        mr-8 + p(0 8px) + fxsh0-->
        <div class="van-field__button">button slot</div>
        <!--        pl8 + fxsh0-->
      </div>
    </div>
    <i class="van-icon van-icon-arrow van-cell__right-icon"><!----></i>
    <!--    mr4 + h24 + lh24px-->
    extra slot
  </div>
  <!--  df + p(10px 16px) + lh14px-->
</template>

<script>
  export default {
    name: "Field.vue"
  }
</script>

<style scoped>

</style>
