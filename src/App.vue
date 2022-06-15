<template>
  <div>
    <div class="nav">
      <router-link to="/Find">find</router-link>
      <a href="#/my">my</a>
      <a href="#/part">part</a>
    </div>
    <div class="router">
    <router-view></router-view>
      
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
  .router{
    height: 400px;
    border: 1px solid red;
  }
  .nav a{
    margin-left: 10px;
  }
</style>