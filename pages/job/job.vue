<template>
	<view class="content">
		<view class="box_one">
			<view class="span_one">
				<
			</view>
			<input class="input_one" type="text" value="" placeholder="       请输入关键词" />
			<image class="logo_one" src="../../static/img/fabu@3x.png" mode=""></image>
			<view class="span_two">
				已发布
			</view>
		</view>
		<view class="box_two">
			<view class="box_two_span_a">
				地区
			</view>
			<image class="box_two_image_a" src="../../static/img/shaixuan@3x.png" mode=""></image>
			<view class="box_two_span_b">
				职位
			</view>
			<image class="box_two_image_b" src="../../static/img/shaixuan@3x.png" mode=""></image>
			<view class="box_two_span_c">
				工资
			</view>
			<image class="box_two_image_c" src="../../static/img/shaixuan@3x.png" mode=""></image>
		</view>
		<!-- 横线 -->
		<view class="divider"/>
		<view class="box_three">
			<view class="box_three_a" style="background-color: #38a4ec;">
				招聘
			</view>
			<view class="box_three_b" style="background-color: #f0982e;">
				求职
			</view>
			<view class="box_three_c" style="background-color: #f53b3b;">
				兼职
			</view>
		</view>
		<!-- 横线 -->
		<view class="divider_b"/>
		<!-- 第一格 -->
		<view class="box_four">
			<view class="box_four_a">
				<view class="box_four_a_span_a">
					销售安装
				</view>
				<view class="box_four_a_span_b">
					5000-8000
				</view>
			</view>
			<view class="box_four_b">
				<view class="box_four_b_span_a">
					经验不限/招聘人数：3人
				</view>
				<view class="box_four_b_span_b">
					3-17
				</view>
			</view>
			<view class="box_four_c">
				<view class="box_four_c_one">
					年假
				</view>
				<view class="box_four_c_two">
					包吃
				</view>
				<view class="box_four_c_three">
					社保
				</view>
			</view>
			<view class="box_four_d ">
				<view class="box_four_d_span_a">
					公司
				</view>
				<view class="box_four_d_span_b">
					成都多元化科技有限公司
				</view>
				<button class="button_one" type="default">咨询</button>
			</view>
		</view>
		<view class="divider_c"/>
		<!-- 第二格 -->
		<view class="box_four">
			<view class="box_four_a">
				<view class="box_four_a_span_a">
					机场地勤
				</view>
				<view class="box_four_a_span_b">
					5000-8000
				</view>
			</view>
			<view class="box_four_b">
				<view class="box_four_b_span_a">
					经验不限/招聘人数：3人
				</view>
				<view class="box_four_b_span_b">
					3-17
				</view>
			</view>
			<view class="box_four_c">
				<view class="box_four_c_one">
					年假
				</view>
				<view class="box_four_c_two">
					包吃
				</view>
				<view class="box_four_c_three">
					社保
				</view>
			</view>
			<view class="box_four_d ">
				<view class="box_four_d_span_a">
					公司
				</view>
				<view class="box_four_d_span_b">
					成都天府国际机场
				</view>
				<button class="button_two" type="default">咨询</button>
			</view>
		</view>
		<view class="divider_c"/>
		<!-- 第三格 -->
		<view class="box_four">
			<view class="box_four_a">
				<view class="box_four_a_span_a">
					客服销售
				</view>
				<view class="box_four_a_span_b">
					5000-8000
				</view>
			</view>
			<view class="box_four_b">
				<view class="box_four_b_span_a">
					经验不限/招聘人数：3人
				</view>
				<view class="box_four_b_span_b">
					3-17
				</view>
			</view>
			<view class="box_four_c">
				<view class="box_four_c_one">
					年假
				</view>
				<view class="box_four_c_two">
					包吃
				</view>
				<view class="box_four_c_three">
					社保
				</view>
			</view>
			<view class="box_four_d ">
				<view class="box_four_d_span_a">
					公司
				</view>
				<view class="box_four_d_span_b">
					成都多元化科技有限公司
				</view>
				<button class="button_one" type="default">咨询</button>
			</view>
		</view>
		<view class="box_buttom">
			<button class="button_three" type="default">
				招聘发布
			</button>
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
	.button_three {
		background-color: #FF3E1E;
		color: #fffefe;
		width: 94%;
		border-radius: 20rpx;
		margin-top: 300rpx;
	}
	.box_buttom {
		background: #f7f7f7;
		width: 100%;
		height: 400rpx;
		margin-top: 20rpx;
	}
	.button_two {
		width: 19vw;
		border-radius: 10rpx;
		height: 4.5vh;
		line-height: 63rpx;
		font-size: 30rpx;
		background-color: #ff3e1e;
		color: #ffffff;
		margin-left: 180rpx;
	}
	.button_one {
		width: 19vw;
		border-radius: 10rpx;
		height: 4.5vh;
		line-height: 63rpx;
		font-size: 30rpx;
		background-color: #ff3e1e;
		color: #ffffff;
		margin-left: 90rpx;
	}
	.box_four_d_span_a {
		border: 1px solid #108DF2;
		color: #108DF2;
		font-size:29rpx;
		width: 13vw;
		height: 3.5vh;
		line-height: 50rpx;
		margin-left: 20rpx;
		text-align: center;
	}
	.box_four_d_span_b {
		color: #B3B3B3;
		font-size: 28rpx;
		margin-top: 7rpx;
		margin-left: 30rpx;
	}
	.box_four_d {
		display: flex;
		margin-top: 40rpx;
	}
	
	.box_four_c {
		display: flex;
		margin-top: 20rpx;
		font-size: 28rpx;
	}
	.box_four_c view {
		width: 13vw;
		height: 4vh;
		background-color: #e2f2ff;
		color: #108df2;
		margin-left: 23rpx;
		text-align: center;
		line-height: 50rpx;
	}
	.box_four_b {
		display: flex;
		font-size: 28rpx;
		color: #666666;
		margin-top: 15rpx;
	}
	.box_four_b_span_a {
		margin-left: 20rpx;
	}
	.box_four_b_span_b {
		margin-left: 297rpx;
	}
	.box_four_a_span_a {
		font-weight: 600;
		margin-left: 20rpx;
	}
	.box_four_a_span_b {
		font-weight: 600;
		color: #fe2b2b;
		margin-left: 370rpx;
	}
	.box_four_a {
		display: flex;
		margin-top: 20rpx;
	}
	/* box_four上 */
	.box_three view {
		background-color: #007AFF;
		width: 29vw;
		height: 7vh;
		margin-left: 14rpx;
		border-radius: 20rpx;
		margin-right: 8rpx;
		margin-top: 30rpx;
		text-align: center;
		line-height: 90rpx;
		color: #ffffff;
	}
	.box_three {
		display: flex;
	}
	.divider_c{
		 background: #f7f7f7;
		 width: 100%;
		 height: 25rpx;
		 margin-top: 30rpx;
		}
	.divider_b{
		 background: #E0E3DA;
		 width: 98%;
		 height: 1rpx;
		 margin-left: 10rpx;
		 margin-top: 30rpx;
		}
	.divider{
		 background: #E0E3DA;
		 width: 98%;
		 height: 1rpx;
		 margin-left: 10rpx;
		 margin-top: 10rpx;
		}
	.box_two_span_b {
		margin-left: 190rpx;
	}
	.box_two_span_c {
		margin-left: 190rpx;
	}
	.box_two {
		display: flex;
		margin-left: 17rpx;
		margin-top: 20rpx;
		color: #999999;
	}
	.box_two image {
		width: 3.5vw;
		height: 1.2vh;
		margin-top: 20rpx;
		margin-left: 8rpx;
	}
	.span_two {
		font-size: 25rpx;
		position: absolute;
		margin-left: 597rpx;
		margin-top: 80rpx;
	}
	.logo_one {
		width: 5vw;
		height: 3vh;
		margin-top: 40rpx;
		margin-left: 60rpx;
	}
	.span_one {
		font-size: 60rpx;
		margin-top: 30rpx;
		margin-right: 30rpx;
	}
	.box_one {
		display: flex;
	}
	.input_one {
		width: 480rpx;
		height: 80rpx;
		background-color: #f4f4f4;
		border-radius: 35rpx;
		text-indent: 30rpx;
		margin-top: 35rpx;
		background-image: url(../../static/img/sousuo@2x.png);
		background-repeat: no-repeat;
		background-position: 40rpx;
	}
.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>
