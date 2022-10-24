<template>
  <h2 class="h2">Simple Vue website</h2>
  <input type="text" placeholder="enter name here" v-model="name"/>
  <br/><br/>
  <input type="text" placeholder="enter Surname" v-model="text1"/>
  <br/><br/>
  <button class="button1" type="submit" >Submit</button>
  <br/><br/>
    <button type="reset">CLICK TO RESET</button>
    <p>{{name}}</p>
    <p>{{text1}}</p>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
          name:null,
          text1:null


    }
    
  },
  }

</script>

<style>

#app {
  background-color: blanchedalmond;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.h2{
  font-style: italic;
}

</style>
