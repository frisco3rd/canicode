<template>
  <v-app>
    <v-content>
      <Navigation/>
      <Homepage/>
    </v-content>
  </v-app>
</template>

<script>
import Navigation from './components/Navigation'
import Homepage from './components/Homepage'

export default {
  name: 'App',
  components: {
    Navigation,
    Homepage
  },
  data () {
    return {
    
    }
  }
}
</script>