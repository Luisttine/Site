<template>
  <div id="app">
    <input type="text" name="nome" value="" placeholder="e-mail" />
    <Login msg="Digite seu e-mail!"/>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>


<script>
import HelloWorld from './components/HelloWorld.vue'
import Login from './components/Login.vue'


export default {
  name: 'App',
  components: {
    HelloWorld, 
    Login
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
