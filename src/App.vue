<template>
  <main class="app">
    <Comments />
  </main>
</template>

<script>
import Comments from './components/Comments'

export default {
  name: 'app',
  components: {
    Comments
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500&display=swap');

.app {
  display: block;
  margin: 2rem auto;
  max-width: 700px;
  font-family: 'Roboto', sans-serif;
}
</style>
