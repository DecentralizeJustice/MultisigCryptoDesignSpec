<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" style="width:25vw;height:auto;">
    <HelloWorld/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
