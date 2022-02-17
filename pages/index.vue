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
  margin-left: auto;
  margin-right: auto;
}

.bg {
  // background-color: rgb(65, 60, 60);
  height: auto;
  position: relative;
  top: 0;
  left: -25px;
}
</style>