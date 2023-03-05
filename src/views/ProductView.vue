<template>
    <div class="product">
      <HeaderShayna />
       
      <FooterShayna/>
    </div>
  </template>
  
  <script>

  // @ is an alias to /src
  // import HelloWorld from '@/components/HelloWorld.vue'
  // import CarouselShayna from "@/components/CarouselShayna.vue";
 
  import HeaderShayna from "@/components/HeaderShayna.vue";
  import FooterShayna from '@/components/FooterShayna.vue';
  
  
  
  export default {
    name: "ProductView.vue",
    components: {
      // HelloWorld
      HeaderShayna,
      FooterShayna,
  },
  };
  </script>
  