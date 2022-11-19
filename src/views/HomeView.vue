<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld title="嘿嘿" msg="1" type="black"/>
    <HelloWorld title="bbb" msg="2" type="blue"/>
    <HelloWorld title="aaa" msg="3"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
.black{
  background-color: #222;
}
.blue{
  background-color: rgb(25, 21, 255);
}
</style>