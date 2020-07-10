<template>
	<view class="content">
		<MyProgress :nowD="80" :sumD="100" :content='"LV 20"' :contentColor='"rgba(3,144,252,1)"' :contentBacColor='"#ffffff"' :time="3000" :wid="280" :type='"linear"'></MyProgress>
	</view>
</template>

<script>
	import MyProgress from "@/components/my-progress.vue"
	export default {
		components: {
			MyProgress
		},
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
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		background-color: #007AFF;
		height: 500rpx;
	}

	

</style>
