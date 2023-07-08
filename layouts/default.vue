<template>
  <div class="container">
    <AppHeader />
    <Nuxt />
  </div>
</template>

<script>
import AppHeader from '../components/AppHeader'
export default {
  components : {
     AppHeader
    
  }
}
</script>

<style>
 *{
   box-sizing: border-box;
   margin: 0;
   padding: 0;
 }

 body {
   font-size: 1rem;
   font-family: Arial, Helvetica, sans-serif;
   line-height: 1.6;
   /*background: #f4f4f4;*/
 }

 a {
   color: #666;
   text-decoration: none;
 }

 ul {
   list-style: none;
 }

.container {
  /*max-width: 800px;*/
  margin: 1rem auto;
  overflow: hidden;
  padding: 0 2rem;
  background: #fff;
}

 

</style>