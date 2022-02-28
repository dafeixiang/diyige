<template>
	<view class="content">
		<view class="box_one">
			<image class="image_a" src="../../static/img/fanhui.png" mode=""></image>
			<view class="box_one_span_a">
				房屋租售
			</view>
			<view class="box_one_span_b">
				成都
			</view>
			<image class="image_b" src="../../static/img/xiala.png" mode=""></image>
		</view>
		<image class="image_c" src="../../static/img/bendizixun@3x.png" mode=""></image>
		<view class="box_two">
			<image src="../../static/img/xingfang@3x.png" mode=""></image>
			<image src="../../static/img/ershoufang@3x.png" mode=""></image>
			<image src="../../static/img/zufang@3x.png" mode=""></image>
			<image src="../../static/img/zaijian@3x.png" mode=""></image>
			<image src="../../static/img/jijireng@3x.png" mode=""></image>
		</view>
		<view class="box_three">
			<view class="box_three_span_a">
				新房
			</view>
			<view class="box_three_span_b">
				二手房
			</view>
			<view class="box_three_span_c">
				租房
			</view>
			<view class="box_three_span_d">
				在建楼盘
			</view>
			<view class="box_three_span_e">
				经纪人
			</view>
		</view>
		<view class="span_one">
			为你推荐
		</view>
		<view class="box_four">
			<image class="image_five" src="../../static/img/hehuo@3x.png" mode=""></image>
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
	.image_five {
		width: 40vw;
		height: 15vh;
		margin-right: 350rpx;
		margin-top: 20rpx;
	}
	.span_one{
		font-size: 35rpx;
		font-weight: 700;
		margin-top: 30rpx;
		color: #333333;
		margin-right: 500rpx;
	}
	.box_three {
		display: flex;
		margin-right: 0rpx;
	}
	.box_three view {
		margin-left: 60rpx;
		font-size: 28rpx;
	}
	.box_two image {
		width: 13vw;
		height: 7vh;
		margin-left: 47rpx;
		margin-top: 30rpx;
		right: 20rpx;
	}
	.image_c {
		width: 94vw;
		height: 20vh;
		border-radius: 20rpx;
		margin-top: 40rpx;
	}
	.box_one_span_b {
		font-size: 28rpx;
		color: #333333;
	}
	.box_one {
		display: flex;
		margin-top: 30rpx;
	}
	.image_a {
		width: 7vw;
		height: 3vh;
		margin-right: 210rpx;
	}
	.image_b {
		width: 4vw;
		height: 2vh;
		margin-top: 8rpx;
	}
	.box_one_span_a {
		color: #333333;
		font-weight: 600;
		margin-right: 200rpx;
		
	}
.content {
 	display: flex;
 	flex-direction: column;
 	align-items: center;
 	justify-content: center;
 }
</style>
