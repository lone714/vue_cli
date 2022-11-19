<template>
  <div class="news">
    <h1>This is an about page</h1>
    <Images link="https://fakeimg.pl/100/"/>
    <Images link="https://fakeimg.pl/150/"/>
    <HelloWorld title="緊張喔"/>
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Images from '@/components/Images.vue'


export default {
  name: 'NewsView',
  components: {
    HelloWorld,
    Images
  }
}
</script>
