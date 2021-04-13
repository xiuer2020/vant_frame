<template>
  <div class="van-picker">
    <div class="van-picker__toolbar">
      <button type="button" class="van-picker__cancel">cancel slot</button>
      <!-- dib + p(0 16px) + h100p -->
      title slot
      <button type="button" class="van-picker__confirm">confirm slot</button>
      <!-- dib + p(0 16px) + h100p -->
    </div>
    <!-- df + aic + jcsb + h44 即为default slot的父元素 -->
    <!---->columns-top slot
    <div class="van-picker__columns" style="height: 264px">
      <div class="van-picker-column">
        <ul
          class="van-picker-column__wrapper"
          style="
            transform: translate3d(0px, 110px, 0px);
            transition-duration: 0ms;
            transition-property: none;
          "
        >
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item van-picker-column__item--selected"
            style="height: 44px"
          >
            option slot
          </li>
          <!-- h44 + df aic + jcc + p(0 4px) 即option lot -->
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item"
            style="height: 44px"
          >
            option slot
          </li>
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item"
            style="height: 44px"
          >
            option slot
          </li>
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item"
            style="height: 44px"
          >
            option slot
          </li>
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item"
            style="height: 44px"
          >
            option slot
          </li>
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item"
            style="height: 44px"
          >
            option slot
          </li>
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item"
            style="height: 44px"
          >
            option slot
          </li>
          <li
            role="button"
            tabindex="0"
            class="van-picker-column__item"
            style="height: 44px"
          >
            option slot
          </li>
        </ul>
      </div>
      <div class="van-picker__mask" style="background-size: 100% 110px"></div>
      <div
        class="van-hairline-unset--top-bottom van-picker__frame"
        style="height: 44px"
      ></div>
    </div>
    columns-bottom slot<!---->
  </div>
   <!-- posr -->
</template>

<script>
export default {};
</script>

<style>
</style>