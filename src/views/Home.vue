<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <p>APP</p>
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/> -->
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
// import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

@Component({
  components: {
    // HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style lang="stylus" scoped>
p
  color red
  font-size 60px
</style>
