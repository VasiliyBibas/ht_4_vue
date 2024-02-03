<template>
  <Main/>
  <Blog/>
  <BlogDetails/>

</template>

<script>
import Main from './components/Main.vue';
import Blog from './components/Blog.vue';
import BlogDetails from './components/BlogDetails.vue';



export default {
  name: 'App',
  components: {
    Main,
    Blog,
    BlogDetails
}
}
</script>

<style lang="scss">

</style>
