<template>
    <img alt="Vue logo" src="./assets/logo.png">
    <user-chat></user-chat>
</template>

<script>
import UserChat from './components/UserChat.vue';

export default {
    name: 'App',
    components: {
        UserChat
    },
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
