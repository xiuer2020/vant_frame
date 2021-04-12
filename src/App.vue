<template>
  <div id="app">
    <van-field v-model="value" label="文本" placeholder="请输入用户名">
      <template #label>label slot</template>
      <template #input>input slot</template>
      <template #left-icon>left-icon slot</template>
      <template #right-icon>right-icon slot</template>
      <template #button>button slot</template>
      <template #extra>extra slot</template>
    </van-field>
  </div>
</template>
<script>
  export default {
    data: () => ({

    }),
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

  }
</style>
