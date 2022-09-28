<template>
	<!--eslint-disable-line no-mixed-spaces-and-tabs-->
	<div>
		<div class="store_my">
			<a href="#">I Migliori</a>
		</div>
		<div class="container_my">
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

	</div>
</template>
/* eslint-disable */   	  
<script>
 export default {
		name: 'ResponsiveTablet',
	}
</script>
/* eslint-disable */   	  
	
<style scoped lang="scss">
	@import "../../assets/sass/variable.scss";
	.container_my{
		display: flex;	
		flex-wrap: wrap;
	}
	.responsive_layout_my{	
		width: calc(100% / 3 - 10px);
		margin-top: 20px;
		margin-left: 10px;
		img{
			border: 1px solid ;
			border-radius: 20px;
		}
	}
	.store_my{
		font-size: 30px;
		color:$secondarycolor ;
		text-align: center;
	}

 </style>