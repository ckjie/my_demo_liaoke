<template>
	<footer id='lk_footer'>
	    <div class="container">
	        <div class="row" style="padding-top: 20px;">
	            <div class="col-sm-4 col-sm-offset-1 one">
	                <div class="row">
	                    <ul class="col-sm-6">
	                        <li><a href="javascript:void(0);">关于我们</a></li>
	                        <li><a href="javascript:void(0);">课程介绍</a></li>
	                        <li><a href="javascript:void(0);">热门课程</a></li>
	                    </ul>
	                    <ul class="col-sm-6">
	                        <li><a href="javascript:void(0);">名师授课</a></li>
	                        <li><a href="javascript:void(0);">课堂互动</a></li>
	                        <li><a href="javascript:void(0);">联系我们</a></li>
	                    </ul>
	                </div>
	            </div>
	            <div class="col-sm-4 two">
	                <h5>公司地址: 上海市松江区松江大学城</h5>
	                <h5>联系电话：*************</h5>
	                <h5>地址邮箱：*************</h5>
	            </div>
	            <div class="col-sm-4 three">
	                <h5>联系我们:</h5>
	                <a href="javascript:void(0);">
	                    <img src="../assets/weixin-h.png" alt="" width="50px;" data-toggle='tooltip' data-placement='bottom' title='添加微信'>
	                    <img src="../assets/xinlang-h.png" alt="" width="50px;" data-toggle='tooltip' data-placement='bottom' title='关注微博'>
	                </a>
	            </div>
	        </div>
	    </div>
	</footer>
</template>

<script>
	import jquery from 'jquery'
    export default {
        name: 'Footer',
        mounted(){
        	jquery("[data-toggle='tooltip']").tooltip();
        }
    }
</script>

<style>
	#lk_footer{
		width: 100%;
		height: 200px;
		background: url('../assets/ft_bg.png') no-repeat center;
		-webkit-background-size: cover;
		background-size: cover;
		color: #fff;
		font-size: 16px;
	}

	#lk_footer ul{
		list-style: none;
	}

	#lk_footer .one, #lk_footer .two{
		padding: 10px;
		height: 180px;
		border-right: 1px solid #666;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	#lk_footer .one li{
		line-height: 40px;
	}

	#lk_footer .one li a{
		color: #fff;
	}

	#lk_footer .three{
		padding: 10px 50px;
		height: 180px;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: flex-start;
	}

	#lk_footer .three a{
		margin-right: 15px;
		text-decoration: none;
	}

	#lk_footer .row .two h5, #lk_footer .row .three h5, #lk_footer .row .three a{
		font-size: 14px;
	}
</style>
