<template>
  <header>
    <div class="logo">
      <img src="../assets/dc-logo.png" alt="logo dc" />
    </div>

    <nav>
      <ul>
        <li v-for="link in navLinks" :key="link.id">
          <a :href="link.url">
            {{ link.label }}
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  props: {
    navLinks: Array,
  },
};
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

    ul {
      font-size: 20px;
      line-height: 70px;
      display: flex;
      justify-content: center;

      li {
        padding: 0 10px;
        cursor: pointer;

        a {
          color: #000;
          font-weight: bold;

          &:hover {
            color: $dc-blue;
            padding-bottom: 35px;
            border-bottom: 5px solid $dc-blue;
          }
        }
      }
    }
  }
}
</style>
