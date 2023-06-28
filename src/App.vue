<template>
  <h1>Hi <b>{{ userData.name }}</b> and your email is <b>{{ userData.email }}</b></h1>
  <br/>
<div>

      <input type="text" name="" id="" v-model="userData.name" placeholder="Type your name here...">
      <input type="email" name="" id="" v-model="userData.email" placeholder="Type your email here..">

      <input type="text" name="" id="" v-model="userData.website" placeholder="Type your website here...">
      </div>

</template>


<script setup="">
import { reactive } from 'vue';


const userData=reactive({
  name:'',
  email:'',
  website:''
})


</script>