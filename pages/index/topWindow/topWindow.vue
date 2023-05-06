<template>
	<view>
		<view class="left-header">
			<navigator class="logo" open-type="reLaunch" url="/pages/component/view/view">
				<!-- <image src="" mode="heightFix" style="width: 30px;"></image> -->
				<h1>华夏中医</h1>
			</navigator>
		</view>
		<view>
			<!-- <custom-tab-bar direction="horizontal" :show-icon="false"
			 /> -->
			<uni-link class="phone-link" href="https://m3w.cn/uniapp" text="体验手机版"></uni-link>
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {

		}
	}
</script>

<style>
.left-header {
		padding: 0 15px;
		display: flex;
		height: 60px;
		flex-direction: row;
		justify-content: space-between;
		align-items: center;
		box-sizing: border-box;
	}

	.logo {
		display: flex;
		flex-direction: row;
		align-items: center;
		flex: 1;
	}
</style>
