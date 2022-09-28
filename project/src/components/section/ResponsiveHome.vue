<template>
	<!--eslint-disable-line no-mixed-spaces-and-tabs-->
	<div class="container_my">
		<div class="store_my">
			<a href="#">I Migliori</a>
		</div>
		<div class="responsive_layout_my">
			<a href="#">
				<img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" alt="">
			</a>
		</div>
		<div class="responsive_layout_my">
			<a href="#">
				<img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" alt="">
			</a>
		</div>
		<div class="responsive_layout_my">
			<a href="#">
				<img src="https://www.buttalapasta.it/wp-content/uploads/2017/11/pizza-margherita.jpg" alt="">
			</a>
		</div>
	</div>
</template>
/* eslint-disable */   	  
<script>
 export default {
		name: 'ResponsiveHome',
	}
</script>
/* eslint-disable */   	  
	
<style scoped lang="scss">
	@import "../../assets/sass/variable.scss";
	.container_my{
		width: 100%;
		display: flex;
		align-items: center;
		flex-direction: column;
	}
	.responsive_layout_my{	
		width: 90%;
		margin-top: 20px;
		img{
			border: 1px solid ;
			border-radius: 20px;
		}
	}
	.store_my{
		font-size: 30px;
		color:$secondarycolor ;
	}
 </style>