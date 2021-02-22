<template>
  <div class="content home">
    <!-- <img alt="Vue logo" src="../../assets/logo.png"> -->
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/main/mainCon/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
