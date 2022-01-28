<template>
  <div class="macro-container">
    <div class="container">
      <div class="links">
        <ul>
          <a href="#"><h3>DC COMICS</h3></a>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">Tv</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
          <a href="#"><h3>SHOP</h3></a>
          <li><a href="#">Shop DC</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
        </ul>

        <ul>
          <a href="#"><h3>DC</h3></a>
          <li><a href="#">Terms Of Use</a></li>
          <li><a href="#">Privacy policy (New</a></li>
          <li><a href="#">Ad Choices</a></li>
          <li><a href="#">Advertising</a></li>
          <li><a href="#">Jobs</a></li>
          <li><a href="#">Subscriptions</a></li>
          <li><a href="#">Talent Workshops</a></li>
          <li><a href="#">CPSC Certificates</a></li>
          <li><a href="#">Ratings</a></li>
          <li><a href="#">Shop Help</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>

        <ul>
          <a href="#"><h3>SITES</h3></a>
          <li><a href="#">DC</a></li>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC Power Visa</a></li>
        </ul>
      </div>

      <div class="logo-bg">
        <img src="../assets/dc-logo-bg.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.macro-container {
  background: url(../assets/footer-bg.jpg);
  background-size: cover;

  .container {
    width: 1200px;
    margin: 0 auto;
    display: flex;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    color: #fff;

    .links {
      display: flex;
      width: 70%;
      ul {
        padding: 20px;

        h3 {
          padding: 10px 0;
          font-size: 25px;
        }
        li {
          list-style: none;

          a {
            color: gray;
            text-decoration: none;

            &:hover {
              color: #fff;
            }
          }
        }
      }
    }
    .logo-bg {
      width: 30%;

      img {
        height: 300px;
      }
    }
  }
}
</style>
