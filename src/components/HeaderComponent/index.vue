<template>
<div id="header">
  <ConTainer>
    <div class="header">
      <img src="../../assets/logo.svg" alt="" width="200">
      <nav>
        <a href="#">Афиша</a>
        <a href="#">Медиа</a>
        <a href="#">Фильмы</a>
        <a href="#">Актёры</a>
        <a href="#">Новости</a>
        <a href="#">Подборки</a>
        <a href="#">Категории</a>

      </nav>
      <button>Войти</button>
    </div>
  </ConTainer>
</div>
</template>

<script>
import ConTainer from "@/ConTainer";
export default {
  name: "HeaderComponent",
  components: {ConTainer}
}
</script>

<style scoped lang="scss">
#header {
  .header {
    display: flex;
    align-items: center;justify-content: space-between;
    nav {
      a {
        color: #FFF;
        font-size: 13px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
        padding: 0 30px;
        font-family: sans-serif;
      }
    }
    button {
      width: 100px;
      height: 42px;
      flex-shrink: 0;
      border-radius: 10px;
      background: #3657CB;
      box-shadow: 0 0 15px 0 rgba(72, 113, 255, 0.80);
      color: white;
      border: none;
    }
  }
}
</style>