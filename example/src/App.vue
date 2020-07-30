<template>
  <div id="app">
      <!-- <router-view></router-view> -->
    <hello-world></hello-world>
  </div>
</template>

<script>
import HelloWorld from '@/components/Home'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
@import "./common/style/base.scss";

#app {
  position: relative;
  width: 100%;
  height: 100%;
}
</style>
