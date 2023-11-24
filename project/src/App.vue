<template>
  <div id="app">
    <BlogDetails/>
  </div>
</template>

<script>
import BlogDetails from './components/BlogDetails.vue'

export default {
  name: 'App',
  components: {
    BlogDetails
  }
}
</script>

<style lang="scss">
#app {
  font-family: Jost, sans-serif;
  margin-top: 96px;
  margin-bottom: 96px;
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
