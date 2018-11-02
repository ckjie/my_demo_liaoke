<template>
	<section id='lk_carousel' class="carousel slide" data-ride="carousel">
		<ul class="carousel-indicators">
			<li data-target="#lk_carousel" data-slide-to="0" class="active"></li>
			<li data-target="#lk_carousel" data-slide-to="1"></li>
			<li data-target="#lk_carousel" data-slide-to="2"></li>
		</ul>
		<div class="carousel-inner">
			<div class="carousel-item item active">
				<img src='../assets/slide_01.png'>
			</div>
			<div class="carousel-item item">
				<img src='../assets/slide_02.png'>
			</div>
			<div class="carousel-item item">
				<img src='../assets/slide_03.png'>
			</div>
		</div>
		<a class="carousel-control-prev" href="#lk_carousel" data-slide="prev">
			<span class="carousel-control-prev-icon"></span>
		</a>
		<a class="carousel-control-next" href="#lk_carousel" data-slide="next">
			<span class="carousel-control-next-icon"></span>
		</a>
	</section>
</template>

<script>
	import jquery from 'jquery'
    export default {
        name: 'Carousel'
    }
</script>

<style>
	@media screen and (min-width: 800px){
		#lk_carousel .item{
			height: 410px;
		}
	}

	#lk_carousel .item img{
		width: 100%;
		height: 100%;
	}
</style>
