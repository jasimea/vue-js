<template>
  <div id="app">
   
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Navbar />
    <Sidebar/>
    
    <!-- When click on the button of Input component the event should be triggered in this component and log the data -->
    <Input />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import Sidebar from './components/Sidebar.vue'
import Input from './components/Input.vue'





export default {
  name: 'App',
  components: {
    HelloWorld,Navbar,Sidebar,Input
  }
}
</script>

<style>

</style>
