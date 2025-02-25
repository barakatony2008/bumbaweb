<template>
 <studentregistration_component></studentregistration_component>
 <aboutus_component></aboutus_component>
 <button_component></button_component>
</template>

<script>
import studentregistration_component from './components/studentregistration_component.vue';
import aboutus_component from './components/aboutus_component.vue';
import button_component from './components/button_component.vue';
export default {
  name: 'App',
  components:{
    studentregistration_component,
    aboutus_component,
    button_component
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color:green;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
