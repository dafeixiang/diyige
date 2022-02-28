<template>
	<view class="content">
		<view class="span_one">
			<view class="span_one_a">
				<
			</view>
			<view class="span_one_b">
				邀请好友
			</view>
		</view>
		<view class="view_box">
			<image class="image_one" src="../../static/img/bg.png" mode=""></image>
			<view class="box_one">
				Applogo
			</view>
			<view class="span_two">
				12345678
			</view>
			<view class="span_three">
				·我的邀请码·
			</view>
			<button class="button_one" type="default">复制邀请码</button>
		    <view class="span_four">
		    	扫描二维码
		    </view>
			<view class="span_five">
				下载APP和好友一起领金币吧~
			</view>
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
	.span_four {
		position: absolute;
		margin-top: 820rpx;
		position: absolute;
		margin-left: 250rpx;
		font-size: 30rpx;
	}
	.span_five {
		position: absolute;
		font-size: 12rpx;
		margin-top: 870rpx;
		margin-left: 250rpx;
		color: #646464;
	}
	.button_one {
		position: absolute;
		width: 250rpx;
		height: 80rpx;
		background-color: #ff3e1e;
		margin-top: 600rpx;
		margin-left: 190rpx;
		line-height: 80rpx;
		color: #fffbfa;
	}
	.span_three {
		position: absolute;
		margin-top: 500rpx;
		margin-left:230rpx;
		color: #a2a2a2;
	}
	.span_two {
		position: absolute;
		margin-top: 430rpx;
		margin-left: 190rpx;
		font-size: 52rpx;
	}
	.box_one {
		position: absolute;
		margin-top: 200rpx;
		margin-left: 240rpx;
		width: 130rpx;
		height: 130rpx;
		background-color: #ff3e1e;
		border-radius: 20rpx;
		color: #fffbfb;
		text-align: center;
		line-height: 130rpx;
		font-size: 25rpx;
	}
	.view_box {
		display: flex;
	position: relative;
	}
	.image_one {
		width: 600rpx;
		height: 900rpx;
		margin-top: 100rpx;
	}
	.span_one {
		display: flex;
		font-size: 37rpx;
		margin-top: 30rpx;
		color: #fff5f4;
	}
	.span_one_a {
		display: flex;
		margin-right: 250rpx;
	}
	.span_one_b {
		display: flex;
		margin-right: 260rpx;
	}
.content {
 	display: flex;
 	flex-direction: column;
 	align-items: center;
 	justify-content: center;
 }
  page {
	  background-color: #ff3e1e;
  }
</style>
