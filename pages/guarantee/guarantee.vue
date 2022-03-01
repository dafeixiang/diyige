<template>
	<view class="content">
		<view class="box_first">
		<view class="box_one">
			<image class="image_one" src="../../static/img/fanhui.png" mode=""></image>
			<view class="span_one" v-for="(item,index) in list">
				{{item.name}}
			</view>
		</view>
		<image class="image_two" src="../../static/img/fenxiang@3x.png" mode=""></image>
		<view class="span_five">
			<uni-data-checkbox mode="tag" v-model="value" :localdata="range" @change="change"></uni-data-checkbox>
		</view>
	</view>
	<view class="box_three">
		<view class="box_three_a" v-for="(item,index) in list">
			<view class="box_three_a_a">
				{{item.name_a}}
			</view>
			<view class="box_three_a_b">
				{{item.name_c}}
			</view>
		</view>
		<view class="box_three_b">
			<view class="box_three_b_a" v-for="(item,index) in list">
				{{item.name_d}}
			</view>
			<view class="box_three_b_b" v-for="(item,index) in list">
				{{item.num_a}}
			</view>
			<view class="box_three_b_c" v-for="(item,index) in list">
				{{item.name_e}}
			</view>
			<view class="box_three_b_d" v-for="(item,index) in list">
				{{item.num_b}}
			</view>
		</view>
		<view class="box_three_c">
			<view class="box_three_c_a" v-for="(item,index) in list">
				{{item.name_f}}
			</view>
			<view class="box_three_c_b" v-for="(item,index) in list">
				{{item.num_c}}
			</view>
		</view>
		<!-- 横线 -->
		<view class="divider_b"/>
		<view class="box_four">
			<button class="button_one" type="default" v-for="(item,index) in list">{{item.name_g}}</button>
			<button class="button_two" type="default" v-for="(item,index) in list">{{item.name_h}}</button>
		</view>
	</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				value: 0,
				range: [{"value": 0,"text": "全部"    },{"value": 1,"text": "待完成"},{"value": 2,"text": "已完成"}],
				list:[
					{
					  name:'平台担保',
					  name_a:'物品名称:土鸡肉',
					  name_c:'卖出',
					  name_d:'物品价格:',
					  name_e:'电话号码:',
					  name_f:'快递单号:',
					  name_g:'确认收货',
					  name_h:'分享订单',
					  num_a:'150元',
					  num_b:'15564412227',
					  num_c:'256959933344233'
					},
				],
			}
		},
		methods: {
			change(e){
			            console.log('e:',e);
			        }
		}
	}
</script>

<style>
	.box_four {
		display: flex;
		margin-top: 30rpx;
	}
	.box_four button {
		width: 25vw;
		height: 4vh;
		line-height: 4vh;
		font-size: 32rpx;
		margin-right: 10rpx;
	}
	.button_one {
		margin-left: 300rpx;
		font-weight: 400;
		color: #FF3E1E;
		border: 1rpx solid #FF3E1E;
		background-color: #FFFFFF;
	}
	.button_two {
		background-color: #FF3E1E;
		color: #FFFFFF;
	}
	.divider_b{
		 background: #F7F7F7;
		 width: 98%;
		 height: 5rpx;
		 margin-left: 10rpx;
		 margin-top: 30rpx;
		}
	.box_three_c {
		display: flex;
		margin-top: 20rpx;
	}
	.box_three_c_b {
		margin-left: 10rpx;
	}
	.box_three_c_a {
		color: #999999;
		font-size: 31rpx;
		margin-left: 15rpx;
	}
	.box_three_b_a {
		color: #999999;
		font-size: 31rpx;
		margin-left: 15rpx;
	}
	.box_three_b_b {
		margin-left: 10rpx;
		font-size: 31rpx;
	}
	.box_three_b_c {
		color: #999999;
		font-size: 31rpx;
		margin-left: 125rpx;
		font-size: 31rpx;
	}
	.box_three_b_d {
		margin-left: 10rpx;
		font-size: 31rpx;
	}
	.box_three_b {
		display: flex;
		margin-top: 20rpx;
	}
	.box_three {
		background-color: #FFFFFF;
		margin-top: 40rpx;
		width: 94vw;
		height: 26vh;
		border-radius: 20rpx;
	}
	.box_three_a {
		display: flex;
		margin-top: 30rpx;
	}
	.box_three_a_a {
		margin-left: 15rpx;
	}
	.box_three_a_b {
		margin-left: 380rpx;
		color: #35A1DF;
	}
	.box_first {
		background-color: #FFFFFF;
		
	}
	.span_five {
		margin-right: 280rpx;
		margin-top: 20rpx;
	}
	.box_two {
		display: flex;
		margin-right: 300rpx;
	}
	.box_two view {
		margin-left: 30rpx;
	}
.image_two {
		width: 94vw;
		height: 20vh;
		margin-top: 30rpx;
	}
	.box_one {
		display: flex;
		margin-top: 30rpx;
		margin-right: 315rpx;
	}
	.span_one {
		font-size: 35rpx;
		font-weight: 700;
		color: #333333;
		margin-left: 195rpx;
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
	  page {
		  background-color: #F7F7F7;
	  }
</style>
