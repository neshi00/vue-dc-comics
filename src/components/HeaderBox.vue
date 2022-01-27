<template>
  <header>
    <div class="logo">
      <img src="../assets/dc-logo.png" alt="logo dc" />
    </div>

    <nav>
      <ul>
        <li>
          <a href="#">CHARACTERS</a>
        </li>
        <li>
          <a href="#">COMICS</a>
        </li>
        <li>
          <a href="#">MOVIE</a>
        </li>
        <li>
          <a href="#">TV</a>
        </li>
        <li>
          <a href="#">GAMES</a>
        </li>
        <li>
          <a href="#">COLLECTIBLES</a>
        </li>
        <li>
          <a href="#">VIDEOS</a>
        </li>
        <li>
          <a href="#">FANS</a>
        </li>
        <li>
          <a href="#">NEWS</a>
        </li>
        <li>
          <a href="#">SHOP</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

header {
  width: 1200px;
  display: flex;
  margin: 0 auto;
  padding: 20px 0;

  .logo {
    width: 30%;

    img {
      height: 70px;
      vertical-align: middle;
    }
  }

  nav {
    width: 70%;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;

    ul {
      font-size: 20px;
      line-height: 70px;
      display: flex;
      justify-content: center;

      li {
        list-style: none;
        padding: 0 5px;
        cursor: pointer;

        a {
          text-decoration: none;
          color: #000;
          font-weight: bold;
        }
      }
    }
  }
}
</style>
