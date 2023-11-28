<template>
  <div id="app">
    <HeaderComp/>
    <BlogDetails/>
    <FooterComp/>
  </div>
</template>

<script>
import BlogDetails from './components/BlogDetails.vue'
import HeaderComp from './components/HeaderComp.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    BlogDetails,
    HeaderComp,
    FooterComp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Jost, sans-serif;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.center {
  width: 1200px;
  margin: 0 auto;
}

a {
  text-decoration: none;
}
</style>
