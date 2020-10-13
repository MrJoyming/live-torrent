<template>
  <el-container>
  <el-header><Header></Header></el-header>
  <el-main><Mian></Mian></el-main>
  <el-footer><Footer></Footer></el-footer>
</el-container>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/header'
import Mian from './components/mian'
import Footer from './components/footer'
export default {
  name: 'App',
  components: {
    Header,
    Mian,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
