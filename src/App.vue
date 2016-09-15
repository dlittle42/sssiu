<template>
  <div id="app" class="container">
    <div class="item">
      <img src="./assets/logo.png">
    
      <h1>{{ msg }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello SSSIU!'
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
.container
{
     display: flex;
     align-items: center;
     justify-content: center;
     height: 100vh;
}
.item
{
     background-color: #f3f2ef;
     border-radius: 3px;
     width: 200px;
     height: 200px; 
}
</style>
