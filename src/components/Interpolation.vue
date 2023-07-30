<template>
    <div>
      <h1>Interpolation And Data</h1>
      <h1>Email : {{ email }}</h1>
      <h1>Contact : {{ mobile }}</h1>
      <h1>Contact : {{ mobile== '01617181934' }}</h1>
      <!-- <h1>Assigning Value inside of Interpolation: {{ mobile = '01617181934' }}</h1> -->
      <h1>Name : {{ getName() }}</h1>
    </div>
  </template>
  
  <script>
  export default {
    name: 'InterpolationAndData',
    data(){
        return {
            email:'swe.rony@gmail.com',
            mobile: '01725260320',
            getName:function(){
                return "Akramul Haque Rony"
            }
        }
    }
  }
  </script>

  <style scoped> 
    h1
    {
        color:orange;
    }
</style>