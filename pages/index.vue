<template>
<div>
  <div class="m-60 h-48 flex justify-center items-center ">
    <img class="fixed h-96 w-72" src="~/assets/foto.png">
    <p1 class=" flex justify-center  z-10">Hello I'm Alif</p1>
  </div>
  <div>
  <div class="m-96  flex " >
    <p id="div2" class="text-center z-10" >
      My Interest Is In Computer Technology, Such As Programming, Therefore I Like To Apply My Knowledge And Explore New Possibilities,I Also Enjoy Working With Teams
    </p>
  </div>
  <div class="m-96  flex " >
    <p id="div3" class="text-center  z-10" >
    My Life Is Like A Book That They’ve Judging By A Cover But Have Never Took The Time To Fucking Read The Shit 
    </p>
    </div>
</div>
</div>  
</template>

<script>
export default {

  layout: 'default',

  mounted() {
    document.querySelectorAll('a[nuxt-link^="#"]').forEach(elem => {
    elem.addEventListener('click', e => {
        e.preventDefault();
        document.querySelector(elem.getAttribute('href')).scrollIntoView({
            behavior: 'smooth',
            offsetTop: 20
        });
    });
});
  }
}


</script>
