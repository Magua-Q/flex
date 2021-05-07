<template>
	<view class="container box">
		<view class="content-item">1</view>
		<view class="content-item">2</view>
		<view class="content-item">3</view>
		<view class="content-item">4</view>
		<view class="content-item">5</view>
		<view class="content-item">6</view>
		<view class="content-item">7</view>
		<view class="content-item">8</view>
		<view class="content-item">9</view>
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
	.container {
		background-color: #FFFFFF;
		margin: 0 0 55px;
		display: flex;
	}
	.content-item {
		height: 200px;
		width: 200px;
		background: yellow;
		text-align: center;
		line-height: 200px;
		margin: 5px
	}
	.box {
		/* flex-direction: row;
		flex-wrap: nowrap; */
		/* flex-wrap: nowrap; */
		/* flex-wrap: wrap-reverse; 反向换行*/
		flex-flow: row nowrap;
	}
</style>
