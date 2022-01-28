<template>
  <div class="macro-container">
    <div class="container">
      <button>SIGN-UP NOW!</button>
      <div class="social-box">
        <span>FOLLOW US</span>
        <img src="../assets/footer-facebook.png" alt="" />
        <img src="../assets/footer-twitter.png" alt="" />
        <img src="../assets/footer-youtube.png" alt="" />
        <img src="../assets/footer-pinterest.png" alt="" />
        <img src="../assets/footer-periscope.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.macro-container {
  background-color: #303030;

  .container {
    width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    padding: 30px;

    button {
      border: 2px solid $dc-blue;
      padding: 15px;
      font-weight: bold;
      color: #fff;
      background-color: #303030;
      cursor: pointer;
    }
    .social-box {
      display: flex;
      align-items: center;

      span {
        padding: 0 10px;
        color: $dc-blue;
        font-size: 20px;
        font-weight: bold;
        cursor: pointer;
      }
      img {
        padding: 0 5px;
        cursor: pointer;
      }
    }
  }
}
</style>
