## 简介

欢迎使用 [腾讯云游戏多媒体引擎 SDK](https://cloud.tencent.com/product/tmg?idx=1) 。为方便开发者接入腾讯云游戏多媒体引擎产品，这里向您介绍适用于游戏多媒体引擎 SDK 的接入指引。

使用 GME 有以下五个步骤：
1. [在腾讯云后台新建 GME 服务](#.E6.96.B0.E5.BB.BA.E6.9C.8D.E5.8A.A1);
2. [下载对应版本的客户端 SDK](#.E4.B8.8B.E8.BD.BD-sdk);
3. [参照接入 API 文档， 将 SDK 移植到工程](#.E7.9B.B8.E5.85.B3-sdk-.E6.8A.80.E6.9C.AF.E6.96.87.E6.A1.A3);
4. [查看日常运营后台统计](#.E6.8E.A7.E5.88.B6.E5.8F.B0.E7.94.A8.E9.87.8F.E7.BB.9F.E8.AE.A1);
5. [接入过程中特殊问题自主排除与反馈](#.E7.89.B9.E6.AE.8A.E9.97.AE.E9.A2.98.E5.A4.84.E7.90.86);


## 新建服务
#### 1.登录成功后，单击【新建应用】
![](https://main.qcloudimg.com/raw/a4b3dbd8aefd9dd032f8c3ce4154b227.png)

#### 2.填入相应的信息。  
填写该页面所需信息，按照需要选择所需的服务。 
- 音质不同计费方式也不同，计费详情请参考 [产品价格](https://cloud.tencent.com/document/product/607/17808) 及咨询相关腾讯云商务工作人员。设置完成可再修改。

- 如果是游戏类应用，需选择相应的平台引擎。

- 语音消息及转文本服务设置完成可再修改。

![](https://main.qcloudimg.com/raw/bafdd3250004a5d69322beab1d6c25c7.png)


#### 3.创建应用成功后，应用管理列表就有刚刚创建的应用。
列表中的 AppID 在接入 SDK 进行开发过程中会作为参数使用。

![](https://main.qcloudimg.com/raw/9e78b27c75b9bfcd2ce02ae1d02b7046.png)


#### 4.应用管理列表中，在相应的应用那一行，单击【设置】按钮，进入应用设置。
![](https://main.qcloudimg.com/raw/ac27c53e9a07fa819344f668978fe019.png)

应用信息模块，单击【修改】后可对相应信息进行修改。

#### 5.鉴权信息模块，可获取应用相应的鉴权。
![](https://main.qcloudimg.com/raw/76b5038763d2aded0be39b0d1bc27efa.png)

 - 此模块中的权限密钥会作为参数使用到 SDK 接入过程中。 
 - 页面修改密钥后，15 分钟 ~ 1 小时内生效，不建议频繁更换。
 - 只有创建游戏的账号、主账号、全局协作者可以操作【重置密钥】。
 -  **鉴权详细使用请参考 [游戏多媒体引擎密钥说明文档](https://cloud.tencent.com/document/product/607/12218)**。
 
 ![](https://main.qcloudimg.com/raw/df3f92e2eb50aea9d8dde32f252045f6.png)




#### 6.业务及服务的开启关闭

在这里可以对业务及服务进行开启或者关闭。
![](https://main.qcloudimg.com/raw/a5711820b59c6d4047565562094d1595.png)

![](https://main.qcloudimg.com/raw/ec0f00f1afc229b6db5676772c53edad.png)

## 下载 SDK 
#### 1.下载地址
请在 [SDK 下载指引](https://cloud.tencent.com/document/product/607/18521) 下载相关 Demo 及 SDK。

#### 2.接入准备
接入 SDK 需要使用腾讯云提供的 appid 及相关权限密钥。即应用管理列表中的 AppID 及 应用设置中的鉴权信息模块。

更多平台相关配置请参考各平台工程配置文档。

#### 3.官方 Demo 使用需知

Demo 中带有腾讯云测试账号，可进行功能体验，如需更换个人及公司测试账号，需要在 Demo 中在相应界面将腾讯云测试账号 AppID 更换为开发者在控制台获取的 AppID，并需要在 AVChatViewController-GetAuthBuffer 函数中修改实时语音的权限密钥。

## 控制台用量统计
[运营指引文档](https://cloud.tencent.com/document/product/607/17448)


## 特殊问题处理
[常见问题文档](https://cloud.tencent.com/document/product/607/17359)     [错误码文档](https://cloud.tencent.com/document/product/607/15173)
