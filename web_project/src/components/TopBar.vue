<template>
	<!-- 1楼：顶部条 -->
	<div class="topbar">
		<div class="container">
			<a href="#">
				<span class="fa fa-mobile-phone fa-lg"></span>
				下载手机客户端
			</a>
			<span>|</span>
			<a href="#">
				<span class="fa fa-envelope"></span>
				反馈意见
			</a>
			<span>|</span>
			<span>
				<span class="fa fa-phone"></span>
				客服热线：4008-200-200
			</span>
			
			<!-- 右侧的登录/注册菜单 -->
			<div class="login-register-box">
				<a href="#">登录</a>
				<span>|</span>
				<a href="#">注册</a>
			</div>
		</div>
	</div>
</template>

<script>
	export default{
		
	}
</script>

<style>
	.topbar{
		width: 100%;
		height: 60px;
		line-height: 40px;
		background:rgba(0,0,0,0.4);
		border-bottom: none;	
		text-align: center;
		padding: 20px;
		font-size: 1.1em;
	}
	
	.topbar>.container>a{
		padding-left: 2em;
		
	}
	.topbar>.container>span{	/* 复杂选择器:>选择孩子,逗号选取多个*/
		padding-left: 2em;
		color: #fff;
	}		
	.topbar  .login-register-box {
		float: right;
		background: #db1900;
		padding: 0  1em;
		width: 100px;
	}
	.topbar  .login-register-box  a {
		color: #fff;
	}
	.topbar  .login-register-box  a:hover {
		color: #e8b916;
	}
	.topbar  .login-register-box  span {
		margin: 0  0.5em;
		color: #fff;
	}
</style>
