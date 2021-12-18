<template>
  <div class="companyprofile">
    <div class="proimg">
      <img v-holder="'img=100px100p?auto=yes&theme=social&text=Full width'" />
    </div>
    <div class="profile">
      <div class="title">
        公司简介
        <div class="subtitle">Company profile</div>
      </div>
      <div class="context">
        我们是一家致力于帮助中小微企业利用本地商圈资源，重新发掘自身的知识学习与输出能力，运用好抖音流量工具，通过打造商业IP，实现区域圈商经济，从而帮助中小微企业进行运营模式转型，创造出更新更高更大价值的互联网公司。
      </div>
      <div class="context">
        <p>愿景 - 创造出更新更高更大价值的互联网公司。</p>
        <p>使命 - 创造出更新更高更大价值的互联网公司。</p>
        <p>价值观 - 创造出更新更高更大价值的互联网公司。</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.companyprofile {
  display: flex;
  max-width: 1920px;
  min-width: 1200px;
  margin: 0 auto;
  padding: 0 40px 150px;
  justify-content: space-between;
  .proimg {
    width: 800px;
    height: 520px;
    border-radius: 25px;
    overflow: hidden;
    margin-right: 56px;
  }
  .profile {
    flex: 1;
    height: 520px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    overflow: hidden;

    .title {
      font-size: 48px;
      font-family: Microsoft YaHei;
      font-weight: 400;
      color: #000000;
      .subtitle {
        font-size: 24px;
      }
    }
    .context {
      font-size: 30px;
      font-family: 'MicrosoftYaHeiLight';
      p {
        margin-top: 20px;
        font-size: 36px;
      }
    }
  }
}
@media screen and (max-width: 1750px) {
  .companyprofile {
    display: flex;
    max-width: 1920px;
    min-width: 1200px;
    margin: 0 auto;
    padding: 0 30px;
    box-sizing: border-box;
    justify-content: space-between;
    .proimg {
      width: 600px;
      height: 390px;
      border-radius: 25px;
      overflow: hidden;
      margin-right: 56px;
    }
    .profile {
      width: 600px;
      height: 390px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      overflow: hidden;

      .title {
        font-size: 24px;
        font-family: Microsoft YaHei;
        font-weight: 400;
        color: #000000;
        .subtitle {
          font-size: 12px;
        }
      }
      .context {
        font-size: 15px;
        font-family: 'MicrosoftYaHeiLight';
        p {
          margin-top: 20px;
          font-size: 18px;
        }
      }
    }
  }
}
</style>
