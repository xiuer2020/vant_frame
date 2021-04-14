<template>
  <div class="van-circle">
    <svg viewBox="0 0 1040 1040">
      <path d="M 520 520 m 0, -500 a 500, 500 0 1, 1 0, 1000 a 500, 500 0 1, 1 0, -1000"
            class="van-circle__layer" style="fill: none; stroke-width: 40px;"></path>
      <path d="M 520 520 m 0, -500 a 500, 500 0 1, 1 0, 1000 a 500, 500 0 1, 1 0, -1000"
            class="van-circle__hover"
            style="stroke-width: 41px; stroke-dasharray: 942px, 3140px;"></path>
    </svg>
    default slot
  </div>
<!--  posr + w100 + h100-->
</template>

<script>
  export default {
    name: "Circle.vue"
  }
</script>

<style scoped>

</style>
