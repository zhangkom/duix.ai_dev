# Duix - 硅基数字人SDK 🌐🤖 [[English]](./README_EN.md)   

<div style="width: 100%; text-align: center;">
  <img src="res/logo.jpg" style="width: 100%; height: auto;"/>
</div>

## 简介 Introduction   
DUIX全称为"Dialogue User Interface System"，是硅基智能打造的数字人智能交互平台，已将硅基数字人SDK进行开源，开发者能够在Android和iOS等设备上一键部署，为用户提供即时的虚拟人互动体验。内置的两个形象使得用户可以轻松上手，直接体验数字人的魅力。
该SDK不仅提供了直观的效果展示，还支持用户进行二次开发。可以根据提供的开放文档轻松开发出定制化的虚拟人应用。硅基数字人SDK是完全开源的，底层推理引擎以及上层的商业化应用逻辑都开放了源代码。开发者可以深入了解其工作原理，并进行进一步的优化和创新。  <br><br> 

### 适用场景 Applicable Scenarios
- 部署成本低: 无需客户提供技术团队进行配合，支持低成本快速部署在多种终端及大屏。
- 网络依赖小: 适合地铁、银行、政务等多种场景的虚拟助理自助服务。
- 功能多样化: 可根据客户需求满足视频、媒体、客服、金融、广电等多个行业的多样化需求。<br><br>

### 核心功能 Core Features
- 部署成本低: 无需客户提供技术团队进行配合，支持低成本快速部署在多种终端及大屏。
- 网络依赖小: 适合地铁、银行、政务等多种场景的虚拟助理自助服务。
- 功能多样化: 可根据客户需求满足视频、媒体、客服、金融、广电等多个行业的多样化需求。<br><br>

### 源码目录说明 Directory Structure  
```
duix-android: android demo       
duix-ios: ios demo  
```     

### 开放文档入口 Open Documentation Portal

android参考 [简体中文](./duix-android/dh_aigc_android/README.md) <br>
ios参考 [简体中文](./duix-ios/GJLocalDigitalDemo/GJLocalDigitalSDK.md)  <br><br>

### 数字人形象展示 Digital Avatar Showcase
<p align="center">
  <img src="res/女.jpg" width=200/>
  <img src="res/男.jpg" width=200/>
</p>

内置的公共模特，模板和AI模型包可以通过公网地址下载。    
[女](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716034688/bendi1_0329.zip)
[男](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716034688/bendi3_20240518.zip)<br><br>

### 更多本地模型下载 More Local Model Downloads

我们提供了更多的数字人模型，可供下载和使用。以下是当前可用的模型列表：我们将不定期更新本地模型包，以便您可以下载和使用最新的模型。以下是当前可用的本地模型包列表：

| **苏菲** [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716888936579/sufei_20240528.zip) | **慕容晓** [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716888801385/murongxiao_20240528.zip) | **冷焱** [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716888754222/lengyan_20240528.zip) | **Amelia** [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716888645375/amelia_20240528.zip) | **艾瑞克** [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716888516200/airuike_20240528.zip) | **子轩** [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716890628522/zixuan_20240529.zip) |
|---|---|---|---|---|---|
| **赵雅 [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716891345706/zhaoya_20240529.zip)** | **忆瑶 [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716891579303/yiyao_20240529.zip)** | **心妍 [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716891699212/xinyan_20240529.zip)** | **晓萱 [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716891894722/xiaoxuan_20240529.zip)** | **思瑶 [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716892228368/siyao_20240529.zip)** | **诗雅 [下载](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716892436557/shiya_20240529.zip)** |


请根据您的需求下载相应的模型文件。我们建议您在下载后仔细阅读随附的文档，以确保正确安装和使用模型。<br><br>

### 版本记录 Changelog

- **3.0.4**: 修复部分设备gl默认float低精度导致无法正常显示形象问题。
- **3.0.3**: 优化本地渲染<br><br>

### 致谢 Acknowledgments
-音频特征我们借鉴了 [wenet](https://github.com/wenet-e2e/wenet)  <br><br>

### 联系我们 contact us
    maoliyan@guiji.ai
