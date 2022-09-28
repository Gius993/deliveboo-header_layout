
<template>
<!--eslint-disable-line no-mixed-spaces-and-tabs-->
  <div>
     <HeaderHome />
  <div class="carrousel_my">
       <CarrouselHome />
      <CarrouselHome />
      <CarrouselHome />
      <CarrouselHome />
      <CarrouselHome />
    </div>
    <div class="responsive_my">
        <ResponsiveHome />
    </div>
	</div>
</template>
  
  <script>

  import HeaderHome from './section/HeaderHome.vue';
  import CarrouselHome from './section/CarrouselHome.vue';
  import ResponsiveHome from './section/ResponsiveHome.vue';



  export default {
	name: 'HomeUtent',
  components: {
    HeaderHome,
    CarrouselHome,
    ResponsiveHome,
}
  }
</script>
  

<style scoped lang="scss">


  .carrousel_my{
      margin-top: 150px;
      display: flex;
      justify-content: center;
     overflow: hidden;
    }
    .responsive_my{
      display: none;
    }
    @media screen and (max-width: 620px) {
    .carrousel_my{
      display: none;
    }
    .responsive_my{
      display: block;
    }
}
  </style>
  