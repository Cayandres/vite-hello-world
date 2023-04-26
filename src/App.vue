
<script>
import AppTitle from "./components/AppTitle.vue"
export default {
  name: "App",
  components:{
    AppTitle
  },
  data(){
    return{
      title: "ciao"
    }
  }
  
}
</script>

<template>
  <h1>{{ title }}</h1>
  <AppTitle/>
</template>

<style>

</style>