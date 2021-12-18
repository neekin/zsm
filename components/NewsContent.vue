<template>
  <div class="news">
    <div class="title">
      新闻动态
      <div class="subtitle">News information</div>
    </div>
    <el-row class="projects">
      <el-col :span="12"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="content">
            长三角地区汇聚了孵化独角兽及未来独角兽的各种关键要素，经济实力强劲，消费能力强，拥有2.25亿人口。
          </div>
        </div>
      </el-col>
      <el-col :span="12"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="content">
            长三角地区汇聚了孵化独角兽及未来独角兽的各种关键要素，经济实力强劲，消费能力强，拥有2.25亿人口。
          </div>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.news {
  padding-top: 160px;
  padding-bottom: 170px;
  .title {
    font-size: 48px;
    font-family: Microsoft YaHei;
    font-weight: 400;
    color: #000000;
    text-align: center;
    .subtitle {
      font-size: 24px;
    }
  }

  .preimg {
    width: 850px;
    height: 580px;
    margin: 40px auto 0;
    img {
      border-radius: 25px;
      width: 100%;
    }
    .info {
      font-size: 36px;
      margin-top: 40px;
      text-align: center;
    }
    .content {
      font-size: 24px;
      text-align: center;
    }
  }
  .projects {
    max-width: 100%;
    min-width: 1200px;
  }
}
</style>
