<template>
   <div class="fixed left-6 bottom-24  ">
     <ul>
       <a href="https://github.com/george666-cloud"><li><font-awesome-icon :icon="faEnvelope" /></li></a>
     </ul>
     <ul>
       <li><font-awesome-icon :icon="faGithub" /></li> 
     </ul>
     <ul>
       <li><font-awesome-icon :icon="faLinkedin" /></li>
     </ul>
     <ul>
       <li><font-awesome-icon :icon="faInstagram" /></li>
      </ul> 
  </div>
</template>

<script>

import {
   
   faGithub,
   faLinkedin,
   faInstagram,

   } from '@fortawesome/free-brands-svg-icons'

import { 
 
     faEnvelope,

        } from '@fortawesome/free-solid-svg-icons'

export default {
  data () {
     return {

       faEnvelope,
       faGithub,
       faLinkedin,
       faInstagram,

    }
  },
}
</script>
