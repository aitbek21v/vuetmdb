<template>
<div id="hero">
  <ConTainer>
    <h1>Популярные</h1>
    <div class="hero">

    </div>
  </ConTainer>
</div>
</template>

<script>
import ConTainer from "@/ConTainer";
export default {
  name: "HeroSection",
  components: {ConTainer}
}
</script>

<style scoped lang="scss">
#hero {
  padding-top: 150px;
  h1 {
    color: #FFF;
    font-family: Qanelas;
    font-size: 40px;
    font-style: normal;
    font-weight: 900;
    line-height: normal;
  }
  .hero {

  }
}
</style>