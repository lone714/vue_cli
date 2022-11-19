<template>
    <div class="ing">
        <img :src="link" alt="">
        <HelloWorld title="緊張喔"/>
    </div>
</template>
<script>
export default {
  props: {
    link: String
  }
}
</script>
<style lang="scss">
    .img{
        width: 100vw;
        height: 10rem;
        background-color: #999;
    }
</style>