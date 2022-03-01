<template>
	<view class="content">
		<view class="box_one">
			<image class="image_one" src="../../static/img/fanhui.png" mode=""></image>
			<view class="span_one">
				自产自销
			</view>
			<view class="span_two">
				我的发布
			</view>
		</view>
		<image class="image_two" src="../../static/img/fenxiang@3x.png" mode=""></image>
		<!-- 横线 -->
		<view class="divider"/>
		<view class="box_b">
		<view class="box_two">
			<image class="image_three" src="../../static/bingguang@3x.png" mode=""></image>
			<view class="span_three">
				小儿紫
				<view class="span_four" style="font-weight: 100;color: #B3B3B3;">
					2018-08-12
				</view>
			</view>
		</view>
		<view class="span_five">
			自己养的土鸡出售 有需要可联系15564412227
		</view>
		<view class="box_three">
			<image src="../../static/img/pingtai@3x.png" mode=""></image>
			<image src="../../static/img/jinbi@3x.png" mode=""></image>
			<image src="../../static/img/renzheng@3x.png" mode=""></image>
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
	.box_three {
		display: flex;
	}
	.box_three image {
		width: 30vw;
		height: 16vh;
		margin-left: 10rpx;
		margin-top: 30rpx;
	}
	.span_five {
		font-size: 31rpx;
		margin-top: 20rpx;
		color: #333333;
	}
	.span_three {
		font-size: 32rpx;
		font-weight: 700;
		color: #333333;
	}
	.box_two {
		display: flex;
		margin-right: 420rpx;
		margin-top: 20rpx;
	}
	.divider{
		 background: #f7f7f7;
		 width: 100%;
		 height: 25rpx;
		 margin-top: 30rpx;
		}
	.image_three {
		width: 11vw;
		height: 6vh;
		margin-right: 10rpx;
	}
	.image_two {
		width: 94vw;
		height: 20vh;
		margin-top: 30rpx;
	}
	.box_one {
		display: flex;
		margin-top: 30rpx;
	}
	.span_one {
		font-size: 35rpx;
		font-weight: 700;
		color: #333333;
		margin-left: 195rpx;
	}
	.span_two {
		font-size: 31rpx;
		margin-left: 195rpx;
		color: #333333;
	}
	.image_one {
		width: 7vw;
		height: 3vh;
	}
.content {
  	display: flex;
  	flex-direction: column;
  	align-items: center;
  	justify-content: center;
  }
</style>
