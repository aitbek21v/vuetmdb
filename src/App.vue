<template>
 <HeaderComponent/>
  <Herosection/>
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent";
import Herosection from "@/components/Herosection";
export default {
  name: 'App',
  components: {
    HeaderComponent,
    Herosection
  }
}
</script>

<style>
body {
  background: #1E2538;
}
</style>
