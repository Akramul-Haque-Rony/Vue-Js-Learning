<template>
    <div>
      <h1>Home Component</h1>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HomeComponent',
    props: {
      msg: String
    }
  }
  </script>

  <style scoped> 
    h1
    {
        color:orange;
    }
</style>