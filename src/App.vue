<template>
  <div id="app">
    <Message/>
    <Users/>
  </div>
</template>

<script>
import Users from './components/Users.vue'
import Message from './components/Message.vue'

export default {
  name: 'app',
  components: {
    Users,
    Message
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
