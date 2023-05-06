<template>
	<view class="right">
		<view class="me">
			登陆 注册 主题
			<Login />
		</view>
		<view class="sponsor">
			赞助
		</view>
		<view class="siteinfo">
			在线会员 累计用户 新注册
		</view>
		<view class="ad"></view>
	</view>
</template>

<script setup>
	import Login from '../../login/login.vue'
</script>

<style>
.right{
	background-color: burlywood;
}
</style>
