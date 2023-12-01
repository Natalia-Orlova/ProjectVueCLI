<template>
  <div id="app">
    <HeaderComp/>
  <!-- <BlogDetails/> -->
    <ProjectsPage/>
    <FooterComp/>
  </div>
</template>

<script>
// import BlogDetails from './components/BlogDetails.vue'
import HeaderComp from './components/HeaderComp.vue'
import FooterComp from './components/FooterComp.vue'
import ProjectsPage from './components/ProjectsPage.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    // BlogDetails,
    ProjectsPage,
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
