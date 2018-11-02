<template>
	<section id='lk_hot'>
	    <div class='title text-center'>
	        <h1><strong>热门课程</strong></h1>
	        <img src="../assets/star.png" alt="" class="img-fluid">
	    </div>
	    <div class="container">
	        <div class="row">
	            <div class="col-lg-6 lesson">
	                <div class="media">
	                	<div class="media-left">
	                        <img src="../assets/lnj.png" alt="李南江" class="img-fluid rounded-circle img-thumbnail mr-3" width="100px;">
	                    </div>
	                    <div class="media-body">
	                        <h4><small>
	                            <span class="text-danger">【热】</span>
	                            从零玩转HTML5+跨平台
	                        </small></h4>
	                        <p class="text-muted" style="margin-top: 10px;">
	                            李南江老师带你从零基础入门大前端开发, So Easy, Too Happy!
	                        </p>
	                    </div>
	                    <div class="mt-4 ml-3 media-right text-danger">
	                        206节课
	                    </div>
	                </div>
	            </div>
	            <div class="col-lg-6 lesson">
	                <div class="media">
	                	<div class="media-left">
	                        <img src="../assets/yjh.png" alt="叶建华" class="img-fluid rounded-circle img-thumbnail mr-3" width="100px;">
	                    </div>
	                    <div class="media-body">
	                        <h4><small>
	                            <span class="text-danger">【热】</span>
	                            从零玩转JavaScript+项目实战
	                        </small></h4>
	                        <p class="text-muted" style="margin-top: 10px;">
	                            叶建华老师带你轻松解读JavaScript的前世今生, 全程案例驱动讲解!
	                        </p>
	                    </div>
	                    <div class="mt-4 ml-3 media-right text-danger">
	                        256节课
	                    </div>
	                </div>
	            </div>
	            <div class="col-lg-6 lesson">
	                <div class="media">
	                	<div class="media-left">
	                        <img src="../assets/wzs.png" alt="王顺子" class="img-fluid rounded-circle img-thumbnail mr-3" width="100px;">
	                    </div>
	                    <div class="media-body">
	                        <h4><small>
	                            <span class="text-danger">【热】</span>
	                            从零玩转人工智能+Python系列
	                        </small></h4>
	                        <p class="text-muted" style="margin-top: 10px;">
	                            王顺子老师倾情打造, 各种奇淫技巧层出不穷, 赶紧到碗里来!
	                        </p>
	                    </div>
	                    <div class="mt-4 ml-3 media-right text-danger">
	                        600+节课
	                    </div>
	                </div>
	            </div>
	            <div class="col-lg-6 lesson">
	                <div class="media">
	                	<div class="media-left">
	                        <img src="../assets/yjh.png" alt="叶建华" class="img-fluid rounded-circle img-thumbnail mr-3" width="100px;">
	                    </div>
	                    <div class="media-body">
	                        <h4><small>
	                            <span class="text-danger">【热】</span>
	                            从零玩转Vue+Node全系列
	                        </small></h4>
	                        <p class="text-muted" style="margin-top: 10px;">
	                            打通前后端, 真实企业项目实操, 内容涉及前端、后端、微信端, 让你一次学个够!
	                        </p>
	                    </div>
	                    <div class="mt-4 ml-3 media-right text-danger">
	                        400+节课
	                    </div>
	                </div>
	            </div>
	            <div class="col-lg-6 lesson">
	                <div class="media">
	                	<div class="media-left">
	                        <img src="../assets/gxq.jpg" alt="高新强" class="img-fluid rounded-circle img-thumbnail mr-3" width="100px;">
	                    </div>
	                    <div class="media-body">
	                        <h4><small>
	                            <span class="text-danger">【热】</span>
	                            从零玩转JavaEE全系列
	                        </small></h4>
	                        <p class="text-muted" style="margin-top: 10px;">
	                            高新强老师全程高能, 只为成就更好的你! 学Java, 就选"高薪墙"!
	                        </p>
	                    </div>
	                    <div class="mt-4 ml-3 media-right text-danger">
	                        700+节课
	                    </div>
	                </div>
	            </div>
	            <div class="col-lg-6 lesson">
	                <div class="media">
	                	<div class="media-left">
	                        <img src="../assets/lnj.png" alt="李南江" class="img-fluid rounded-circle img-thumbnail mr-3" width="100px;">
	                    </div>
	                    <div class="media-body">
	                        <h4><small>
	                            <span class="text-danger">【热】</span>
	                            从零玩转jQuery+ajax系列
	                        </small></h4>
	                        <p class="text-muted" style="margin-top: 10px;">
	                            这里有用JQ做的小游戏, 也有JQ做的QQ音乐, 还有...., 你要学的, 江哥这里都有!
	                        </p>
	                    </div>
	                    <div class="mt-4 ml-3 media-right text-danger">
	                        200+节课
	                    </div>
	                </div>
	            </div>
	        </div>
	    </div>
	</section>
</template>

<script>
    export default {
        name: 'Hot'
    }
</script>

<style>
	#lk_hot .lesson{
		padding: 15px 10px;
	}

	#lk_hot .lesson .media-body{
		vertical-align: middle;
	}

	#lk_hot .lesson .media-body p{
		font-size: 15px;
	}

	#lk_hot .lesson .media-right{
		font-size: 16px;
	}
</style>
