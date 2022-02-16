<template>
  <div class="container">
    <div class="intro_bg">
      <!-- <img src="~assets/images/intro_bg.svg" alt="" /> -->
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
.intro_bg {
  background-image: url(~assets/images/intro_bg.svg);
  //background: url("@/assets/images/intro_bg.svg");
  background-color: rgb(40, 199, 75);
  // width: 500px;
  // padding-top: 146px;
  margin-top: 50px;
  // width: 1266px;
  height: 561px;
  // background-position: center center;
  background-repeat: no-repeat;
  // background-attachment: fixed;
  // background-size: cover;

  // margin-left: auto;
  // margin-right: auto;
}
</style>