<template>
  <nav class="main-nav">
    <router-link :to="{ name: 'HomePage' }">Home Page</router-link>
    <router-link :to="{ name: 'ProjectsList' }">Tasks</router-link>
    <router-link :to="{ name: 'AddProject' }">Add New Task</router-link>
  </nav>
</template>

<script>
export default {};
</script>

<style>
.main-nav {
  text-align: center;
  margin: 40px auto;
}

.main-nav a {
  display: inline-block;
  text-decoration: none;
  color: #999;
  font-size: 18px;
  margin: 0 10px;
}

a.router-link-active {
  border-bottom: 2px solid #00ce89;
  padding-bottom: 4px;
}
</style>
