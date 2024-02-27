<template>
  <div>
   
      <job-board></job-board>
    <login-screen></login-screen>
    <double-registration></double-registration>
    <on-boarding></on-boarding>
 
  </div>

 </template>
<script>

import JobBoard from './components/JobBoard.vue';
import LoginScreen from './components/LoginScreen.vue';
import DoubleRegistration from './components/DoubleRegistration.vue';
import onBoarding from './components/onBoarding.vue';



export default {
  name: 'App',
  components: {
 
    JobBoard,
    LoginScreen,DoubleRegistration,
    onBoarding 
 
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background:#EDEFF7;
  padding-top:50px;
 
}

*{
  margin: 0;
}
@media only screen and (max-width: 600px){

     #app{
      width: 100%; /* Adjust width for smaller screens if needed */
    max-width: none; /* Remove max-width on smaller screens if needed */
     }
}
</style>
