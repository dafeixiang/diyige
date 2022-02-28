<template>
	<view class="content">
		<view class="span_one">
			<  返回
		</view>
		<view class="span_two">
			忘记密码
		</view>
		<input class="input_one" type="text" value="" placeholder="请输入账号" />
		<view class="box_one">
			<input class="input_two" type="text" value="" placeholder="请输入验证码" />
			<button class="button_one" type="default">获取验证码</button>
		</view>
		<input class="input_three" type="text" value="" placeholder="请输入新密码" />
		<button class="button_two" type="default">确认修改</button>
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
	.box_one {
			display: flex;
			margin-top: 50rpx;
		}
		.button_one {
			text-align: center;
			line-height: 90rpx;
			width: 200rpx;
			height: 90rpx;
			font-size: 27rpx;
			border-radius: 20rpx;
			background-color: #ff3e1e;
			color: #ffeeeb;
		}
		.button_two {
			line-height: 90rpx;
			width: 640rpx;
			height: 90rpx;
			font-size: 30rpx;
			margin-top: 100rpx;
			border-radius: 50rpx;
			background-color: #ff3e1e;
			color: #ffeeeb;
			text-align: center;
		}
		.input_two {
			width: 400rpx;
			height: 90rpx;
			margin-right: 40rpx;
			border-radius: 20rpx;
			background-color:#f6f4fc;
			text-indent: 30rpx;
		}
		.span_two {
			font-size: 50rpx;
			margin-top: 50rpx;
			margin-right: 450rpx;
		}
		.input_one {
			width: 640rpx;
			height: 90rpx;
			margin-top: 50rpx;
			border-radius: 20rpx;
			background-color: #f6f4fc;
			text-indent: 30rpx;
		}
		.input_three {
			width: 640rpx;
			height: 90rpx;
			margin-top: 50rpx;
			border-radius: 20rpx;
			background-color: #f6f4fc;
			text-indent: 30rpx;
		}
		.input_four {
			width: 640rpx;
			height: 90rpx;
			margin-top: 50rpx;
			border-radius: 20rpx;
			background-color: #f6f4fc;
			text-indent: 30rpx;
		}
	.span_one {
		 color: #ff6c55;
		 font-size: 36rpx;
		 display: flex;
		 margin-right: 550rpx;
		 margin-top: 50rpx;
	}
.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>
