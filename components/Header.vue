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
    <div class="header__wrapper">
      <button class="button header__btn google-blue dark-text outline">
        Log in
      </button>
      <button class="button header__btn google-blue dark-text fill">
        Register
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
$text-color: rgb(140, 0, 255);

.button.google-blue.outline {
  background: transparent;
  border-color: #4285f4;
  color: #4285f4;
}

.button.google-blue.outline:hover {
  background: rgba(66, 133, 244, 0.2);
  border-color: #1266f1;
}

.button.google-blue {
  background: #4285f4;
  border-color: transparent;
  padding: 16px 30px;
  border-width: 1px;
  font-size: 18px;
  line-height: 25px;
}
.button.google-blue:hover {
  background: #1266f1;
}

.button.dark-text {
  color: #fff;
  text-decoration: none;
}

.header__btn {
  min-width: 200px;
  margin-right: 20px;
  font-weight: 600;
  height: 69px;
  font-size: 18px;
  line-height: 25px;
}

.header__btn:last-of-type {
  margin-right: 0;
}

.button {
  position: relative;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  border: 1px solid transparent;
  box-sizing: border-box;
  border-radius: 10px;
  text-align: center;
  cursor: pointer;
  box-shadow: none;
  transition: 0.25s ease-in-out, color 0.25s ease-in-out;
  white-space: nowrap;
}

.header {
  /* background-color: rgb(238, 118, 118);*/
  //background: transparent;
  padding-top: 20px;
  padding-bottom: 20px;
  display: flex;
  justify-content: space-between;
  /*z-index: 51;*/
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  // background-color: rgb(199, 214, 66);
}

.container {
  //max-width: 1166px;
  //max-width: 100%;

  width: 1166px;
  padding-left: 100px;
  padding-right: 100px;
  margin-left: auto;
  margin-right: auto;
}

.header__logo {
  margin: 0 60px 0 0;
}

.header__wrapper {
  // background-color: rgb(154, 167, 81);
  display: flex;
  align-items: center;
  height: 70px;
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

.header__nav-item a {
  color: #000;

  text-decoration: none;
}

.header__nav-item a:hover {
  color: rgb(82, 82, 83);
}

// body {
//   font-family: Open Sans, Arial, sans-serif;
//   font-size: 16px;
//   line-height: 1.42;
// }
</style>