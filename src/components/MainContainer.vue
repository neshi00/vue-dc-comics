<template>
  <div class="macro-container">
    <div class="container">
      <button class="current-series">CURRENT SERIES</button>

      <main>
        <div class="card" v-for="(comic, index) in comicsList" :key="index">
          <img :src="comic.thumb" />
          <p>{{ comic.series }}</p>
        </div>
      </main>

      <div class="box-load">
        <button class="load-more">LOAD MORE</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    comicsList: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.macro-container {
  background-color: #1c1c1c;

  .container {
    width: 1200px;
    margin: 0 auto;
  }

  .current-series {
    background-color: $dc-blue;
    padding: 5px 20px;
    font-size: 30px;
    margin: -20px 0;
  }

  main {
    padding: 50px 0;
    display: flex;
    flex-wrap: wrap;

    .card {
      width: calc(100% / 6);
      padding: 10px;

      p {
        color: #fff;
        padding: 20px 0;
      }
    }
  }

  .box-load {
    padding: 20px 0;
    display: flex;
    justify-content: center;

    .load-more {
      background-color: $dc-blue;
      padding: 7px 21px;
      font-size: 7px;
    }
  }
}
</style>
