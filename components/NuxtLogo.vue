<template>
  <div class="logo">
    <img v-holder="{ img: '72x60', theme: 'vine', text: 'Logo' }" />
    用科技改变世界，共创未来！
  </div>
</template>

<style lang="scss" scoped>
.logo {
  display: flex;
  align-items: center;
  font-size: 20px;
  font-family: Microsoft YaHei;
  font-weight: 300;
  color: #ffffff;
  img {
    margin-right: 10px;
    border-radius: 10px;
    margin-left: 60px;
  }
}
</style>
