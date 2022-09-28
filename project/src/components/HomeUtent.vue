
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
    <div class="responsive_my_tb">
      <ResponsiveTablet />
    </div>
    <div class="responsive_my_sp">
        <ResponsiveHome />
    </div>
	</div>
</template>
  
  <script>

  import HeaderHome from './section/HeaderHome.vue';
  import CarrouselHome from './section/CarrouselHome.vue';
  import ResponsiveHome from './section/ResponsiveHome.vue';
  import ResponsiveTablet from './section/ResponsiveTablet.vue';  

  export default {
	name: 'HomeUtent',
  components: {
    HeaderHome,
    CarrouselHome,
    ResponsiveHome,
    ResponsiveTablet,
    
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
    .responsive_my_sp{
      display: none;
    }
    .responsive_my_tb{
      display: none;
    }
    @media screen and (max-width: 920px) {
      .carrousel_my{
         display: none;
    }
    .responsive_my_tb{
      display:block;
    }
}
    @media screen and (max-width: 620px) {
      .responsive_my_tb{
        display:none;
      }
    .carrousel_my{
      display: none;
    }
    .responsive_my_sp{
      display: block;
    }
}
  </style>
  