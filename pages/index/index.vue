<template>
	<view class="container" >
		<view class="rectangle-1">
			<view class="group-30">
				<image class="group-1" src="../../images/三杠.png" mode=""></image>
				<view class="lucknow"><text>lucknow</text></view>
				<image class="vector" src="../../images/搜索.png" mode=""></image>
			</view>
			<view class="group-31">
				<view class="w28">
					28
					<view class="du">
						℃
					</view>
				</view>
				<view class="sunset-clouds">
					Sunset,Clouds
				</view>
			</view>
			
		</view>
		<view class="rectangle-2">
			<view class="ellipse-1">
				<image class="ellipsis-1-img" src="../../images/加号.png" mode=""></image>
			</view>
		</view>
		<view class="rectangle-3">
			<view class="today0">
				<view class="today1">
					Today
				</view>
				<view class="today2">
					Lucknnew,Uttar Pradesh
				</view>	
			</view>
			<view class="tianqi">
				<view class="tian0">
					<text>Now</text>
					<image src="../../images/Group5.png" mode=""></image>
					<text>22°</text>
				</view>
				<view class="tian0">
					<text>3PM</text>
					<image src="../../images/阴天.png" mode=""></image>
					<text>20°</text>
				</view>
				<view class="tian0">
					<text>4PM</text>
					<image src="../../images/阴天.png" mode=""></image>
					<text>18°</text>
				</view>
				<view class="tian0">
					<text>5PM</text>
					<image src="../../images/阴天.png" mode=""></image>
					<text>22°</text>
				</view>
				<view class="tian0">
					<text>6PM</text>
					<image src="../../images/阴天.png" mode=""></image>
					<text>16°</text>
				</view>
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
	. {
		width: 750rpx;
		height: 1418rpx;
	}
	.container {
		width: 100%;
		height: 100%;
	}
	.rectangle-1 {
		width: 750rpx;
		height: 1000rpx;
		display: flex;
		background-image: url(../../images/背景1.png);
		flex-direction: column;
	}
	.group-30 {
		width: 656rpx;
		height: 42rpx;
		display: flex;
		justify-content: space-between;
		margin-top: 70rpx;
		position: absolute;
		margin-left: 40rpx;
	}
	.group-1 {
		width: 46rpx;
		height: 42rpx;
		float: left;
	}
	.vector {
		width: 36rpx;
		height: 36rpx;
		float: right;
	}
	.lucknow {
		width: 176rpx;
		height: 38rpx;
		font-size: 44rpx;
		color: #ffffff;	
		flex-grow: <2>
	}
	.group-31 {
		width: 302rpx;
		height: 240rpx;
		position: absolute;
		align-self: center;
		margin-top: 394rpx;
		display: flex;
		flex-direction: column;
	}
	.w28 {
		width: 212rpx;
		height: 146rpx;
		font-size: 198rpx;
		color: #ffffff;
		margin-top: -50rpx;
		display: flex;
	}
	.du{
		height: 50rpx;
		width: 50rpx;
		font-size: 60rpx;
		color: #ffffff;
		float: right;
		margin-top: 30rpx;
	}
	.sunset-clouds {
		width: 292rpx;
		height: 44rpx;
		font-size: 44rpx;
		color: #ffffff;
		margin-top: 90rpx;
	}
	.ellipse-1 {
		width: 120rpx;
		height: 120rpx;
		margin-left: 550rpx;
		margin-top: -55rpx;
	}
	.ellipsis-1-img{
		height: 100%;
		width: 100%;
	}
	.rectangle-3{
		width: 750rpx;
		height: 250rpx;
	}
	.today0{
		width: 750rpx;
		height: 60rpx;
		top: 0;
	}
	.today1 {
		width: 110rpx;
		height: 40rpx;
		font-size: 40rpx;
		font-weight: bold;
		color: #000000;
		float: left;
		padding-left: 50rpx;
	}
	.today2{
		font-size: 25rpx;
		color: #000000;
		float: right;
		padding-top: 10rpx;
		padding-right: 50rpx;
	}
	.tianqi{
		display: flex;
		flex-direction: row;
		justify-content: space-around;
	}
	.tian0{
		width: 100rpx;
		height: 200rpx;
		display: flex;
		flex-direction: column;
	}
	.tian0 image{
		padding-top: 25rpx;
		width: 78rpx;
		height: 50rpx;
		align-self: center;
	}
	.tian0 text{
		padding-top: 20rpx;
		align-self: center;
	}
</style>
