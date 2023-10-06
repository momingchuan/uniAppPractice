<template>
	<view>
		<view>当前标题：{{title}}</view>
		<view>当前的数值：{{num}}</view>
		<view>当前的数组：{{arr[0]}}</view>
		<view>当前的数组：{{arr[1]}}</view>
		<view>当前的数组：{{arr[2]}}</view>
		<view>当前的对象名字：{{obj.name}}</view>
		<view>当前的对象年龄：{{obj.age}}</view>
		--------------------------------------- if else 使用
		<view v-if="day==1">周一</view>
		<view v-if="day==2">周二</view>
		<view v-if="day==3">周三</view>
		<view v-if="day==4">周四</view>
		<view v-if="day==5">周五</view>
		<view v-if="day==6">周六</view>
		<view v-if="day==7">周七</view>
		<view v-else>格式出错</view>
		---------------------------------------循环结构
	<!-- 	<view v-for="(value, name, index) in object"> -->
		<view v-for="(item,index) in arr" class="out">
			<view class="row">{{index+"-"+item}}</view>
			
			
		</view>
		---------------------------------------循环结构
			
		<view class="goods" v-for="item in goods">
			<view class="goods row">商品名称：{{item.title}}-   价格￥{{item.price}}</view>
		</view>
		
		
		
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title:"微信小程序",
				num:123,
				arr:["hello","world",6,6,6],
				obj:{name:"张三",age:22},
				day:7,
				
				goods:[
					{
						title:"商品1",
						price:22.5
					},
					{
						title:"商品2",
						price:35.0
					}
				]
			};
		}
	}
</script>

<style lang="scss">

.out{
	.row{
		font-size: 50rpx;
		border-bottom:1rpx solid #ccc;
	}
}

</style>


<!-- 3.3完 -->