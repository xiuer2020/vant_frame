<template>
  <div class="van-tabs van-tabs--line">
    <div class="van-tabs__wrap">
      <div role="tablist" class="van-tabs__nav van-tabs__nav--line">nav-left slot
        <div role="tab" aria-selected="true" class="van-tab van-tab--active"><span
          class="van-tab__text van-tab__text--ellipsis">title slot</span>
<!--          dib + p(0 4px)-->
        </div>
        <div role="tab" class="van-tab"><span
          class="van-tab__text van-tab__text--ellipsis">标签 2</span></div>
        <div role="tab" class="van-tab"><span
          class="van-tab__text van-tab__text--ellipsis">标签 3</span></div>
        <div role="tab" class="van-tab"><span
          class="van-tab__text van-tab__text--ellipsis">标签 4</span></div>
        <div class="van-tabs__line" style="transform: translateX(107px) translateX(-50%);"></div>
        nav-right slot
      </div>
<!--      h100p + pb15 + df + posr-->
    </div>
<!--    h44-->
    <div class="van-tabs__content">
      <div role="tabpanel" class="van-tab__pane" style="">default slot</div>

      <div role="tabpanel" class="van-tab__pane" style="display: none;"><!----></div>
      <div role="tabpanel" class="van-tab__pane" style="display: none;"><!----></div>
      <div role="tabpanel" class="van-tab__pane" style="display: none;"><!----></div>
    </div>
<!--    db-->
  </div>
</template>

<script>
  export default {}
</script>

<style>

</style>
