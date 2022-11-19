<template>
  <div class="news">
    <h1>This is an about page</h1>
        <HelloWorld title="嘿嘿" msg="1"/>
        <Images/>
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'NewsView',
  components: {
    HelloWorld,
    img
  }
}
</script>
