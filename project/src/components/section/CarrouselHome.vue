
<template>
<div class="slider_my">
	<div class="slide-track_my">
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
		<div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
    <div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
    <div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
    <div class="slide_my">
      <a href="#">
        <img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" height="100" width="250" alt="" />
      </a>
		</div>
	</div>
</div>
</template>
/* eslint-disable */    
<script>

	export default {
		name: 'CarrouselHome',
		el: '#app',
}
</script>
/* eslint-disable */  	  
	
<style scoped lang="scss">
 /* eslint-disable */
 @import "../../assets/sass/variable.scss";

$animationSpeed: 80s;

// Animation
@keyframes scroll {
	0% { transform: translateX(0); }
	100% { transform: translateX(calc(-250px * 7))}
}


// Styling
.slider_my {	
	
	position: relative;
	
	
	&::before,
	&::after {
	
		content: "";
		height: 100px;
		position: absolute;
		width: 200px;
		z-index: 2;
	}
	
	&::after {
		right: 0;
		top: 0;
		transform: rotateZ(180deg);
	}

	&::before {
		left: 0;
		top: 0;
	}
	
	.slide-track_my {
		animation: scroll $animationSpeed linear infinite;
		display: flex;
		width: calc(350px * 7);
	}
	
	.slide_my {
	
    width: calc(100% / 7);
    margin-left: 10px;
    display: flex;
    align-items: center;
}
    display: flex;
    align-items: center;
    a{
      display: inline-block;
      width: 100%;
    }
   img{
    width: 100%;
    border-radius: 15px;
    border: 1px solid;
   }
	}
  .slide_my:hover{
    img{
    width: 100%;
    border-radius: 15px;
    border: 5px solid  $maincolor;
   }
  }

</style>
	