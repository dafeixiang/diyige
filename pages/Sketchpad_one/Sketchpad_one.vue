<template>
	<view class="content">
		<view class="Home">
			<view class="span_one">
				成都
			</view>
			<image class="image_one" src="../../static/img/dingwei@3x.png" mode=""></image>
			<input class="input_one" type="text" value="" placeholder="       找房子 找工作 找好货" />
			<image class="image_two" src="../../static/img/xiaoxi@3x.png" mode=""></image>
		</view>
		<!-- 轮播图 -->
		<view class="Carousel">
			<view class="uni-padding-wrap">
				<view class="page-section swiper">
					<view class="page-section-spacing">
						<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval"
							:duration="duration">
							<swiper-item>
								<view class="box_one"></view>
							</swiper-item>
							<swiper-item>
								<view class="box_two"></view>
							</swiper-item>
							<swiper-item>
								<view class="box_three"></view>
							</swiper-item>
							<swiper-item>
								<view class="box_four"></view>
							</swiper-item>
							<swiper-item>
								<view class="box_five"></view>
							</swiper-item>
						</swiper>

					</view>
				</view>
			</view>
		</view>
		<!-- 轮播图上 -->
        <view class="classify_one">
			 <image src="../../static/classify/qiuzhi@3x.png" mode=""></image>
			 <image src="../../static/classify/zushou@3x.png" mode=""></image>
			 <image src="../../static/classify/zhoubianyou@3x.png" mode=""></image>
			 <image src="../../static/classify/ershoumaimai@3x.png" mode=""></image>
			 <image src="../../static/classify/xiangqiang@3x.png" mode=""></image>
        </view>
		<view class="span_first">
			<view-span>招聘求职</view-span>
			<view-span>房屋租售</view-span>
			<view-span>周边游</view-span>
			<view-span>二手买卖</view-span>
			<view-span>相亲交友</view-span>
		</view>
	    <view class="classify_two">
	    	  <image src="../../static/classify/zoxun@3x.png" mode=""></image>
			  <image src="../../static/classify/bendifuwu@3x.png" mode=""></image>
			  <image src="../../static/classify/zhuangrang@3x.png" mode=""></image>
			  <image src="../../static/classify/pingche@3x.png" mode=""></image>
			  <image src="../../static/classify/ershouche@3x.png" mode=""></image>
	    </view>
		<view class="span_second">
			  <view-span>咨询求职</view-span>
			  <view-span>便民电话</view-span>
			  <view-span>门店转让</view-span>
			  <view-span>顺风拼车</view-span>
			  <view-span>二手车</view-span>
		</view>
		<view class="classify_three">
			   <image src="../../static/classify/chongwu@3x.png" mode=""></image>
			   <image src="../../static/classify/miaosha@3x.png" mode=""></image>
			   <image src="../../static/classify/tuangou@3x.png" mode=""></image>
			   <image src="../../static/classify/muyi@3x.png" mode=""></image>
			   <image src="../../static/classify/shangchao@3x.png" mode=""></image>
		</view>
	    <view class="span_third">
	    	  <view-span>宠物交易</view-span>
			  <view-span>秒杀</view-span>
			  <view-span>团购</view-span>
			  <view-span>母婴用品</view-span>
			  <view-span>附件商超</view-span>
	    </view>
		<view class="box_first">
			<view class="city">
			<view class="span_four">
				同城
			</view>
			<view class="span_five">
				最新
			</view>
			<view class="span_six">
				找工作怎么找更有效容易，带你看看找工作方法...
			</view>
			</view>
			<!-- 横线 -->
			<view class="divider"/>
			<!-- 分6 -->
			<view class="module">
				<view class="module_one">
					<view class="span_one_a">
						自产自销
					</view>
					<view class="span_one_b">
						农家产品自产
					</view>
				<image src="../../static/liuwa@3x.png" mode=""></image>
				</view>
				<view class="module_two">
					<view class="span_two_a">
						宾馆住宿
					</view>
					<view class="span_two_b">
						住宿便携服务
					</view>
				<image src="../../static/bingguang@3x.png" mode=""></image>
				</view>
				<view class="module_three">
					<view class="span_three_a">
							旅游租车
						</view>
						<view class="span_three_b">
							租车更快出游
						</view>
					<image src="../../static/zuche@3x.png" mode=""></image>
				</view>
			</view>
			<view class="module2">
				<view class="module_four">
					<view class="span_four_a">
							特价门票
						</view>
						<view class="span_four_b">
							每日特价门票
						</view>
					<image src="../../static/tejiamenpiao@3x.png" mode=""></image>
				</view>
				<view class="module_five">
					<view class="span_five_a">
							电视频道
						</view>
						<view class="span_five_b">
							本地CCTV
						</view>
					<image src="../../static/dianshipingdao@3x.png" mode=""></image>
				</view>
				<view class="module_six">
					<view class="span_six_a">
							短视频
						</view>
						<view class="span_six_b">
							趣味短视频
						</view>
					<image src="../../static/img/duanshiping@3x.png" mode=""></image>
				</view>
			</view>
		</view>
	     <view class="platform">
<!-- 			 <view class="platform_span">
			 	<view class="platform_span_a">
			 		平台担保
			 	</view>
			 	<view class="platform_span_b">
			 		蓉城发布
			 	</view>
			 	<view class="platform_span_c">
			 		商家认证
			 	</view>
			 </view> -->
	     	<image src="../../static/img/pingtai@3x.png" mode=""></image>
			<image src="../../static/img/jinbi@3x.png" mode=""></image>
			<image src="../../static/img/renzheng@3x.png" mode=""></image>
	     </view>
		 <view class="platform_two">
		 	<image src="../../static/img/fenxiang@3x.png" mode=""></image>
			<image src="../../static/img/hehuo@3x.png" mode=""></image>
		 </view>
		 <view class="platform_three">
		 	<image src="../../static/img/bendizixun@3x.png" mode=""></image>
		 </view>
		 <view class="span_seven">
		 	<view-span class="span_seven_a">最新发布</view-span>
			<view-span class="span_seven_b">New</view-span>
		 </view>
		 <view class="span_eight">
		 	学习宣扬贯彻党的十九大 学习宣扬贯彻党...
		 </view>
		 <view class="image_three">
		 	<image class="image_three_a" src="../../static/img/jinbi@3x.png" mode=""></image>
			<image class="image_three_b" src="../../static/img/pingtai@3x.png" mode=""></image>
			<image class="image_three_c" src="../../static/img/renzheng@3x.png" mode=""></image>
		 </view>
		 <view class="span_nine">
		 	<view-span class="span_nine_a">最新科技</view-span>
			<view-span class="span_nine_b">2021-02-12</view-span>
			<view-span class="span_nine_c">1.6km</view-span>
		 </view>
		 <!-- 横线 -->
		 <view class="divider"/>
		 <view class="box_six">
		 	<view class="span_ten">
		 		防部国防部：全军和武警部队官
		 		深入学习贯彻党的十九届五...
		 	</view>
			<image class="image_four" src="../../static/img/jinbi@3x.png" mode=""></image>
		 </view>
		 <view class="span_nine_one">
		 	<view-span class="span_nine_one_a">国防部发布</view-span>
		 	<view-span class="span_nine_one_b">1小时前</view-span>
		 	<view-span class="span_nine_one_c">1.3km</view-span>
		 </view>
		 <!-- 横线 -->
		 <view class="divider"/>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				background: ['color1', 'color2', 'color3'],
				indicatorDots: true,
				autoplay: true,
				interval: 2000,
				duration: 500
			}
		},
		methods: {
			changeIndicatorDots(e) {
				this.indicatorDots = !this.indicatorDots
			},
			changeAutoplay(e) {
		 	this.autoplay = !this.autoplay
			},
			intervalChange(e) {
				this.interval = e.target.value
			},
			durationChange(e) {
				this.duration = e.target.value
			}
		}
	}
</script>

<style>
	.image_four {
		width: 42vw;
		height: 8vh;
		margin-right: 20rpx;
	}
	.span_ten {
		font-size: 28rpx;
		margin-left: 35rpx;
	}
	.box_six {
		display: flex;
		margin-top: 40rpx;
	}
	.span_nine_one {
		color: #999999;
		font-size: 28rpx;
		margin-top: 15rpx;
		margin-left: 15rpx;
	}
	.span_nine_one_b {
		margin-left: 50rpx;
	}
	.span_nine_one_c {
		margin-left: 330rpx;
	}
	/*  */
	.span_nine {
		color: #999999;
		font-size: 28rpx;
		margin-top: 15rpx;
		margin-left: 15rpx;
	}
	.span_nine_b {
		margin-left: 50rpx;
	}
	.span_nine_c {
		margin-left: 300rpx;
	}
	.image_three {
		display: flex;
	}
	.image_three image {
		width: 29vw;
		height: 9vh;
		margin-left: 18rpx;
		margin-top: 20rpx;
	}
	.span_eight {
		font-size: 32rpx;
		margin-top: 30rpx;
		margin-right:90rpx;
	}
	.span_seven {
		display: flex;
	}
	.span_seven_a {
		font-size: 35rpx;
		color: #fe1931;
		font-weight: 700;
		margin-top: 30rpx;
		margin-right: 10rpx;
	}
	.span_seven_b {
		font-size: 18rpx;
		color:#fe1931;
		border: 1rpx solid #fe1931;
		height: 2vh;
		margin-top: 39rpx;
		margin-right: 490rpx;
	}
	.platform_three image {
		width: 93vw;
		height: 13vh;
		margin-left: 12rpx;
		margin-top: 30rpx;
	}
	.platform_two image {
		width: 336rpx;
		height: 140rpx;
		margin-top: 30rpx;
		margin-left: 30rpx;
		right: 6rpx;
	}
	.platform image {
		width: 215rpx;
		height: 120rpx;
		margin-left: 30rpx;
		right: 10rpx;
		margin-top: 30rpx;
	}
	.span_one_b {
		font-size: 10rpx;
		position: absolute;
		margin-top: 40rpx;
		color: #c0c0c0;
	}
	.span_two_b {
		font-size: 10rpx;
		position: absolute;
		margin-top: 40rpx;
		color: #c0c0c0;
	}
	.span_three_b {
		font-size: 10rpx;
		position: absolute;
		margin-top: 40rpx;
		color: #c0c0c0;
	}
	.span_four_b {
		font-size: 10rpx;
		position: absolute;
		margin-top: 40rpx;
		color: #c0c0c0;
	}
	.span_five_b {
		font-size: 10rpx;
		position: absolute;
		margin-top: 40rpx;
		color: #c0c0c0;
	}
	.span_six_b {
		font-size: 10rpx;
		position: absolute;
		margin-top: 40rpx;
		color: #c0c0c0;
	}
	.module2 {
		display: flex;
	}
	.module2 image {
		width:72rpx ;
		height: 72rpx;
		margin-left: 30rpx;
	}
	.span_one_a {
		font-size: 26rpx;
	}
	.span_two_a {
		font-size: 26rpx;
	}
	.span_three_a {
		font-size: 26rpx;
	}
	.span_four_a {
		font-size: 26rpx;
	}
	.span_five_a {
		font-size: 26rpx;
	}
	.span_six_a {
		font-size: 26rpx;
	}
	.module_six image {
		margin-left: 55rpx;
	}
	.module {
		display: flex;
	}
	.module_four {
		display: flex;
		margin-left: 30rpx;
		margin-top: 50rpx;
	}
	.module_five {
		display: flex;
		margin-left: 30rpx;
		margin-top: 50rpx;
	}
	.module_six {
		display: flex;
		margin-left: 30rpx;
		margin-top: 50rpx;
	}
	.module_three {
		display: flex;
		margin-left: 30rpx;
		margin-top: 50rpx;
	}
	.module_two {
		display: flex;
		margin-left: 30rpx;
		margin-top: 50rpx;
	}
	.module_one {
		display: flex;
		margin-left: 30rpx;
		margin-top: 50rpx;
	}
	.module image {
		width:72rpx ;
		height: 72rpx;
		margin-left: 30rpx;
	}
	.divider{
		 background: #E0E3DA;
		 width: 98%;
		 height: 5rpx;
		 margin-left: 10rpx;
		 margin-top: 10rpx;
		}
	.span_six{
		font-size: 25rpx;
		margin-top: 10rpx;
		margin-left: 10rpx;
		margin-top: 16rpx;
	}
	.city {
         display: flex;
	}
	.span_four {
		display: flex;
		color: #fe073a;
		font-size: 36rpx;
		font-weight: 900;
		margin-top: 10rpx;
		margin-left: 15rpx;
	}
	.span_five {
		border: 1rpx solid #fe3767;
		border-radius: 10rpx;
		font-size: 10rpx;
		font-weight: 500;
		height: 34rpx;
		color: #fe3767;
		margin-top: 16rpx;
		margin-left: 20rpx;
	}
	.box_first {
		width: 700rpx;
		height: 360rpx;
		background-color: #ffffff;
		margin-top: 30rpx;
	}
	.span_first view-span {
		margin-left: 24rpx;
		font-size: 30rpx;
		color: #959595;
	}
	.span_second view-span {
		margin-left: 24rpx;
		font-size: 30rpx;
		color: #959595;
	}
	.span_third view-span {
		margin-left: 46rpx;
		font-size: 30rpx;
		color: #959595;
	}
	.classify_one image{
		margin-left: 38rpx;
		right: 10rpx;
		margin-top: 40rpx;
		width: 100rpx;
		height: 100rpx;
	}
	.classify_two image{
		margin-left: 38rpx;
		right: 10rpx;
		margin-top: 40rpx;
		width: 100rpx;
		height: 100rpx;
	}
	.classify_three image{
		margin-left: 38rpx;
		margin-top: 40rpx;
		right: 10rpx;
		width: 100rpx;
		height: 100rpx;
	}
	/* 轮播图 */
	.swiper {
		width: 700rpx;
		height: 300rpx;
	}
	.Carousel {
		margin-top: 50rpx;
		
	}
	.box_one {
		background-color: #007AFF;
		width: 700rpx;
		height: 300rpx;
	}

	.box_two {
		background-color: #18BC37;
		width: 700rpx;
		height: 300rpx;
	}

	.box_three {
		background-color: #F0AD4E;
		width: 700rpx;
		height: 300rpx;
	}
	
	.box_four {
		background-color: #FFFF00;
		width: 700rpx;
		height: 300rpx;
	}
	
	.box_five {
		background-color: #FF00FF;
		width: 700rpx;
		height: 300rpx;
	}

	/* 轮播图上 */
	.input_one {
		width: 480rpx;
		height: 80rpx;
		background-color: #f4f4f4;
		border-radius: 35rpx;
		text-indent: 30rpx;
		margin-top: 35rpx;
		margin-right: 20rpx;
		background-image: url(../../static/img/sousuo@2x.png);
		background-repeat: no-repeat;
		background-position: 40rpx;
	}

	.Home {
		display: flex;
	}

	.image_one {
		display: flex;
		width: 35rpx;
		height: 32rpx;
		margin-top: 58rpx;
		margin-right: 20rpx;
	}

	.image_two {
		display: flex;
		width: 50rpx;
		height: 50rpx;
		margin-top: 50rpx;
	}

	.span_one {
		display: flex;
		margin-right: 10rpx;
		margin-top: 50rpx;
	}

	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	page {
		  background-color: #fcfbfb;
	}
</style>
