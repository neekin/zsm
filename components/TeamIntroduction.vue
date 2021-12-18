<template>
  <div class="teamintroduction">
    <div class="title">
      团队介绍
      <div class="subtitle">Team introduction</div>
    </div>

    <el-row class="teams">
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6"
        ><div class="preimg">
          <img
            v-holder="{
              img: '100px100p',
              theme: 'sky',
              text: 'gitlab',
              auto: 'yes',
            }"
          />
          <div class="info">王同学</div>
          <div class="content">
            清华大学毕业
            <p>五道口小卖部创始人</p>
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
.teamintroduction {
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
    width: 360px;
    height: 360px;
    margin: 40px auto;
    padding: 100px 0;
    img {
      border-radius: 50%;
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
