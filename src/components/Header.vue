<template>
  <div class="header">
    
      <router-link :to="{name:'root'}">
        <img src="../assets/cnodejs_light.svg" alt>
      </router-link>
    

    <ul>
      <li>
        <a href="#">首页</a>
      </li>
      <li>
        <a href="#">新手入门</a>
      </li>
      <li>
        <a href="#">API</a>
      </li>
      <li>
        <a href="#">关于</a>
      </li>
      <li>
        <a href="#">注册</a>
      </li>
      <li>
        <a href="#">登录</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
/* * {
  margin: 0;
  padding: 0;
}
ul {
  list-style: none;
  display: flex;
  margin-right: 60px;
}
.header {
  background-color: #444444;
  height: 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
img {
  max-width: 120px;
  margin-left: 72px;
  padding-bottom: 6px;
}
li {
  margin-right: 28px;
}
a {
  text-decoration: none;
  color: #cccccc;
  font-size: 13px;
} */

.header{
  background-color:#5a5555 ;
  height: 50px;
}
img{
  max-width: 120px;
  margin-left: 50px;
  margin-top: 10px;
}
  ul{
    list-style: none;
    float: right;
    margin: 4px;
    margin-right: 60px;
  }
  li{
    display: inline-block;
    padding: 10px 15px;
  }
  a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
  }
</style>
