<script>
export default {
  props: {
    thumbImg: {
      type: String,
      required: false,
      default: "indirizzo immagine di default",
    },
    price: {
      type: String,
      required: true,
    },
    series: {
      type: String,
      required: false,
    },
    type: {
      type: String,
      required: false,
    },
  },
};
</script>

<template>
  <div class="card">
    <img :src="thumbImg" :alt="series" />
    <h2>{{ series }}</h2>
    <h3>{{ type }}</h3>
  </div>
</template>

<style lang="scss" update>
.card {
  width: 50%;
  text-align: center;
  border: 2px solid salmon;
  background-color: gray;
  color: black;
}

img {
  width: 100%;
  height: 50%;
}
</style>
