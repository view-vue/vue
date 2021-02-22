<template>
  <div id="app">
      <BasicHeader></BasicHeader>
      <!-- <router-link to="/">Home</router-link> -->
    <router-view/>
      <BasicFooter></BasicFooter>
  </div>
</template>

<style lang="scss">

  // @import './assets/css/style.css';
  // css 로드 여기부터

// test
#app {
  height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  a {
    font-weight: bold;
    color: #2c3e50;
    transition: .2s;

    &.router-link-exact-active {
      color: #42b983;
      
    }
  }
}


@import url(./assets/css/style.css);
</style>

<script>
// @ is an alias to /src
import basicheader from '@/basic/BasicHeader'
import basicFooter from '@/basic/BasicFooter'

export default {
  name: 'nav',
  components: {
    'BasicHeader' : basicheader,
    'BasicFooter' : basicFooter
  },
}
</script>