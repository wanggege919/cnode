<template>
  <div class="App">
    <Header />
    <div class="main clearfix">
      <router-view name = 'slidebar'></router-view>
      <router-view name = 'main'></router-view>

    </div>
    
  </div>
  
</template>

<script>
import Header from './components/Header'
import PostList from './components/PostList'
export default {
  name: 'App',
  components:{
    Header,PostList
  }
}
</script>

<style scoped>
  /* *{
    margin: 0;padding: 0
  } */
  
  .main{
    width:80%;
    margin: 0 auto;
  }
  .clearfix:after{
    content:'';
    display:block;
    clear:both
  }
</style>
