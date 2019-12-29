# ParallaxEffects
Parallax effect in your web-app and website............so used this code and modify your web.....




javascript file


<script>
    
   window.addEventListener('scroll', ()=>{
     const parallax = document.querySelector('.parallax');
         let scrollPosition = window.pageYOffset;
             parallax.style.transform = 'translateY(' + scrollPosition * 0.5 + 'px'
   });
   
</script> 
