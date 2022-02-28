<template>
	<view class="content">
		<view class="span_one_a">
			邀請好友
		</view>
		<!-- 轮播图 -->
		<view class="Carousel">
			<view class="uni-padding-wrap">
				<view class="page-section swiper">
					<view class="page-section-spacing">
						<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval"
							:duration="duration">
							<swiper-item>
								<image class="box_one" src="../../static/img/butanmengxiang.png" mode=""></image>
							</swiper-item>
							<swiper-item>
								<image class="box_two" src="../../static/img/zufangmianfei.png" mode=""></image>
							</swiper-item>
							<swiper-item>
								<image class="box_three" src="../../static/img/ershouche.png" mode=""></image>
							</swiper-item>
							<swiper-item>
								<image class="box_four" src="../../static/tongchengxiangqing.png" mode=""></image>
							</swiper-item>
							<swiper-item>
								<image class="box_five" src="../../static/img/banner@3x.png" mode=""></image>
							</swiper-item>
						</swiper>
		
					</view>
				</view>
			</view>
		</view>
		<!-- 轮播图上 -->
		<button class="span_one_b" type="default">
			分享海報
		</button>
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
	.span_one_b {
		width: 90vw;
		height: 7vh;
		margin-top: 50rpx;
		color: #ff3e1e;
		line-height: 7vh;
	}
	.span_one_a {
		font-size: 38rpx;
		color: #ffffff;
		margin-top: 30rpx;
	}
/* 轮播图 */
	.swiper {
		width: 90vw;
		height: 75vh;
	}
	.Carousel {
		margin-top: 30rpx;
		
	}
	.box_one {
		width: 90vw;
		height: 75vh;
	}

	.box_two {
		width: 90vw;
		height: 75vh;
	}

	.box_three {
		width: 90vw;
		height: 75vh;
	}
	
	.box_four {
		width: 90vw;
		height: 75vh;
	}
	
	.box_five {
		width: 90vw;
		height: 75vh;
	}

	/* 轮播图上 */
  .content {
  	display: flex;
  	flex-direction: column;
  	align-items: center;
  	justify-content: center;
  }
  page {
  	  background-color: #FF3E1E;
  }
</style>
