<template>
  <div id="app">
    <van-tabs v-model="active">
      <template #nav-left>nav-left slot</template>
      <template #nav-right>nav-right slot</template>

      <van-tab title="标签 1">
        <template #default>default slot</template>
        <template #title>title slot</template>
      </van-tab>
      <van-tab title="标签 2">内容 2</van-tab>
      <van-tab title="标签 3">内容 3</van-tab>
      <van-tab title="标签 4">内容 4</van-tab>
    </van-tabs>
  </div>
</template>
<script>
  import {Toast} from 'vant';

  export default {
    data() {
      return {
        active: 0
      };
    },
  };
</script>
<style lang="less">
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    padding-top: 50px;
    background-color: #ddd;
    min-height: 1000vh;
  }

  .preview-cover {
    position: absolute;
    bottom: 0;
    box-sizing: border-box;
    width: 100%;
    padding: 4px;
    color: #fff;
    font-size: 12px;
    text-align: center;
    background: rgba(0, 0, 0, 0.3);
  }
</style>
