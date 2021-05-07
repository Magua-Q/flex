<template>
	<view class="body">
		<view class="header">
			头部
		</view>
		<view class="wrap">
			<scroll-view scroll-y="true" class="list">
				<view class="content">
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
					<view class="card">
						<view>
							<image src="@/static/mn.jpg" mode="widthFix"></image>
						</view>
						<view>布局</view>
						<view>免费</view>
					</view>
				</view>
			</scroll-view>
			
		</view>
		
		<view class="footer">
			<view class="item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>首页</view>
			</view>
			<view class="item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>首页</view>
			</view>
			<view class="item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>首页</view>
			</view>
			<view class="item">
				<image src="../../static/logo.png" mode="widthFix"></image>
				<view>首页</view>
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
.body {
	display: flex;
	flex-direction: column;
	height: 100vh;
}
.header {
	text-align: center;
	margin-top: 10px;
}
.wrap {
	position: relative;
	flex-grow: 1;
}
.content {
	
	display: flex;
	flex-direction: row;
	flex-wrap: wrap;
	justify-content: space-between;
	margin-left: 2vw;
	margin-right: 2vw;
}
.card {
	width: 47vw;
	margin-top: 10px;
	margin-bottom: 10px;
}
image {
	width: 100%;
	border-radius: 5px;
}
.footer {
	display: flex;
	justify-content: space-between;
}
.item {
	width: 45px;
	text-align: center;
	font-size: 14px;
	padding: 20px;
}
.item image {
	width: 39px; 
}
.list {
	position: absolute;
	left: 0;
	top: 0;
	righ: 0;
	bottom: 0;
}
</style>
