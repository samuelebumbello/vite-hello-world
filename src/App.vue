<script>

import Header from "./components/AppTitle.vue"
import Jumbotron from "./components/AppHero.vue"


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
  color: rgb(61, 216, 87);
}
</style>