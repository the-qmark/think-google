<template>
  <div class="container">
    <div class="intro_bg">
      <img class="bg" src="~assets/images/intro_bg.svg" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  layout: "myDefault",
  name: "IndexPage",
};
</script>

<style lang="scss" scoped>
.container {
  position: relative;
  //height: auto;
  margin-top: 50px;
}

.intro_bg {
  // background-image: url(~assets/images/intro_bg.svg);
  //background: url("@/assets/images/intro_bg.svg");
  background-color: rgb(40, 199, 75);
  // width: 500px;
  // padding-top: 146px;

  // width: 1266px;
  //height: auto;
  // background-position: center center;
  // background-repeat: no-repeat;

  // background-attachment: fixed;
  // background-size: cover;
  // margin-left: auto;
  // margin-right: auto;
}

.bg {
  // background-color: rgb(65, 60, 60);
  height: auto;
  position: relative;
  top: 0;
  left: -25px;
}
</style>