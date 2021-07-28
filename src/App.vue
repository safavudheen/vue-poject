<template>
  <div id="app">
 
    <vuePro />
    <posters/>
    <rowPost/>
  </div>
</template>

<script>
import vuePro from './components/vuePro.vue'
import posters from './components/posters.vue'
import rowPost from './components/rowPost.vue'

export default {
  name: 'App',
  components: {
    vuePro,
    posters,
    rowPost
  }
}
</script>

<style>
*{
  margin: 0;
}
#app {
  margin: 0;
}
</style>
