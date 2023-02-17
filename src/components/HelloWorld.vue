<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>{{ age }}</h1>
    <h1>{{ gender }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return {
      msg: 'Hello Abdallah Mahmoud',
      age: '20',
      gender: 'male',
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
