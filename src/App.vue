<template>

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
 body {
    background-image:url("https://www.google.com/search?q=image&sxsrf=ALeKk00LCGlnxt4ejcIIBCYMpz9aRl1-Dw:1629127911335&tbm=isch&source=iu&ictx=1&fir=gxFxsvFBmxeZ9M%252C0JWe7yDOKrVFAM%252C_&vet=1&usg=AI4_-kReDzFRmzDAOj_DsRSOvMu2NwesqQ&sa=X&ved=2ahUKEwiE8sqz7rXyAhVfhf0HHfBjDEMQ9QF6BAgMEAE&biw=1920&bih=969#imgrc=gxFxsvFBmxeZ9M")!important;
  
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}

</style>
