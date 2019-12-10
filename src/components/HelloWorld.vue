<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <router-link id="Home" to="/Home">首页</router-link>
      <router-link id="FirstPage" to="/FirstPage">第一页</router-link>
      <router-link id="SecondPage" to="/SecondPage">第二页</router-link>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li><a href="http://localhost:8080/#/Home" target="_blank">Home</a></li>
      <li><a href="http://localhost:8080/#/FirstPage" target="_blank">FirstPage</a></li>
      <li><a href="http://localhost:8080/#/SecondPage" target="_blank">SecondPage</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '欢迎查看我的Vue学习示例'
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
