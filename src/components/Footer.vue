<template>
  <footer>
    <p>Created by Brendan Ryan</p>
    <a href="https://brendanryan.xyz">Portfolio</a><br>
    <router-link to="/about">About</router-link>
  </footer>
</template>

<script>
export default {
  name: 'FooterX'
}
</script>


<style scoped>
  a {
    color: 'green';
  }
  footer {
    margin-top: 30px;
    text-align: center;
  }
</style>