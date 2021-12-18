<template>
  <div class="productioncenter">
    <div class="title">
      产品中心
      <div class="subtitle">Project Center</div>
    </div>
    <el-row class="projects">
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: '产品图片',
              auto: 'yes',
            }"
          />
          <div class="info">产品浏览包</div>
          <div class="content">
            长三角地区汇聚了孵化独角兽及未来独角兽的各种关键要素，经济实力强劲，消费能力强，拥有2.25亿人口。
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: '产品图片',
              auto: 'yes',
            }"
          />
          <div class="info">产品浏览包</div>
          <div class="content">
            长三角地区汇聚了孵化独角兽及未来独角兽的各种关键要素，经济实力强劲，消费能力强，拥有2.25亿人口。
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: '产品图片',
              auto: 'yes',
            }"
          />
          <div class="info">产品浏览包</div>
          <div class="content">
            长三角地区汇聚了孵化独角兽及未来独角兽的各种关键要素，经济实力强劲，消费能力强，拥有2.25亿人口。
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: '产品图片',
              auto: 'yes',
            }"
          />
          <div class="info">产品浏览包</div>
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
.productioncenter {
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
    width: 400px;
    height: 400px;
    margin: 40px auto;
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
      margin-top: 50px;
      text-align: center;
    }
  }
  .projects {
    max-width: 100%;
    min-width: 1200px;
  }
}
</style>
