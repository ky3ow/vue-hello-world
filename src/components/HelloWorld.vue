<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Socials</h3>
    <ul>
      <li><a href="https://github.com/ky3ow" target="_blank" rel="noopener">GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/volodymyr-havryliuk-1ba70a249/" target="_blank" rel="noopener">LinkedIn</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
