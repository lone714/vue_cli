<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Button type="primary">Primary</Button>

    <hr>
    <Carousel v-model="value" loop>
        <CarouselItem v-for="item in 5" :key="item">
          <img alt="" :src="require(`@/assets/images/avatar/report_avatar_1.png`)"/>
        </CarouselItem>
    </Carousel>
  </div>
</template>

<script>
    export default {
        data () {
            return {
                value: 0
            }
        }
    }
</script>