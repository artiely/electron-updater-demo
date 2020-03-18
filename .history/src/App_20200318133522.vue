<template>
  <div id="app">
   这是一个版本更新测试：Artiely
   <p>当前版本：{{version}}</p>
  </div>
</template>

<script>
const {version} = require('../package.json')
console.log("version", version)
export default {
  name: 'App',
  data(){
    return {
      version
    }
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
  margin-top: 60px;
}
</style>
