<script setup lang="ts">
import { ref } from 'vue'

const greeting = ref(" ")

// function onInput(e){
//   greeting.value = e.target.value
// }
</script>

<template>
<div class="bg-img">
  <h1>Greetings Application </h1>
    <div class="container">
      <input v-model="greeting" placeholder="Your name">
      <form action="/dataCollectionLocation" method="post" autocomplete="on">
      <button type="button">Cancel</button>
      <button type="submit">Submit</button>

  <!-- <input type="button" value="Cancel" />
  <input type="Submit" value="Submit" />
 -->

</form>
<p> Hello {{ greeting }}</p>
</div>
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
  /* text-shadow: 0.7cm; */
  /* font-family: 'Bungee Shade', cursive; */
  font-family: 'Monoton', cursive;
  font-family: 'Diplomata', cursive;
  /* font-family: 'Ubuntu', sans-serif; */
}
.container{
  position: absolute;
  margin: 20px;
  width: auto;
  align-content: center;
}
p{
  color:rgb(2, 1, 12);
  font-size:50px;
  font-style:bold;
}
</style>
