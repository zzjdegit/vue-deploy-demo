<template>
  <div class="hello">
    <h1>Hello Nginx</h1>
    <h1>{{ msg }}</h1>
    <h2>测试一下自动化部署，提交下更新代码啦，O(∩_∩)O哈哈~</h2>
    <div>配置项目https</div>
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
