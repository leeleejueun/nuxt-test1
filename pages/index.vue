<template>
  <div>
    <header>
      <nuxt-link to="/">Home</nuxt-link>
      <nuxt-link to="/about">About</nuxt-link>
    </header>
    여기는 유미세포마을
    <div class="image">
      <img src="@/assets/img/출출이.jpg">
      <img src="@/assets/img/감성세포.jpg">
      <img src="@/assets/img/배달세포.jpg">
      <img src="@/assets/img/본심이.jpg">
      <img src="@/assets/img/응큼이.jpg">
      <img src="@/assets/img/패션세포.jpg">
    </div>
    <TestContent />
  </div>
</template>

<script>

export default {
    name: "IndexPage",
}
</script>

<style lang="scss" scoped>
  .image{border: 5px solid red;}
</style>