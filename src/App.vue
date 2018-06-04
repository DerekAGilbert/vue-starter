<template>
  <div class="app-scoped">
    <nav id="nav">
      <router-link to="/about">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/portfolio">Portfolio</router-link>
      <router-link to="/contact">Contact</router-link>
    </nav>
    <div class="">
      <router-view/>
    </div>
  </div>
</template>

<style scoped lang="scss">
.app-scoped {
  #nav {
    display: flex;
    width: 100%;
    justify-content: center;
    a {
      margin: 10px 5px;
    }
  }
}

</style>
