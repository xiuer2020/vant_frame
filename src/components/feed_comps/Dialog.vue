<template>
  <div id="demo">
    <div class="van-overlay" style="z-index: 2001;"></div>
    <div role="dialog" aria-labelledby="标题" class="van-dialog" style="z-index: 2002;">
      <div class="van-dialog__header">title slot</div>
<!--      pt26 + lh24px-->
      <div class="van-dialog__content">default slot</div>
<!--      db-->
      <div class="van-hairline--top van-dialog__footer">
        <button class="van-button van-button--default van-button--large van-dialog__cancel">
          <div class="van-button__content"><span class="van-button__text">取消</span></div>
        </button>
        <button
          class="van-button van-button--default van-button--large van-dialog__confirm van-hairline--left">
          <div class="van-button__content"><span class="van-button__text">确认</span></div>
        </button>
      </div>
    </div>
  </div>
</template>
