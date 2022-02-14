<template>
  <div class="header container">
    <div class="header__wrapper">
      <a href="/"
        ><img src="~assets/images/google.svg" alt="GOOGLE" class="header__logo"
      /></a>
      <div class="header__nav">
        <ul class="header__nav-list">
          <li class="header__nav-item">
            <a href="/">Schedule</a>
          </li>
          <li class="header__nav-item">
            <a href="/">Speakers</a>
          </li>
          <li class="header__nav-item">
            <a href="/">Participants</a>
          </li>
          <li class="header__nav-item">
            <a href="/">Store</a>
          </li>
        </ul>
      </div>
    </div>
    <div class="header__wrapper">BUTTONS</div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
$text-color: rgb(140, 0, 255);

.header {
  background-color: rgb(238, 118, 118);
  //background: transparent;
  padding-top: 20px;
  padding-bottom: 20px;
  display: flex;
  justify-content: space-between;
  z-index: 51;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
}

.container {
  max-width: 70%;
  //width: 1366px;
  padding-left: 100px;
  padding-right: 100px;
  margin-left: auto;
  margin-right: auto;
}
.header__logo {
  margin: 0 60px 0 0;
}

.header__wrapper {
  background-color: rgb(81, 167, 167);
  display: flex;
  align-items: center;
}

.header__nav {
  display: flex;
  align-content: center;
}

.header__nav-list {
  display: flex;
  align-items: center;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.header__nav-item {
  margin-right: 40px;
}
</style>