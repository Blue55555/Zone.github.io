<template>
  <div class="container">
    <div class="navigation">
      <div>1233</div>
      <div class="nav-bgroup">
        <div class="nav-button">
          <div class="line line1"></div>
          <div class="line line2"></div>
          <div class="line line3"></div>
        </div>
        <div class="nav-button"></div>
        <div class="nav-button"></div>
      </div>
    </div>
    <div class="bg1"></div>
    <div class="txt"></div>
  </div>
</template>

<script>
// import { useRoute, useRouter } from "vue-router";sudo npm rebuild node-sass
export default {
  name: "Header",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.txt {
  width: 100%;
  height: 1000px;
  text-align: center;
}
.bg1 {
  width: 100%;
  height: 800px;
  background-size: cover;
  background-attachment: fixed;
  text-align: center;
  color: #fff;
  background-position: center center;
  background-repeat: no-repeat;
}
.bg1 {
  background-image: url(https://pica.zhimg.com/80/v2-fc7dd601bd31983941b6df35ebdb8a50_1440w.jpg);
}

.navigation {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 75px;
  display: flex;
  justify-content: space-between;
  background-color: #fff;
}

.line {
  position: absolute;
  top: 7px;
  left: 50%;
  width: 28px;
  margin-left: -15px;
  height: 2px;
  background: #666;
  transition: all 0.2s ease;
}

.line1 {
  top: 16px;
}

.line2 {
  top: 21px;
}

.line3 {
  top: 25px;
}

.nav-bgroup {
}

.nav-button {
  width: 35px;
  height: 35px;
  position: relative;
}
</style>
