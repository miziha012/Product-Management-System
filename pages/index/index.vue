<template>
	<view>
		<button @click="scanBarcode">扫描条形码123</button>
	</view>
</template>

<script>
	export default {
		methods: {
			scanBarcode() {
				uni.scanCode({
					onlyFromCamera: true,
					scanType: ['barCode'],
					success: (res) => {
						console.log('条形码信息：', res.result);
						// 在这里处理扫描结果
						uni.showToast({
							title: '扫描成功: ' + res.result,
							icon: 'none'
						});
					},
					fail: (err) => {
						console.log('扫描失败：', err);
						uni.showToast({
							title: '扫描失败',
							icon: 'none'
						});
					}
				});
			}
		}
	}
</script>