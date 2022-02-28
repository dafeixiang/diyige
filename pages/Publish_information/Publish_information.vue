<template>
	<view class="content">
		<view class="box">
		<view class="box_one">
			<image class="image_a" src="../../static/img/fanhui.png" mode=""></image>
			<view class="box_one_span_a">
				发布信息
			</view>
		</view>
		</view>
		<view class="box_two">
			<view class="box_two_a">
				<view class="box_two_a_span_a">
					类型
				</view>
				<view class="box_two_a_span_b">
					*
				</view>
				<input class="input_one" type="text" value="" placeholder="请选择类型" />
			</view>
			<view class="box_two_b">
				<view class="box_two_b_span_a">
					职位名称
				</view>
				<view class="box_two_b_span_b">
					*
				</view>
				<input class="input_two" type="text" value="" placeholder="请输入职位名称" />
			</view>
			<view class="box_two_c">
				<view class="box_two_c_span_a">
					薪资待遇
				</view>
				<view class="box_two_c_span_b">
					*
				</view>
				<input class="input_three" type="text" value="" placeholder="请输入薪资待遇" />
			</view>
			<view class="box_two_d">
				<view class="box_two_d_span_a">
					招聘人数
				</view>
				<view class="box_two_d_span_b">
					*
				</view>
				<input class="input_four" type="text" value="" placeholder="请输入招聘人数" />
			</view>
			<view class="box_two_e">
				<view class="box_two_e_span_a">
					公司名称
				</view>
				<view class="box_two_e_span_b">
					*
				</view>
				<input class="input_five" type="text" value="" placeholder="请输入公司名称" />
			</view>
			<view class="box_two_f">
				<view class="box_two_f_span_a">
					工作经验
				</view>
				<view class="box_two_f_span_b">
					*
				</view>
				<input class="input_six" type="text" value="" placeholder="请输入工作经验" />
			</view>
		</view>
		<view class="box_three">
			<view class="box_three_span_a">
				职位福利（没有可不选）
			</view>
			<view class="box_three_span_b">
				<button class="button_four" type="default">房补</button>
				<button class="button_four" type="default">包住</button>
				<button class="button_four" type="default">包吃</button>
				<button class="button_four" type="default">社保</button>
				<button class="button_four" type="default">年假</button>
			</view>
			<view class="box_three_span_c">
				<button class="button_five" type="default">年休</button>
				<button class="button_six" type="default">加薪</button>
			</view>
		</view>
		<view class="box_four">
			<view class="box_four_b">
				<view class="box_four_b_span_a">
					联系电话
				</view>
				<view class="box_four_b_span_b">
					*
				</view>
				<input class="box_four_input_two" type="text" value="" placeholder="请输入联系电话" />
			</view>
		</view>
		<view class="box_buttom">
			<button class="button_ten" type="default">
				确认发布
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
	.box_buttom {
		background: #f7f7f7;
		width: 100%;
		height: 400rpx;
		margin-top: 80rpx;
	}
	.button_ten {
		background-color: #FF3E1E;
		color: #fffefe;
		width: 94%;
		border-radius: 20rpx;
		margin-top: 270rpx;
	}
	.box_four_input_two {
		text-indent: 60rpx;
	}
	.box_four_b {
		display: flex;
		margin-top: 30rpx;
		margin-left: 30rpx;
	}
	.box_four_b_span_b {
		color: #f41717;
	}
	.box_four {
		width: 94%;
		height: 7vh;
		margin-top: 50rpx;
		background-color: #FFFFFF;
		border-radius: 20rpx;
	}
	.button_six {
		right: 213rpx;
	}
	.box_three_span_c button {
		width: 14vw;
		height: 4.3vh;
		font-size: 10rpx;
		margin-top: 25rpx;
		margin-left: 20rpx;
	}
	.box_three_span_c {
		display: flex;
	}
	.box_three_span_b {
		display: flex;
	}
	.box_three_span_b button {
		width: 14vw;
		height: 4.3vh;
		font-size: 10rpx;
		margin-top: 25rpx;
	}
	.box_three_span_a {
		margin-top: 30rpx;
		margin-left: 30rpx;
	}
	.box_three {
		width: 94%;
		height: 20vh;
		margin-top: 50rpx;
		background-color: #FFFFFF;
		border-radius: 20rpx;
	}
	.input_one {
		text-indent: 120rpx;
	}
	.input_two {
		text-indent: 60rpx;
	}
	.input_three {
		text-indent: 60rpx;
	}
	.input_four {
		text-indent: 60rpx;
	}
	.input_five {
		text-indent: 60rpx;
	}
	.input_six {
		text-indent: 60rpx;
	}
	.box_two_a_span_b {
		color: #f41717;
	}
	.box_two_b_span_b {
		color: #f41717;
	}
	.box_two_c_span_b {
		color: #f41717;
	}
	.box_two_d_span_b {
		color: #f41717;
	}
	.box_two_e_span_b {
		color: #f41717;
	}
	.box_two_f_span_b {
		color: #f41717;
	}
	.box_two_a {
		display: flex;
		margin-top: 40rpx;
		margin-left: 30rpx;
	}
	.box_two_b {
		display: flex;
		margin-top: 40rpx;
		margin-left: 30rpx;
	}
	.box_two_c {
		display: flex;
		margin-top: 40rpx;
		margin-left: 30rpx;
	}
	.box_two_d {
		display: flex;
		margin-top: 40rpx;
		margin-left: 30rpx;
	}
	.box_two_f {
		display: flex;
		margin-top: 40rpx;
		margin-left: 30rpx;
	}
	.box_two_e {
		display: flex;
		margin-top: 40rpx;
		margin-left: 30rpx;
	}
	.box_two {
		width: 94%;
		height: 40vh;
		margin-top: 50rpx;
		background-color: #FFFFFF;
		border-radius: 20rpx;
	}
	.box {
		width:100%;
		height: 100rpx;
		background-color:#FFFFFF;
	}
	.box_one {
		display: flex;
		margin-top: 30rpx;
		margin-left: 30rpx;
	}
	.image_a {
		width: 7vw;
		height: 3vh;
		margin-right: 220rpx;
	}
	.box_one_span_a {
		color: #333333;
		font-weight: 600;
		margin-right: 290rpx;
		
	}
	page {
		background-color: #F7F7F7;
	}
.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>
