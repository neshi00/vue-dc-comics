<template>
  <div class="macro-container">
    <div class="container">
      <ul>
        <li>
          <a href="#">
            <img src="../assets/buy-comics-digital-comics.png" alt="" />
            <span>DIGITAL COMICS</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-comics-merchandise.png" alt="" />
            <span>DC MERCHANDISE</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-comics-subscriptions.png" alt="" />
            <span>SUBSCRIPTION</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-comics-shop-locator.png" alt="" />
            <span>COMIC SHOP LOCATOR</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-dc-power-visa.svg" alt="" />
            <span>DC POWER VISA</span>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.macro-container {
  background-color: $dc-blue;
  padding: 40px 0;

  .container {
    width: 1200px;
    margin: 0 auto;

    ul {
      display: flex;
      justify-content: space-between;

      li {
        list-style: none;
        a {
          text-decoration: none;
          color: #fff;
          font-weight: bold;

          img {
            height: 50px;
            vertical-align: middle;
            padding: 0 15px;
          }
          span {
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            font-size: 10px;
          }
        }
      }
    }
  }
}
</style>
