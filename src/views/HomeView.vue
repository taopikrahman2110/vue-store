<template>
  <div class="home">
    <HeaderShayna />
    <CarouselShayna />
    <WomanShayna />
    <InstagramShayna/>
    <PartnerShayna />
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
// import CarouselShayna from "@/components/CarouselShayna.vue";
import CarouselShayna from "@/components/CarouselShayna.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";
import WomanShayna from '@/components/WomanShayna.vue';
import InstagramShayna from '@/components/InstagramShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';



export default {
  name: "HomeView",
  components: {
    // HelloWorld
    HeaderShayna,    
    CarouselShayna,
    WomanShayna,
    InstagramShayna,
    PartnerShayna,
    FooterShayna,
},
};
</script>
