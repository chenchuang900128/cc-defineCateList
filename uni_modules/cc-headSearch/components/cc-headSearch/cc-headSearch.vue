<template>
	<view class="headerSearch">
		<navigator class="searchBox" :url="skipUrl">
			<image src="./search_icon.png" mode=""></image>
			<!-- <navigator to="#"> -->
			搜索全部
			<!-- </navigator> -->
		</navigator>
	</view>
</template>

<script>
	
	export default {
	
		props: {
			// 左边标题栏
			skipUrl: {
				type: String,
				default: ""
			}
	
		},
		data() {
			return {
	
			}
		},
		methods: {
	
	
		}
	
	}
	
</script>

<style scoped>
	.headerSearch {
		height: 110rpx;
		background: #fff;
		width: 100%;
		overflow: hidden;
	}

	.searchBox {
		width: 92%;
		height: 70rpx;
		background: #F4F4F4;
		font-size: 28rpx;
		color: #999;
		border-radius: 10rpx;
		margin: 20rpx auto;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.searchBox navigator {}

	.searchBox image {
		width: 18px;
		height: 18px;
		margin-right: 10rpx;
	}
</style>