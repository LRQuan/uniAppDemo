<template>
	<view class="goodsList">
		<view class="search">搜索</view>
		<view class="config">
			<view>取餐点</view>
			<view>取餐点</view>
			<view>取餐点</view>
		</view>
		<view class="leftBox">
			<view v-for="item in shopList" class="shopItem">
				{{ item.name }}
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				shopList:[
					{
						name:"店铺1",
						goodsList:[
							{
								image:"https://erp-goods-images.oss-cn-shenzhen.aliyuncs.com/615/cakovbeas19r1hi7aqbg.jpeg",
								name:"萝卜炖牛腩"
							},
							{
								image:"https://erp-goods-images.oss-accelerate.aliyuncs.com/upload/images/goods/20643/HD000141.jpg",
								name:"金项链"
							}
						]
					},{
						name:"店铺1",
						goodsList:[
							{
								image:"https://erp-goods-images.oss-cn-shenzhen.aliyuncs.com/615/cakovbeas19r1hi7aqbg.jpeg",
								name:"萝卜炖牛腩"
							},
							{
								image:"https://erp-goods-images.oss-accelerate.aliyuncs.com/upload/images/goods/20643/HD000141.jpg",
								name:"金项链"
							}
						]
					},{
						name:"店铺1",
						goodsList:[
							{
								image:"https://erp-goods-images.oss-cn-shenzhen.aliyuncs.com/615/cakovbeas19r1hi7aqbg.jpeg",
								name:"萝卜炖牛腩"
							},
							{
								image:"https://erp-goods-images.oss-accelerate.aliyuncs.com/upload/images/goods/20643/HD000141.jpg",
								name:"金项链"
							}
						]
					},{
						name:"店铺1",
						goodsList:[
							{
								image:"https://erp-goods-images.oss-cn-shenzhen.aliyuncs.com/615/cakovbeas19r1hi7aqbg.jpeg",
								name:"萝卜炖牛腩"
							},
							{
								image:"https://erp-goods-images.oss-accelerate.aliyuncs.com/upload/images/goods/20643/HD000141.jpg",
								name:"金项链"
							}
						]
					}
				],
			};
		}
	}
</script>

<style lang="scss">
.goodsList{
	.search{
		background-color: blue;
		height: 2.5em;
	}
	.leftBox{
		height: 100%;
		width: 5em;
		background-color: red;
		.shopItem{
			padding: 3px;
		}
	}
}
</style>
