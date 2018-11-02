<template>
	<section id='lk_product' class="jumbotron jumbotron-fluid">
	    <div class="container">
	        <div class="row">
	            <!-- 选项卡头部 -->
	            <div style="overflow: auto;">
	                <ul class="nav nav-tabs lk_nav" role='tablist'>
	                    <li class="nav-item" role='presentation'><a class="nav-link active" href="#product1" data-toggle='tab'>在线大学</a></li>
	                    <li class="nav-item" role='presentation'><a class="nav-link" href="#product2" data-toggle='tab'>会员专享</a></li>
	                    <li class="nav-item" role='presentation'><a class="nav-link" href="#product3" data-toggle='tab'>优质视频</a></li>
	                    <li class="nav-item" role='presentation'><a class="nav-link" href="#product3" data-toggle='tab'>优质视频</a></li>
	                    <li class="nav-item" role='presentation'><a class="nav-link" href="#product3" data-toggle='tab'>优质视频</a></li>
	                    <li class="nav-item" role='presentation'><a class="nav-link" href="#product3" data-toggle='tab'>优质视频</a></li>
	                    <li class="nav-item" role='presentation'><a class="nav-link" href="#product3" data-toggle='tab'>优质视频</a></li>
	                    <li class="nav-item" role='presentation'><a class="nav-link" href="#product3" data-toggle='tab'>优质视频</a></li>
	                    <li class='nav-item d-none d-lg-block'><a class="nav-link" href="#" data-toggle='tab'>更多</a></li>
	                </ul>
	            </div>
	            <!-- 选项卡详情 -->
	            <div class="tab-content">
	                <div class="container tab-pane active" id='product1'>
	                    <div class="container">
	                        <div class="row">
	                            <div class="col-lg-8 pd-left">
	                            	<!-- 第一部分 -->
	                                <div id='pd_one_1' class='media'>
	                                	<img src="../assets/ewm_xzh.jpg" alt="二维码" class="mr-3 mt-3" style="width:140px;">
	                                    <div class="media-body text-muted" style='padding-top: 115px'>
	                                        <h5 class='small'>更多资讯欢迎</h5>
	                                        <h5 class='small'>关注撩课学院</h5>
	                                    </div>
	                                </div>
	                                <!-- 第二部分 -->
	                                <ol id='pd_one-2' class='breadcrumb lead bg-light'>
	                                	<li class="breadcrumb-item">
	                                		<a href="javascript:void(0);">HTML5+全栈</a>
	                                	</li>
	                                	<li class="breadcrumb-item">
	                                		<a href="javascript:void(0);">Python+人工智能</a>
	                                	</li>
	                                	<li class="breadcrumb-item">
	                                		<a href="javascript:void(0);">JavaEE</a>
	                                	</li>
	                                	<li class="breadcrumb-item">
	                                		<a href="javascript:void(0);">Go语言+区块链</a>
	                                	</li>
	                                </ol>
	                                <!-- 第三部分 -->
	                                <div id='pd_one_3'>
	                                    <h1><small>
	                                    欢迎来到IT人的在线大学&nbsp;&nbsp;&nbsp;
	                                    <strong class="text-danger">撩课学院</strong>
	                                    </small></h1>
	                                </div>
	                                <!-- 第四部分 -->
	                                <div id='pd_one_4'>
	                                    <button class='btn btn-primary btn-lg' type="submit" style="margin-right: 20px;">课程咨询</button>
	                                    <button class='btn btn-default btn-lg' type="submit">了解更多</button>
	                                </div>
	                            </div>
	                            <div class='col-lg-4 d-none d-lg-block'>
	                                <img src="../assets/iphoneX.png" alt="" class='img-fluid'>
	                            </div>
	                        </div>
	                    </div>
	                </div>
	                <div class="container tab-pane fade" id='product2'>
	                    <div class="container">
	                        <div class="row">
	                            <div class="col-lg-4 d-none d-lg-block">
	                                <img src="../assets/iphoneX2.png" alt="" class="img-fluid">
	                            </div>
	                            <div id='pd_two_1' class="col-lg-8 pd-left">
	                                <h1 class="text-warning">撩课学院会员</h1>
	                                <p class="lead">
	                                    汇聚名师, 为你呈现前端、后端、移动端、大数据、人工智能等从零基础到项目实战连载课程内容。专属的会员社群和私人订制服务,1年365天持续更新课程全部免费学习！
	                                </p>
	                            </div>
	                        </div>
	                    </div>
	                </div>
	                <div class="container tab-pane fade" id='product3'>
	                    <div class="container">
	                        <div class="row">
	                            <div class="col-lg-6 pd-left">
	                                <h1>
	                                    <strong class="text-danger">案例驱动·体系贯穿·全面系统</strong>
	                                </h1>
	                                <h3>
	                                    10-15分钟的视频
	                                    <span class="text-warning">知识点拆分讲解</span>
	                                </h3>
	                                <h4 class="text-muted" style="margin: 15px 0;">
	                                    玩转HTML5+全栈系列, 玩转Python+人工智能系列, 玩转JavaEE系列, 玩转Go+区块链系列
	                                </h4>
	                                <div class="badge badge-pill badge-secondary" style="padding: 15px 10px; cursor: pointer;">
	                                    已更新3000+视频 | 100000+人订阅
	                                </div>
	                            </div>
	                            <div class="col-md-6 d-none d-lg-block">
	                                <img src="../assets/macBook.png" alt="" class="img-fluid">
	                            </div>
	                        </div>
	                    </div>
	                </div>
	            </div>
	        </div>
	    </div>
	</section>
</template>

<script>
	import jquery from 'jquery'
    export default {
        name: 'Product',
        created(){
        	jquery(window).on('resize',function(){
				let $ul = jquery('#lk_product .nav');
				let $allLis = jquery('[role="presentation"]', $ul);
				// console.log($allLis);

				//3.1 遍历
				let totalW = 0;
				$allLis.each(function(index, item){
					totalW += jquery(item).width();
				});
				console.log(totalW);

				let parentW = $ul.parent().width();

				//3.2 判断并设置宽度
				if(totalW > parentW){
					$ul.css({
						width: totalW + "px"
					})
				}else{
					$ul.removeAttr('style');
				}
			});

			jquery(window).trigger('resize');
        }
    }
</script>

<style>
	#lk_product{
		padding: 30px 0;
	}

	#lk_product .nav{
		font-size: 18px;
	}

	#lk_product .nav li:nth-last-child(1){
		position: absolute;
		right: 110px;
	}

	#lk_product .nav a{
		color: #999;
	}

	#lk_product .lk_nav li .active{
		border: none;
		background-color: transparent;
		border-bottom: 2px solid #0AB4F7;
		color: #000;
	}

	#lk_product .tab-content{
	    padding-top: 20px;
	}

	#lk_product .pd-left{
	    padding: 40px 0;
	}

	#pd_one_1{
	    margin: 15px 0;
	}

	#pd_one_2{
	    background-color: transparent;
	}

	#pd_one_4{
	    margin: 15px 0;
	}

	#lk_product #pd_two_1{
	    padding: 100px 0;
	}

	#lk_product #pd_two_1 h1{
	    margin-bottom: 15px;
	}
</style>