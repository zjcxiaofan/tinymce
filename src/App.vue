<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <tinymce :height='400' v-model='content'></tinymce>
  </div>
</template>

<script>
import tinymce from './components/tinymce/tinymce'

export default {
  name: 'App',
  components: {
    tinymce
  },
  data() {
    return {
      content: `<h1>这里是内容 测试是否能传递</h1>`
    }
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
