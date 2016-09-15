<template>
  <div id="app" class="container">
    <div class="item">
      <img src="./assets/sssiu_welcome.jpg">
    
     <!-- <h1>{{ msg }}</h1> -->
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
  margin: 0;
  padding: 0;
}
.container
{
     display: flex;
     align-items: center;
     justify-content: center;
    
}
.item
{
    
     width: 100%;

}
img{
  width: 100%;

}
</style>
