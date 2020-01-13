<template>
	<view class="container">
		<view class="basic-infor">
			<view class="title">
				<view class="title-view"></view>
				<text class="title-text">基本信息</text>
			</view>
			
			<view class="box">
				<text class="text-title">姓名</text>
				<input class="text-infor" type="text" value="文本标签" />
			</view>
			<view class="box">
				<text class="text-title">学号</text>
				<input class="text-infor" type="text" value="2016xxxxxx" />
			</view>
			<view class="box">
				<text class="text-title">性别</text>
				<input class="text-infor" type="text" value="男" />
			</view>
			<view class="box">
				<text class="text-title">班别</text>
				<input class="text-infor" type="text" value="16计本" />
			</view>
			<view class="box">
				<text class="text-title">专业</text>
				<input class="text-infor" type="text" value="计算机科学与技术" />
			</view>
			<view class="box">
				<text class="text-title">入学年份</text>
				<input class="text-infor" type="text" value="2016年" />
			</view>
			<view class="box">
				<text class="text-title">出生日期</text>
				<input class="text-infor" type="text" value="1997-12-24" />
			</view>
			<view class="box">
				<text class="text-title">QQ号</text>
				<input class="text-infor" type="text" value="456154864546" />
			</view>
			<view class="box">
				<text class="text-title">微信号</text>
				<input class="text-infor" type="text" value="123456553135" />
			</view>
			<view class="box">
				<text class="text-title">邮箱</text>
				<input class="text-infor" type="text" value="1456153135@qq.com" />
			</view>
			<view class="box">
				<text class="text-title">手机号</text>
				<input class="text-infor" type="text" value="123451354864" />
			</view>
			<view class="box">
				<text class="text-title">政治面貌</text>
				<input class="text-infor" type="text" value="共青团员" />
			</view>
			<view class="box">
				<text class="text-title">籍贯</text>
				<input class="text-infor" type="text" value="广东广州" />
			</view>
			<view class="box">
				<text class="text-title">家庭住址</text>
				<input class="text-infor" type="text" value="2016xxxx" />
			</view>
			
			<view class="box">
				<text class="text-title">操作</text>
				<navigator url="" class="btn1" style="margin-right: 50rpx;">修改</navigator>
				<navigator url="" class="btn1">保存</navigator>
			</view>
		</view>
		
		<view class="basic-infor">
			<view class="title">
				<view class="title-view"></view>
				<text class="title-text">干部经历</text>
				<navigator url="" class="btn2">添加</navigator>
			</view>
			
			<view class="box">
				<text class="text-infor">学生会干事</text>
				<navigator url="" class="btn4"> > </navigator>
			</view>
		</view>
		
		<view class="basic-infor">
			<view class="title">
				<view class="title-view"></view>
				<text class="title-text">获奖经历</text>
				<navigator url="" class="btn2">添加</navigator>
			</view>
			
			<view class="box">
				<text class="text-infor">IT文化节一等奖</text>
				<navigator url="" class="btn4"> > </navigator>
			</view>
		</view>
		
		<view class="basic-infor">
			<view class="title">
				<view class="title-view"></view>
				<text class="title-text">考取证书</text>
				<navigator url="" class="btn2">添加</navigator>
			</view>
			
			<view class="box">
				<text class="text-infor">普通话二乙</text>
				<navigator url="" class="btn4"> > </navigator>
			</view>
		</view>
		
		<view class="basic-infor">
			<view class="title">
				<view class="title-view"></view>
				<text class="title-text">实践经历</text>
				<navigator url="" class="btn2">添加</navigator>
			</view>
			
			<view class="box">
				<text class="text-infor">教育实习</text>
				<navigator url="" class="btn4"> > </navigator>
			</view>
		</view>
		
		<view class="basic-infor">
			<view class="title">
				<view class="title-view"></view>
				<text class="title-text">挂科经历</text>
			</view>
			
			<view class="box">
				<text class="text-infor">高等数学</text>
				<navigator url="" class="btn4"> > </navigator>
			</view>
		</view>
		
		<view class="basic-infor">
			<view class="title">
				<view class="title-view"></view>
				<text class="title-text">所受惩罚</text>
			</view>
		</view>
		
		<navigator type="primary" class="btn3">保存更改</navigator>
		
		<navigator type="primary" class="btn3">解除绑定</navigator>
		
		<navigator type="primary" class="btn3">退出登录</navigator>
		
		<view style="margin-top: 20rpx; width: 100%; height: 100rpx; background-color: #0FAEFF;"></view>
		
	</view>

</template>
	
<script>
</script>

<style>
	.container{
		width: 100%;
	    display: flex;
	    flex-direction:column;
	    align-items: center;
	    background-color:#e8e6f3;
	}
	.basic-infor {
		margin-top: 20rpx;
		width: 100%;
		height: auto;
		background-color:#ffffff;
	}
	
	.title {
		width: 100%;
		height: 70rpx;
	}
	
	.title-view {
		float: left;
		width: 10rpx;
		height: 70rpx;
		background-color: #0faeff;
	}
	
	.title-text {
		float: left;
		margin-left: 5%;
		line-height: 70rpx;
	}
	
	.box {
		width: 90%;
		height: 80rpx;
		border-bottom: 1rpx solid #555555;
		border-top: 1rpx solid #555555;
		margin-left: auto;
		margin-right: auto;
	}
	
	.text-title {
		float: left;
		width: 100px;
		line-height: 80rpx;
		font-size: 35rpx;
		font-weight: 500;
	}
	
	.text-infor {
		float: left;
		height: 80rpx;
		font-size: 30rpx;
		line-height: 80rpx;
	}
	
	.btn1 {
		margin-top: 10rpx;
		float: left;
		width: 200rpx;
		height: 60rpx; 
		background-color: #0faeff;
		color: #ffffff;
		font-size: 30rpx;
		align-content: center;
		line-height: 60rpx;
		text-align: center;
	}
	
	.btn2 {
		float: right;
		margin-right: 5%;
		margin-top: 5rpx;
		width: 120rpx;
		height: 60rpx; 
		background-color: #0faeff;
		color: #ffffff;
		font-size: 30rpx;
		line-height: 60rpx;
		text-align: center;
	}
	
	.btn3 {
		margin-top: 20rpx;
		width: 100%;
		height: 80rpx; 
		background-color: #0faeff;
		color: #ffffff;
		font-size: 35rpx;
		line-height: 80rpx;
		text-align: center;
	}
	
	.btn4 {
		float: right;
		margin-top: 10rpx;
		width: 120rpx;
		height: 60rpx; 
		background-color: #ffffff;
		font-size: 30rpx;
		line-height: 60rpx;
		text-align: center;
	}
	
	button::after{ border: none; }
		
</style>
