<template>
  <div class="MembersCarousel">
    <el-carousel class="Carousel">
      <el-carousel-item v-for="item in 4" :key="item">
        <img v-holder="{ img: '100px780', theme: themes[item], text: item }" />
      </el-carousel-item>
    </el-carousel>
    <div class="slogan">
      我们的愿景 ● 未来独角兽集聚一线城市，长三角地区群星璀璨
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      themes: ['vue', 'github', 'sky', 'lava'],
    }
  },
}
</script>
<style scoped lang="scss">
.MembersCarousel {
  position: relative;
  .Carousel {
    top: -70px;
    z-index: 0;
    max-width: 100%;
    min-width: 1200px;
    ::v-deep .el-carousel__container {
      height: 780px;
    }
  }
  .slogan {
    min-width: 1200px;
    max-width: 100%;
    height: 120px;
    background: #0d215c;
    font-size: 36px;
    font-family: Microsoft YaHei;
    font-weight: 300;
    color: #ffffff;
    line-height: 42px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    top: -70px;
  }
}
</style>
