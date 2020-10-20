<template>
  <div id="vue">
  <h1>Hello Vue.js! {{ message }}</h1>
 
  </div>
</template>

<script type="text/javascript">
  export default { 
    name: "HelloVue",
    data (){ 
      return {
        message: "啦啦啦啦啦"
      }
    }
  }
</script>

<style type="text/css">
  #vue{
    color: green;
    font-size: 28px;
  }
</style>