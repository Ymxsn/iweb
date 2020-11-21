<template>
		<div class="navbar">
			<div class="container">
				<!-- 左侧的功能列表 -->
				<ul class="menu">
					<li class="active"><a href="index.html">首页</a></li>
					<li><a href="course.html">全部课程</a></li>
					<li><a href="course.html?tid=1">基础课程</a></li>
					<li><a href="course.html?tid=2">核心课程</a></li>
					<li><a href="course.html?tid=3">进阶课程</a></li>
					<li><a href="teacher.html">名师堂</a></li>
					<li><a href="school.html">校区</a></li>
				</ul>
				
				<!-- 右侧的登录/注册菜单 -->
				<div class="login-register-box">
					<a href="#">登录</a>
					<span>|</span>
					<a href="#">注册</a>
				</div>
				<img class="item" src="../assets/img/VCG21gic19923994.jpg" alt="广告">
			</div>
		</div>
</template>

<script>
</script>

<style>
	.navbar {
		background:rgba(0,0,0,0.4);
		width: 100%;
		height: 120px;
		/* border-bottom: 2px solid #c1eebd; */
		line-height: 39px;
		color: #fff;
		font-size: 1.2em;
	}
	.navbar  .menu {
		
	}
	.navbar  .menu  li {
		float: left;	/*让原本的块级元素li全部浮动起来*/
		padding: 0  1.5em;
	}
	.navbar  .menu  li.active {
		background: #3da232;
	}
	.navbar  .menu  li:hover {
		background: #4AAF3F;
	}
	.navbar  .menu  li  a {		/*使用复杂选择器具有更高的优先级*/
		color: #fff;
	}
	.item {
		position: absolute;
		top: 0;
		left: 50%;	/*先往右移到父容器的中线处，此处的50%指参照物(父容器)的宽度*/
		height: 380px;
		/* CSS中的变形函数：旋转/缩放/扭曲/平移 */
		transform: translateX(-50%);  /*当前元素向左平移，此处的50%指自己的宽度*/
		z-index: -2;	/*图片降低z轴出现顺序，以露出上面的内容*/
		width: 100%;
		height: 100%;
	}
	.navbar  .login-register-box {
		float: right;
		background: #77c558;
		padding: 0  2em;
	}
	.navbar  .login-register-box  a {
		color: #fff;
	}
	.navbar  .login-register-box  a:hover {
		color: #FBFC95;
	}
	.navbar  .login-register-box  span {
		margin: 0  0.5em;
	}
</style>
