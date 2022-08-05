<script setup lang="ts">
import { ref } from 'vue'

const greeting = ref('Hello " "')

</script>

<template>
<div class="bg-img">
  <h1>Greetings Application </h1>
  <form action="/dataCollectionLocation" method="post" autocomplete="on">
  <button type="button">Cancel</button>
  <button type="submit">Submit</button>

  <!-- <input type="button" value="Cancel" />
  <input type="Submit" value="Submit" />
 -->

</form>
</div>
</template>

<style >
.bg-img{
  background-image: url(public/image1.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 500px;
  min-width:1250px;
  background-position:center;


  position:relative;
  
}
button{
 align-content:center;
}
h1{
  text-align: center;
  /* font-size:larger; */
  text-shadow: 0.7cm;
  /* font-family: 'Bungee Shade', cursive; */
  font-family: 'Diplomata', cursive;
  /* font-family: 'Ubuntu', sans-serif; */


}
</style>
