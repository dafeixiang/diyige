<template>
	<view class="content">
		<view class="status_bar" style="height:var(--status-bar-height);width: 100%;">
			
		</view>
		<view class="text-area">
			<text class="title">{{title}}</text>
		</view>
		<view class="demo_one">
			欢迎使用双讯同城
		</view>
		<view class="demo_two">
			用户登录
		</view>
		<input  class="input_one" type="text" value="" placeholder="请输入账号"/>
		<input  class="input_two" type="text" value="" placeholder="请输入密码"/>
		<button type="default" class="button_one">
			<view-span class="span_one">登录</view-span>
		</button>
		<view class="span_two">忘记密码?</view>
		<view class="span_three">
			其他方式登录
		</view>
		<view class="imageAll">
			<image class="image_one" src="../../static/img/zhifubao.png" mode=""></image>
			<image class="image_two" src="../../static/img/weixing.png" mode=""></image>
		</view>
		<view class="box_one">
			<view class="span_four">没有账号,</view>
			<view class="span_five">注册新用户?</view>
		</view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
			
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.imageAll {
		display: flex;
		margin-top: 20rpx;
	}
	.image_one {
		width: 60rpx;
		height: 60rpx;
		margin-right: 50rpx;
	}
	.image_two {
		width: 60rpx;
		height: 60rpx;
	}
	.box_one {
		font-size: 16rpx;
		display: flex;
		margin-top: 70rpx;
		margin-left: 25rpx;
	}
	.span_five {
		color: #ff5539;
	}
	.span_three {
		display: flex;
		margin-top: 100rpx;
		font-size: 20rpx;
		color: #a8a6a9;
	}
	.span_two {
		display: flex;
		color: #ca5841;
		margin-top: 50rpx;
	}
	.span_one {
		display: flex;
		color: #fffbff;
		font-size: 16rpx;
		justify-content: center;
		align-items: center;
		text-align: center;
		margin-left: 200rpx;
	}
	.button_one {
		display: flex;
		align-items: center;
		text-align: center;
		margin-top: 40rpx;
		width: 500rpx;
		height: 70rpx;
		border-radius: 30rpx;
		background-color: #ff3d20;
	}
	.input_one {
		width: 500rpx;
		height: 70rpx;
		margin-top: 30rpx;
		border-radius: 20rpx;
		background-color: #f6f5fc;
		text-indent: 30rpx;
	}
	.input_two {
		width: 500rpx;
		height: 70rpx;
		margin-top: 30rpx;
		border-radius: 20rpx;
		background-color: #f6f5fc;
		text-indent: 30rpx;
	}
	.demo_two{
		display: flex;
		font-size: 35rpx;
		margin-top: 180rpx;
		margin-right: 350rpx;
	}
	.demo_one {
		display: flex;
		font-size: 50rpx;
		margin-top: 150rpx;
	}
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	
</style>
