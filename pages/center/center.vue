<template>
	<view class="box">
		<view class="container">
			这是center
		</view>
		<view class="container item-tall">
			这是center
		</view>
		<view class="container">
			这是center
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
.box {
	display: flex;
	width: 100%;
}
.container {
	width: 100%;
	justify-content: space-between;
	align-items: flex-end;
}
.item-tall {
	height: 100px;
	/* width: 100px; */
	background-color: #007AFF;
}
</style>
