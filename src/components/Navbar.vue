<template>
  <div id="firstParagraph">
    <h3> This is my new component</h3>
    <p>that is the part of the{{ text }}</p>
    <button @click="helloWorld">hello world</button>
  </div>
</template>

<script>
export default {

  data(){
    return{
      text:' iteration 1 & 2',
    }
  },
   methods: {
   helloWorld(){
      console.log("hello world");
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p {
  color: #8342b9;
  font-size: 20px;
  text-align: center;
}
</style>
