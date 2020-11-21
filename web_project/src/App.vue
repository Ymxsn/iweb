<template>
	<!-- 顶部条 -->
	<TopBar></TopBar>
	<!-- 导航条组件 -->
	<!-- <NavBar></NavBar> -->
	<!-- 顶部条搜索条组件 -->
	<!-- <SearchBar></SearchBar> -->
	<!-- 底部条 -->
	<BottomBar></BottomBar>
	<!-- <CarouselBar></CarouselBar> -->
</template>

<script>
	import TopBar from './components/TopBar.vue'
	// import NavBar from './components/NavBar.vue'
	import BottomBar from './components/BottomBar.vue'
	// import CarouselBar from './components/.vue'
	

	export default {
	  components:{TopBar,BottomBar,}
	  
}
</script>

<style>
	/* 此处放置所有组件的公共样式 */
	.container{		/*公共样式*/
		width: 1200px;
		margin-left: auto;
		margin-right: auto;
		border: none; /* 测试用 */
		}
	.theme{	/* 主题色 (公共样式)*/
	}
	.theme-reverse{	/* 主题色的反色  (公共样式) */
		color: #e8b916;
	}
</style>
