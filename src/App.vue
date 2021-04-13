<template>
  <div id="app">
    <van-uploader v-model="fileList" :after-read="afterRead">
      <template #default>default slot</template>
      <template #preview-cover="{ file }">
       
        <div class="preview-cover van-ellipsis" v-if="file">{{ file.name }}url</div>
         <div class="preview-cover van-ellipsis" v-else>{{ file }}</div>
      </template>
    </van-uploader>
  </div>
</template>
<script>
export default {
  data() {
    return {
      fileList: [
        { url: 'https://img01.yzcdn.cn/vant/leaf.jpg' },
        {
          url: 'https://img01.yzcdn.cn/vant/sand.jpg',
          deletable: true,
          beforeDelete: () => {
            Toast('自定义单个预览图片的事件和样式');
          },
        },
        {
          url: 'https://img01.yzcdn.cn/vant/tree.jpg',
          deletable: true,
          imageFit: 'contain',
          previewSize: 120,
        }
      ]
    };
  },
  methods: {
    afterRead:function(a, b, c){
      console.log(a, b, c);
    }
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
