<template>
  <div class="hello">
    <div class="img">
      
    </div>
    <div>
      <p>{{ title }}</p>
      <h1>{{ msg }}</h1>
      <button>搶票唷</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    title: String,
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello {
  width: 100%;
  display: inline-flex;
  margin: 1rem;
}
.ing{
  width: 8rem;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
