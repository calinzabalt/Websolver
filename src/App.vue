<template>
  <v-app>
    <Toolbar />
    <v-content>
      <router-view/>
    </v-content>
    <Footer />
  </v-app>
</template>

<script>
// @ is an alias to /src
import Toolbar from '@/components/Toolbar.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'App',
  metaInfo: {
    title: 'Home',
    titleTemplate: '%s | WebSolver'
  },
  components: {
    Toolbar,
    Footer,
    
  }
}
</script>

<style lang="stylus">
#app
  font-family "eurostile" sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  background-color #00796B

</style>

 
     
