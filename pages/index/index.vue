<template>
	<view class="out">
		<view class="box"></view>
		<view class="block"></view>
		 <icon type="success_no_circle" size="26"/>
		<icon type="cancel" size="26"/>
		<view>uniApp </view>
		<view>Web前端开发</view>
		<text user-select selectable> nodejs span</text>
		<text space="ensp">你好吗？    o</text>
		
		<scroll-view class="scroll" scroll-x scroll-y>
			<view class="group">
				<view class="item">
					111
				</view>
				<view class="item">
					112
				</view>
				<view class="item">
					113
				</view>
				<view class="item">
					114
				</view>
				<view class="item">
					115
				</view>
			</view>
		</scroll-view>

		<swiper class="swiper" circular duration="1000">
			<swiper-item class="item">
				<image src="../../static/images/q.jpg" mode=""></image>
				</swiper-item >
			<swiper-item class="item">
				<image src="../../static/images/q2.jpg" mode=""></image>
				</swiper-item>
			<swiper-item class="item">
				<image src="../../static/images/q3.jpg" mode=""></image>
			</swiper-item>
					
		</swiper>
	</view>

</template>

<script>
	export default {

	}
</script>

<style lang="scss">

.out{
	.box{
		width: 200px;
		height: 200px;
		background: pink;
	}
	.block{
		width: 750rpx;
		height: 200rpx;
		background: gray;
		
		
		


		
	}

	
}

	.scroll{
	
	border: 1px solid  red;
	box-sizing: border-box;
	height: 120rpx;
		.group{
			white-space: nowrap;
			.item{
				width: 220rpx;
				height: 220rpx;
				background: greenyellow;
				display: inline-block;
				margin-right: 10rpx;
			}
		}
		
	}
	
	
	
</style>


/*2.5 完*/