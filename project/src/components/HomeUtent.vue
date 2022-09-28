
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
	</div>
</template>
  
  <script>

  import HeaderHome from './section/HeaderHome.vue';
  import CarrouselHome from './section/CarrouselHome.vue';

  export default {
	name: 'HomeUtent',
  components: {
    HeaderHome,
    CarrouselHome, 
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


  </style>
  