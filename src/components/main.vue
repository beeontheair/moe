<template>
  <div class="blog-main">
      <div class="blog-header">
        
      </div>
  </div>
</template>

<script>
export default {
  name: "main",
  data() {
    return {
      msg: "Welcome to Your Vue.js App1"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang="less">
body{
  margin: 0;
  padding: 0px;
}
  h1,
h2 {
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
.blog-main{
  width: 100%;
  height: 100%;
  background: #fff;
  & .blog-header{
    height: 50px;
    width: 100%;
    background-color: #42b983;
  }
}
</style>
