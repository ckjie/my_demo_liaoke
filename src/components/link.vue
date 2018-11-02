<template>
	<section id='lk_link'>
	    <div class='title text-center'>
	        <h1><strong>友情链接</strong></h1>
	        <img src="../assets/star.png" alt="" class="img-fluid">
	    </div>
	    <ul class="logos">
	        <li><a href="javascript:void(0);"><img src="../assets/ibm-logo.png" width="100px" alt=""></a></li>
	        <li><a href="javascript:void(0);"><img src="../assets/facebook-logo.png" width="50px" alt=""></a></li>
	        <li><a href="javascript:void(0);"><img src="../assets/google-logo.png" width="50px" alt=""></a></li>
	        <li><a href="javascript:void(0);"><img src="../assets/airbnb-logo.png" width="100px" alt=""></a></li>
	        <li><a href="javascript:void(0);"><img src="../assets/swift-logo.png" width="50px" alt=""></a></li>
	        <li><a href="javascript:void(0);"><img src="../assets/paypal-logo.png" width="100px" alt=""></a></li>
	        <li><a href="javascript:void(0);"><img src="../assets/walmart-logo.png" width="100px" alt=""></a></li>
	    </ul>
	</section>
</template>

<script>
    export default {
        name: 'Link'
    }
</script>

<style>
	#lk_link .logos{
		list-style: none;
		text-align: center;
	}

	#lk_link .logos li{
		display: inline-block;
		padding: 20px 30px;
	}
</style>
