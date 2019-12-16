<template>
  <div class="home">
    <h1>开始搭建项目啦，哈哈哈</h1>
    <van-grid>
      <van-grid-item icon="photo-o" text="文字" />
      <van-grid-item icon="photo-o" text="文字" />
      <van-grid-item icon="photo-o" text="文字" />
      <van-grid-item icon="photo-o" text="文字" />
      </van-grid>
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    // HelloWorld
  }
}
</script>
<style scoped>
  h1{
    font-size:34px;
    font-family:Source Han Sans CN;
    font-weight:500;
    /* border-bottom: 1px solid #000; */
  }
</style>
