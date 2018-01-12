<template>
  <div id="app">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
import Logo from './Logo.vue'

export default {
  name: 'app',

  components: { Logo },

  data () {
    return {
      msg: 'Hello CodeMash! 🇺🇸'
    }
  },

  methods: {
    alert () {
      alert('Logo Click! 👏')
    }
  }
}
</script>

<style>
body {
  background: #0c84a9;
  color: #fff;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
