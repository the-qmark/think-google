<template>
  <div class="container">
    <div class="footer">
      <div class="footer__wrapper">BUTTON 1</div>
      <div class="footer__wrapper">BUTTON 2</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyFooter",
};
</script>

<style scoped>
.footer {
  background-color: rgb(232, 248, 141);
  margin-top: 50px;
  height: 100px;
  display: flex;
  justify-content: space-between;
}

.footer__wrapper {
  background-color: rgb(114, 36, 124);
  color: #fff;
  width: 150px;
  text-align: center;
  vertical-align: middle;
  line-height: 100px;
}
</style>