<template>
  <div class="container">
    <div class="box-button">
      <button>test</button>
    </div>

    <main>
      <div class="card" v-for="(comic, index) in comicsList" :key="index">
        <img :src="comic.thumb" />
        <p>{{ comic.series }}</p>
      </div>
    </main>

    <div class="box-button">
      <button>test</button>
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
.container {
  background-color: #1c1c1c;

  .box-button {
    width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: center;

    button {
    }
  }

  main {
    width: 1200px;
    margin: 0 auto;
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
}
</style>
