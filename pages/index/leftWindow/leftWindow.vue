<template>
	<view class="left">
		<view class="menu" >
			<ul>
				<li v-for="item in types" :key="item.url">{{item.name}}</li>
			</ul>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				types: [
					{
						name:"妇科",
						url:'cancer'
					},
					{
						name:"儿科",
						url:'cancer'
					},
					{
						name:"感冒",
						url:'cancer'
					},
					{
						name:"发烧",
						url:'cancer'
					},
					{
						name:"高低血压",
						url:'cancer'
					},
					{
						name:"糖尿病",
						url:'cancer'
					},
					{
						name:"肿瘤",
						url:'cancer'
					},
					{
						name:"风湿",
						url:'cancer'
					},
				]
			}
		},
		methods: {
			
		}
	}
</script>

<style>
.left{
	background-color: aqua;
}
.menu{
	width: 80px;
}
</style>
