<template>
  <div class="container">
    <div class="footer">
      <button class="footer__wrapper">BUTTON 1</button>
      <button class="footer__wrapper">BUTTON 2</button>
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
  /* background-color: rgb(232, 248, 141); */
  margin-top: 50px;
  height: 100px;
  display: flex;
  justify-content: space-between;
}

.footer__wrapper {
  background: transparent;
  border-color: #4285f4;
  color: #4285f4;
  /* color: #fff; */
  width: 150px;
  text-align: center;
  vertical-align: middle;
  line-height: 100px;
  min-width: 200px;
  margin-right: 20px;
  font-weight: 600;
  height: 69px;
  font-size: 18px;
  line-height: 25px;
  box-sizing: border-box;
  border-radius: 10px;
  text-align: center;
}
</style>