<template>
  <div id="app">
    <eheader></eheader>
  </div>
</template>

<script>
import eheader from './components/eheader'
export default {
  components: {
    eheader
  },
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="sass">
@import "./assets/sass/main.sass"
</style>
