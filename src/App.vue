<template>
  <div id="app">
    <img alt="Vue logo" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/e5d19ae7-0615-4760-9162-3b5c0c5cbf81/d9pjdcs-1497f2f9-19f9-4edd-9051-338999455a35.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvZTVkMTlhZTctMDYxNS00NzYwLTkxNjItM2I1YzBjNWNiZjgxXC9kOXBqZGNzLTE0OTdmMmY5LTE5ZjktNGVkZC05MDUxLTMzODk5OTQ1NWEzNS5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ._rPHotfKJNcHrJHxh_jJ47cJy-g48JbZi7wPuJxAbmI">
    <Home msg="TitanicDIY"/>
  </div>
</template>

<script>
import Home from './components/home.vue'

export default {
  name: 'App',
  components: {
    Home
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
