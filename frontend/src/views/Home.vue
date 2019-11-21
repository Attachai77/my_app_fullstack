<template>
  <div class="home">
    <img alt="MDB logo" src="../assets/logo-mdb-vue-small.png">
    <HelloWorld msg="Welcome to Your MDB Vue.js App"/>
    <router-link to="/login">Login</router-link>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
