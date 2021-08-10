<template>
   <div class="fixed left-6 bottom-24  ">
     <ul>
       <a href="mailto:bayulif72@gmail.com"><li><font-awesome-icon :icon="faEnvelope" /></li></a>
     </ul>
     <ul>
       <a href="https://github.com/george666-cloud"><li><font-awesome-icon :icon="faGithub" /></li></a>
     </ul>
     <ul>
       <a href="https://www.linkedin.com/in/alif-bayu-14340a210/"><li><font-awesome-icon :icon="faLinkedin" /></li></a>
     </ul>
     <ul>
       <a href="https://www.instagram.com/yxx666x"><li><font-awesome-icon :icon="faInstagram" /></li></a>
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
