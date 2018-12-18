<template>
  <div class="hello">
{{hell}}
<div v-if='show'>aaaaaaa</div>
<div v-else>bbbbb</div>
<div v-bind:class="ha">ccc</div>
{{0>10?"dui":"cuo"}}
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      hell:'aaa',
      show:false,
      ha:'ha1'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
