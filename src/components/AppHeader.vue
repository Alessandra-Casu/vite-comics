<script>
import NavBar from "./NavBar.vue";

export default {
  data() {
    return {
      logoImgName: "dc-logo.png",
    };
  },
  methods: {
    getImagePath(img) {
      return new URL(`../assets/img/${img}`, import.meta.url).href;
    },
  },
  components: {
    NavBar,
  },
};
</script>

<template>
  <header>
    <div class="headBox">
      <img class="img-logo" :src="getImagePath(logoImgName)" alt="logo" />
      <NavBar></NavBar>
    </div>
  </header>

  <!-- <ul class="list d-flex">
      <li><a href="#">CHARACTERS</a></li>
      <li><a href="#">COMICS</a></li>
      <li><a href="#">MOVIES</a></li>
      <li><a href="#">TV</a></li>
      <li><a href="#">GAMES</a></li>
      <li><a href="#">COLLECTIBLES</a></li>
      <li><a href="#">VIDEOS</a></li>
      <li><a href="#">FANS</a></li>
      <li><a href="#">NEWS</a></li>
      <li><a href="#">SHOP</a></li>
    </ul> -->
</template>

<style lang="scss" update>
header {
  height: 90px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.headBox {
  width: 80%;
  margin: auto;
  display: flex;
}

.img-logo {
  height: 70px;
}
</style>
