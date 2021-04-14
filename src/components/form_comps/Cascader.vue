<template>
  <div class="van-cascader">
    <div class="van-cascader__header"><h2 class="van-cascader__title">title slot</h2><i
      class="van-icon van-icon-cross van-cascader__close-icon"><!----></i></div>
    <div class="van-tabs van-tabs--line van-cascader__tabs">
      <div class="van-tabs__wrap van-tabs__wrap--scrollable">
        <div role="tablist" class="van-tabs__nav van-tabs__nav--line van-tabs__nav--complete">
          <div role="tab" aria-selected="true"
               class="van-tab van-tab--active van-cascader__tab van-cascader__tab--unselected"><span
            class="van-tab__text">请选择</span></div>
          <div class="van-tabs__line" style="transform: translateX(37px) translateX(-50%);"></div>
        </div>
      </div>
      <div class="van-tabs__content van-tabs__content--animated">
        <div class="van-tabs__track"
             style="transform: translate3d(0%, 0px, 0px); transition-duration: 0.3s;">
          <div role="tabpanel" class="van-tab__pane-wrapper">
            <div class="van-tab__pane">
              <ul class="van-cascader__options"></ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="van-cascader">
    <div class="van-cascader__header">
      <h2 class="van-cascader__title">title slot</h2>
<!--      h48 + aic + lh20 + dib -->
      <i
      class="van-icon van-icon-cross van-cascader__close-icon"><!----></i></div>
    <div class="van-tabs van-tabs--line van-cascader__tabs">
      <div class="van-tabs__wrap van-tabs__wrap--scrollable">
        <div role="tablist" class="van-tabs__nav van-tabs__nav--line van-tabs__nav--complete">
          <div role="tab" class="van-tab van-cascader__tab"><span class="van-tab__text">浙江省</span>
          </div>
          <div role="tab"
               class="van-tab van-tab--active van-cascader__tab van-cascader__tab--unselected"
               aria-selected="true"><span class="van-tab__text">请选择</span></div>
          <div class="van-tabs__line"
               style="transform: translateX(99px) translateX(-50%); transition-duration: 0.3s;"></div>
        </div>
      </div>
      <div class="van-tabs__content van-tabs__content--animated">
        <div class="van-tabs__track"
             style="transform: translate3d(-100%, 0px, 0px); transition-duration: 0.3s;">
          <div role="tabpanel" class="van-tab__pane-wrapper van-tab__pane-wrapper--inactive"
               aria-hidden="true">
            <div class="van-tab__pane">
              <ul class="van-cascader__options">
                <li class="van-cascader__option van-cascader__option--selected"><span>浙江省</span><i
                  class="van-icon van-icon-success van-cascader__selected-icon"><!----></i></li>
                <li class="van-cascader__option"><span>江苏省</span></li>
              </ul>
            </div>
          </div>
          <div role="tabpanel" class="van-tab__pane-wrapper">
            <div class="van-tab__pane">
              <ul class="van-cascader__options">
                <li class="van-cascader__option"><span>杭州市</span></li>
                <li class="van-cascader__option"><span>宁波市</span></li>
                <li class="van-cascader__option"><span>温州市</span></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Cascader.vue"
  }
</script>

<style scoped>

</style>
