<script></script>

<template>
  <div
    class="nav-bar container d-flex justify-content-between align-items-center p-3"
  >
    <img class="img-logo" src="../assets/img/dc-logo.png" alt="logo" />
    <ul class="list d-flex">
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
    </ul>
  </div>
</template>

<style lang="scss" update>
.nav-bar {
  height: 90px;
  .img-logo {
    display: inline-block;
    height: 70%;
  }
}

.list {
  list-style: none;
  a {
    text-decoration: none;
    color: black;
    padding-right: 0.5rem;
  }
}
</style>
