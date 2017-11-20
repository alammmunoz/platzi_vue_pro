<template lang="pug">
  #app
    h1 {{ msg }}
    p {{ 1+1 }}
    p {{ 'Hola' + 'Mundo' }}
    p {{ person.name }}
    p {{ person.name.toUpperCase() }}
    p {{ true? 'true' : 'falsedad' }}
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App!',

      person: {
        name: 'Alan'
      }
    }
  }
}
</script>

<style lang="scss">
  @import './scss/main.scss'
</style>
