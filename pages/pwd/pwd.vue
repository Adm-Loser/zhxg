<template>
    <view class="content">
		<view class="pwd-box">
			<view class="pwd-title-box">
				<text class="pwd-title">邮箱找回密码</text>
			</view>
			<view class="input-group">
			    <view class="input-row">
					 <image src="../../static/img/account.png" mode="aspectFill" style="width: 60rpx; height: 60rpx; margin-top: 10rpx; margin-left: 15rpx;"></image>  
			        <m-input type="text" placeholder=""></m-input>
			    </view>
			</view>
			
			<view class="input-group">
			    <view class="input-row">
			        <image src="../../static/img/verification.png" mode="aspectFill" style="width: 60rpx; height: 60rpx; margin-top: 10rpx; margin-left: 15rpx;"></image>  
			        <m-input type="text" placeholder=""></m-input>
					<image src="../../static/img/verification-code.png" mode="aspectFill" style="width: 180rpx; height: 90rpx; float: right; border-left: 1px solid #C8C7CC;"></image> 
			    </view>
			</view>
			
			<view class="btn-row">
			    <button type="primary" class="primary" @tap="findPassword">下一步</button>
			</view>
		</view>
    </view>
</template>

<script>
    import service from '../../service.js';
    import mInput from '../../components/m-input.vue';

    export default {
        components: {
            mInput
        },
        data() {
            return {
                email: ''
            }
        },
        methods: {
            findPassword() {
                /**
                 * 仅做示例
                 */
                if (this.email.length < 3 || !~this.email.indexOf('@')) {
                    uni.showToast({
                        icon: 'none',
                        title: '邮箱地址不合法',
                    });
                    return;
                }
                uni.showToast({
                    icon: 'none',
                    title: '已发送重置邮件至注册邮箱，请注意查收。',
                    duration: 3000
                });
            }
        }
    }
</script>

<style>
	.pwd-box {
		width: 100%;
		height: auto;
		margin-top: 20rpx;
		background-color: #FFFFFF;
	}
	.pwd-title-box {
		background-color: #d0e5fd;
		height: 100rpx;
		width: 100%;
		text-align: center;
	}
	.pwd-title {
		font-size: 40rpx;
		color: #007AFF;
		line-height: 50px;    
	}
	.input-group {
		margin-top: 30upx;
		border-radius: 5px;
		border: 1px solid #C8C7CC;
		overflow: hidden;
		width: 90%;
		margin-left: auto;
		margin-right: auto;
	}
	.input-row {
		height: 80rpx;
	}
	.btn-row {
		width: 90%;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 20rpx;
	}
</style>
