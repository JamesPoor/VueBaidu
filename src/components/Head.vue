<template>
  <div class="top">
    <div class="top-left">
      <a href="#">新闻</a>
      <a href="#">hao123</a>
      <a href="#">地图</a>
      <a href="#">直播</a>
      <a href="#">视频</a>
      <a href="#">贴吧</a>
      <a href="#">学术</a>
      <a href="#">更多</a>
    </div>
    <div class="top-right">
      <i>设置</i>
      <button class="login">登录</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>
<style scoped>
.top {
  width: 100%;
  margin-top: 20px;
  display: flex;
}
.top-left a {
  color: black;
  text-decoration: none;
  padding-left: 30px;
  font-size: 14px;
}
.top-left a:hover {
  color: blue;
}
.top-right {
  position: absolute;
  right: 25px;
}
.top-right i,
span {
  margin-right: 30px;
  font-style: normal;
  font-size: 14px;
}
.login {
  background-color: #5170ea;
  width: 48px;
  height: 25px;
  border: 0;
  color: #ffff;
  border-radius: 5px;
}
</style>