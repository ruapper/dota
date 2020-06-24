<template>
	<view>
		<!-- 游戏资料 -->
		<view class="content">
			<navigator url="../heroItem/hero">
				<image src="../../static/img/hero.png"></image>
				<view>英雄</view>
			</navigator>
			<navigator url="../heroItem/item">
				<image src="../../static/img/items.png"></image>
				<view>物品</view>
			</navigator>
			<navigator url="/pages/player/player">
				<image src="../../static/img/teams.png"></image>
				<view>战队</view>
			</navigator>
			<navigator url="/pages/team/team">
				<image src="../../static/img/player.png"></image>
				<view>选手</view>
			</navigator>
		</view>
		<!-- 近期比赛 -->
		<view></view>
	</view>
</template>

<script>
	export default {
		data() {
			return {}
		},
		onLoad() {},
			methods: {
				// 获取英雄数据
				// toHero() {
				// 	console.log(1)
				// },
				// // 获取物品数据
				// toItem() {
				// 	console.log(2)
				// },
				// // 获取战队数据
				// toTeam() {
				// 	console.log(3)
				// },
				// // 获取选手数据
				// toPlayer() {
				// 	console.log(4)
				// }
			}
		}
</script>

<style lang="scss" scoped>
	.content {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-around;

		navigator {
			display: flex;
			flex-direction: column;
			align-items: center;

			image {
				width: 120rpx;
				height: 120rpx;
			}
		}
	}
</style>
