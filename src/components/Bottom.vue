<template>
  <div class="bottom">
    <a href="#">关于百度</a>
    <a href="#">About Baidu</a>
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
.bottom {
  display: flex;
  justify-content: center;
  align-self: flex-end;
  /* position: absolute;
  bottom: 1px; */
}
a {
  margin-left: 30px;
  text-decoration: none;
  color: #d8d8d8;
  font-size: 12px;
}
a:hover {
  color: black;
}
</style>