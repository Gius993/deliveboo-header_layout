<template>
	<!--eslint-disable-line no-mixed-spaces-and-tabs-->
	<div class="container_my">
		<div class="responsive_layout_my">

		</div>
		<div class="responsive_layout_my">

		</div>
		<div class="responsive_layout_my">

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
	.container_my{
		width: 100%;
		display: flex;
		align-items: center;
		flex-direction: column;
	}
	.responsive_layout_my{
		height: 400px;
		width: 400px;
		background-color: brown;
		border: 1px solid black;
		margin-top: 10px;
	}

 </style>