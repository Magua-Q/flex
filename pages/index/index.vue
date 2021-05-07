<template>
	<view class="content box">
		<!-- <image class="logo" src="/static/logo.png"></image> -->
		<!-- <view class="text-area">
			<text class="title">{{title}}</text>
			<text>我是猪</text>
		</view> -->
		
		<view class="content-item">
			1
		</view>
		<view class="content-item">
			2
		</view>
		<view class="content-item">
			3
		</view>
		<view class="content-item">
			4
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
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
		/* flex-direction: row; 从左到右 */
		/* flex-direction: row-reverse; 从右到左 */
		/* flex-direction: column;从上到下 */
		flex-direction: column-reverse;
	}
</style>
