<template>

  <div class="home">
    <h1>Home <span>page</span></h1>
    <NuxtLink to="/about">
      About (internal link that belongs to the Nuxt App)
    </NuxtLink>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style lang="scss" scoped>
span{
  font-size: 24px;
}
</style>