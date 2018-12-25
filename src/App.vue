<template>
  <div id="app">
    <div class="container">
      <Search></Search>
      <UsersMain></UsersMain>
    </div>
  </div>
</template>

<script>
import Search from './components/Search.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Search,
    UsersMain: Main
  }
}
</script>

<style>
</style>
