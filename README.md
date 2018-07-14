﻿



# 微信好友分析

## 功能说明：用作者的微信号进行示范
#### 1：统计好友的性别
![python](https://github.com/isleak/wechat-friends/blob/master/source/1.png)
#### 2：统计好友的地域分布，并且可视化在地图上展示
![python](https://github.com/isleak/wechat-friends/blob/master/source/2.png)

![python](https://github.com/isleak/wechat-friends/blob/master/source/3.png)
#### 3：将好友的昵称做成词云
因为这个信息比较私人，这里就不展示
#### 4：统计好友个性签名中的高频词汇
![python](https://github.com/isleak/wechat-friends/blob/master/source/4.png)
#### 5：将所有好友的头像合并成一张大图
![python](https://github.com/isleak/wechat-friends/blob/master/source/5.png)
#### 6：微信自动发送与回复消息
<img height="500" align="center" src="https://github.com/isleak/wechat-friends/blob/master/source/6.jpg" alt="">

## 依赖
本程序使用python3，请在python3环境下运行
#### Python 3
- PIL: pip3 install pillow
- pyecharts：pip3 install pyecharts
- pip3 install itchat

## 运行
#### 获取用户信息
python3 get_user_info.py
执行后会在data目录下生成friends.json
会在images目录下存放所有好友的头像
#### 统计用户信息
python3 analyse.py
会在analyse文件夹下生产合成后的图片以及可视化的文件

#
####7：遗憾：还没有把个性签名的表情给整理好。
