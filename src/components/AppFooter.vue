<script></script>

<template>
  <div class="footer">
    <div
      class="sub-footer container d-flex justify-content-between align-items-center p-3"
    >
      <button class="btn">SIGN-UP NOW!</button>
      <div>
        <div class="follow d-flex">
          <h4>FOLLOW US</h4>
          <div class="icons p-1">
            <img src="../assets/img/footer-facebook.png" alt="fb" />
            <img src="../assets/img/footer-twitter.png" alt="" />
            <img src="../assets/img/footer-youtube.png" alt="" />
            <img src="../assets/img/footer-pinterest.png" alt="" />
            <img src="../assets/img/footer-periscope.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" update>
@use "./../assets/styles/partials/variables" as *;
.footer {
  height: 100px;
  background-color: $bg-footer;
  .btn {
    color: white;
    border: 2px solid $blue-comics;
    padding: 0.5rem;
  }
}
.sub-footer {
  height: 100%;
  .follow {
    h4 {
      color: $blue-comics;
    }
  }
}
</style>
