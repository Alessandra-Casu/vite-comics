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
    <img :src="thumbImg" :alt="type" />
    <h5>{{ type }}</h5>
  </div>
</template>

<style lang="scss" scoped>
.card {
  width: 15%;
  text-align: center;
  color: black;
  display: flex;
}

img {
  width: 100%;
  height: 50%;
}
</style>
