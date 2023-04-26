<script>

import Header from "./components/AppTitle.vue"


export default {
  name: 'App',
  components:{
    Header,

  },
  data(){
    return{
      title: "Hello Vite!"
    }
  }
}
</script>

<template>

  <Header/>
  <h1>{{ title }}</h1>
  <Jumbotron/>
</template>


<style scoped>
h1{
  color: crimson;
}
</style>