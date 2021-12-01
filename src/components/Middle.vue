<template>
  <div class="middle">
    <div>
      <div class="sou">
        <img
          class="baidupng"
          src="https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png"
          alt=""
        />
      </div>

      <div>
        <input type="text" />
        <button class="button">百度一下</button>
      </div>
    </div>
    <div class="baidu-resou"></div>
    <div class="baidu-huanyihuan"></div>
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
.middle {
  width: 100%;
  display: flex;
  justify-content: center;
}
.baidupng {
  width: 250px;
  padding-bottom: 20px;
}
input {
  width: 545px;
  height: 40px;
  border-radius: 10px 0 0 10px;
  outline: none;
  border: 2px solid#d8d8d8;
}
input:focus {
  border: 2px solid #5170ea;
}
.button {
  background-color: #5170ea;
  border: 0;
  border-radius: 0px 10px 10px 0px;
  width: 110px;
  height: 46px;
  margin-left: -2px;
  color: #fff;
  font-size: 16px;
  position: relative;
  top: 2px;
}
.sou {
  display: flex;
  justify-content: center;
}
</style>