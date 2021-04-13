<template>
  <div class="van-search">
    left slot
    <div class="van-search__content van-search__content--square">
      <div class="van-search__label">label slot</div>
      <!-- dib + p(0 5px) + lh34px -->
      <div class="van-cell van-cell--borderless van-field">
        <div class="van-field__left-icon">left-icon slot</div>
        <!-- mr4 + dib -->
        <div class="van-cell__value van-cell__value--alone van-field__value">
          <div class="van-field__body">
            <input
              type="search"
              placeholder="请输入搜索关键词"
              class="van-field__control"
            />
            <div class="van-field__right-icon">right-icon slot</div>
            <!-- mr-8 p(0 8px) fxsh0 -->
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- df + p(10px 12px) + aic -->
</template>

<script>
export default {};
</script>

<style>
</style>