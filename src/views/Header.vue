<template>
    <header id='lk_header'>
        <div class='top-bar d-none d-lg-block text-center text-muted'>
            <div class='container'>
                <div class='row'>
                    <div class='top-bar-1 col-md-2'>
                        <a href="javascript:void(0);" class='text-muted'>
                            <i class='icon-phone'></i>
                            <span>关注微信号</span>
                            <span class='caset'></span>
                            <img src="../assets/ewm_xzh.jpg" alt="微信二维码" width='130'>
                        </a>
                    </div>
                    <div class='top-bar-2 col-md-5'>
                        <i class='icon-tel'></i>
                        <span>8888-555-6666（服务时间：9:00-21:00）</span>
                    </div>
                    <div class='top-bar-3 col-md-2'>
                        <a href="javascript:void(0);" class='text-muted'>校企合作</a>
                        <a href="javascript:void(0);" class='text-muted'>培训师</a>
                    </div>
                    <div class='top-bar-4 col-md-3'>
                        <a class='btn btn-default btn-sm btn-register' href="javascript:void(0);" role='button'>免费注册</a>
                        <a class='text-muted' href="javascript:void(0);" role='button' style='margin-left: 10px' data-toggle='modal' data-target='#lk_login'>立即登录</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <nav class="col-md-12 navbar navbar-expand-md navbar-light navbar-lk">
                    <a class="navbar-brand" href="javascript:void(0);">
                        <img src="../assets/lk_logo_sm.png" alt="Logo" style="width:180px;">
                    </a>
                    <button class="navbar-toggler" type="button" data-toggle='collapse' data-target='#lk_nav'>
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id='lk_nav'>
                        <ul class="navbar-nav float-left">
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0);">关于我们</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0);">课程介绍</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0);">热门课程</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0);">名师授课</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0);">课堂互动</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0);">联系我们</a>
                            </li>
                        </ul>
                    </div>
                    <ul class="navbar-nav float-right d-none d-lg-block">
                        <li class="nav-item">
                            <a class="nav-link" href="javascript:void(0);">个人中心</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
        <div id='lk_login' class="modal fade">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <h4 class="modal-title text-info">登录</h4>
                        <button type="button" class="close" data-dismiss="modal">&times;</button>
                    </div>
                    <div class="modal-body">
                        <input type="text" placeholder="请输入手机号码">
                        <input type="password" placeholder="请输入密码">
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-dismiss="modal">关闭</button>
                        <button type="button" class="btn btn-primary">登录</button>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
    export default {
        name: 'Header'
    }
</script>

<style>
    .btn-register {
        color: #FFFFFF;
        background-color: #0AB4F7;
        border-color: #F4F7F7;
    }

    .btn-register:hover,
    .btn-register:focus,
    .btn-register:active,
    .btn-register.active,
    .open .dropdown-toggle.btn-register {
        color: #FFFFFF;
        background-color: #086DF2;
        border-color: #F4F7F7;
    }

    .btn-register:active,
    .btn-register.active,
    .open .dropdown-toggle.btn-register {
        background-image: none;
    }

    .btn-register.disabled,
    .btn-register[disabled],
    fieldset[disabled] .btn-register,
    .btn-register.disabled:hover,
    .btn-register[disabled]:hover,
    fieldset[disabled] .btn-register:hover,
    .btn-register.disabled:focus,
    .btn-register[disabled]:focus,
    fieldset[disabled] .btn-register:focus,
    .btn-register.disabled:active,
    .btn-register[disabled]:active,
    fieldset[disabled] .btn-register:active,
    .btn-register.disabled.active,
    .btn-register[disabled].active,
    fieldset[disabled] .btn-register.active {
        background-color: #0AB4F7;
        border-color: #F4F7F7;
    }

    .btn-register .badge {
        color: #0AB4F7;
        background-color: #FFFFFF;
    }

    @font-face {
        font-family: lk;
        src: url('/static/fonts/lk.eot') format('embedded-opentype'),
        url('/static/fonts/lk.svg') format('svg'),
        url('/static/fonts/lk.ttf') format('truetype'),
        url('/static/fonts/lk.woff') format('woff');
    }

    [class^="icon-"],
    [class*=" icon-"]{
        font-family: lk;
        font-style: normal;
    }

    #lk_header{
        font-size: 14px;
    }

    #lk_header .top-bar{
        height: 40px;
        line-height: 39px;
        border-bottom: 1px solid #e0e0e0;
    }

    #lk_header .top-bar .container .row>div+div{
        border-left: 1px solid #e0e0e0;
    }

    #lk_header .top-bar .container .row .top-bar-1 a{
        position: relative;
    }

    #lk_header .top-bar .container .row .top-bar-1 a img{
        position: absolute;
        display: none;
        left: 50%;
        margin-left: -65px;
        margin-top: -12px;
        z-index: 9999;
    }

    #lk_header .top-bar .container .row .top-bar-1 a:hover img{
        display: block;
    }

    #lk_header .icon-phone::before{
        content: '\e958';
        font-size: 13px;
    }

    #lk_header .icon-tel::before{
        content: '\e942';
        font-size: 13px;
    }

    #lk_header .navbar-lk{
        margin-bottom: 0;
        padding-bottom: 0;
    }

    #lk_header .navbar-lk .navbar-brand{
            height: 70px;
            padding: 10px 15px;
        }

    #lk_header .navbar-lk .navbar-nav a{
        height: 70px;
        line-height: 40px;
    }

    #lk_header .navbar-lk .navbar-nav li.active a,
    #lk_header .navbar-lk .navbar-nav li a:hover{
        background-color: transparent;
        border-bottom: 2px solid #0AB4F7;
    }
</style>