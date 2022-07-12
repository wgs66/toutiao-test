<template>
  <div id="app">
    <!-- 路由出口 -->
    <router-view />
    <h1>hahah</h1>
    <div>
      <i class="toutiao toutiao-shipin"></i>
    </div>
    <div class="box"></div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
.box {
  height: 100px;
  width: 200px;
  background-color: pink;
}
</style>
