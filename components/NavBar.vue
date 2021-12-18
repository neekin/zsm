<template>
  <div class="navbar">
    <NuxtLogo />
    <el-menu
      class="el-menu"
      mode="horizontal"
      default-active="1"
      active-text-color="#fff"
      text-color="#fff"
    >
      <el-menu-item index="1">首页</el-menu-item>
      <el-menu-item index="2">关于公司</el-menu-item>
      <el-menu-item index="3">项目服务</el-menu-item>
      <el-menu-item index="4">产品中心</el-menu-item>
      <el-menu-item index="5">新闻动态</el-menu-item>
      <el-menu-item index="6">联系我们</el-menu-item>
    </el-menu>
  </div>
</template>

<script>
import NuxtLogo from './NuxtLogo.vue'
export default {
  name: 'NavBar',
  comments: {
    NuxtLogo,
  },
}
</script>

<style scoped lang="scss">
.navbar {
  min-width: 1200px;
  width: 100%;
  max-width: 100%;
  display: flex;
  margin: 10px auto 0;
  justify-content: space-between;
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  right: 0;
  overflow: scroll;
  .el-menu {
    border: none;
    background-color: unset;
    .el-menu-item {
      padding: 0;
      margin-right: 78px;
    }
  }
}
</style>
