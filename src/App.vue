<template>
  <div>
    <!-- 顶部导航栏 -->
    <header id="header" class="mui-bar mui-bar-nav">
			<h1 class="mui-title zxy-header">导航栏</h1>
		</header>



<nav class="mui-bar mui-bar-tab zxy-nav">
			<a class="mui-tab-item mui-active" href="#tabbar">
				<span class="mui-icon mui-icon-home"></span>
				<span class="mui-tab-label">首页</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-chat">
				<span class="mui-icon mui-icon-email"><span class="mui-badge">9</span></span>
				<span class="mui-tab-label">消息</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-contact">
				<span class="mui-icon mui-icon-contact"></span>
				<span class="mui-tab-label">通讯录</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-map">
				<span class="mui-icon mui-icon-gear"></span>
				<span class="mui-tab-label">设置</span>
			</a>
		</nav>

  </div>
</template>

<script>
export default {
  
};
</script>


<style lang="scss" scoped>
  .zxy-header {
    background-color: #0ff;
    right: 0;
    left: 0;
  }
  .zxy-nav {
    background-color: #0ff;
  }
</style>
