<template>
  <div class="background">
  </div>
  <Header></Header>
  <Google_content></Google_content>

</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Google_content from './components/Content.vue'


export default {
  name: 'App',
  components: {
    Header,
    Google_content,
 
  }
}
</script>

<style >

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}

</style>
