<template>
	<view>
		<view class="uni-padding-wrap">
			<swiper class="swiper" :indicator-dots="true" :autoplay="true" :interval="1000">
				<swiper-item>
					<view class="swiper-item">
						<image class="logo" src="/static/logo.png"></image>
					</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item">
						<image class="logo" src="/static/logo.png"></image>
					</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item">
						<image class="logo" src="/static/logo.png"></image>
					</view>
				</swiper-item>
			</swiper>
		</view>
	
		<view></view>
	</view>
</template>

<script>
	export default {
		data() {
			return {}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="scss" scoped>
</style>
