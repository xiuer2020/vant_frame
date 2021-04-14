<template>
  <div class="van-stepper">
    <button
      type="button"
      class="van-stepper__minus van-stepper__minus--disabled"
    ></button
    ><input
      type="text"
      role="spinbutton"
      inputmode="decimal"
      aria-valuemax="Infinity"
      aria-valuemin="1"
      aria-valuenow="1"
      class="van-stepper__input"
    /><button type="button" class="van-stepper__plus"></button>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>