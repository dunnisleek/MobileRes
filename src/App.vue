<template>
  <div>
   
    <!-- <account-ui></account-ui> -->
    <job-board></job-board>
    <login-screen></login-screen>
    <subscription-pricing></subscription-pricing>
    <double-registration></double-registration>
    <!-- <project-board></project-board>
     -->
    <on-boarding></on-boarding>
 
  </div>

 </template>
<script>
import onBoarding from './components/onBoarding.vue';

import DoubleRegistration from './components/DoubleRegistration.vue';

import subscriptionPricing from './components/subscriptionPricing.vue';

import LoginScreen from './components/LoginScreen.vue';
import JobBoard from './components/JobBoard.vue';



export default {
  name: 'App',
  components: {
  onBoarding,
    DoubleRegistration,

    subscriptionPricing,

    LoginScreen,JobBoard
 
    
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
