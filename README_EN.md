# Duix - Silicon-Based Digital Human SDK 🌐🤖   

<div style="width: 100%; text-align: center;">
  <img src="res/logo_en.jpg" style="width: 100%; height: auto;"/>
</div>



## Introduction

DUIX, short for “Dialogue User Interface System”, is a digital human intelligent interaction platform created by Silicon Intelligence. The digital human SDK has been open-sourced, allowing developers to deploy on Android and iOS devices with one click, providing users with immediate virtual human interaction experience. The built-in two avatars allow users to easily get started and directly experience the charm of digital humans.

The SDK not only provides intuitive effect demonstration but also supports users for secondary development. Developers can easily develop customized virtual human applications based on the provided open documentation. The Silicon-based Digital Human SDK is completely open-source, with both the underlying inference engine and the upper-level commercial application logic open to source code. Developers can delve into its working principle and further optimize and innovate.<br><br>

## Applicable Scenarios

- Low deployment cost: No need for customers to provide technical teams for cooperation, supports low-cost rapid deployment on various terminals and large screens.
- Low network dependence: Suitable for virtual assistant self-service in scenarios such as subways, banks, and government affairs.
- Diverse functions: Can meet the diverse needs of video, media, customer service, finance, radio, and television in multiple industries according to customer requirements.<br><br>

## Core Functions

- Provides customized AI anchors and intelligent customer service for multi-scene image rental.
- Exclusive image customization: Supports the customization of exclusive virtual assistant images, with options for low-cost or deep image generation.
- Broadcast content customization: Supports the customization of exclusive broadcast content, applied in training, broadcasting, and other scenarios.
- Real-time interactive Q&A: Supports real-time dialogue, can also customize exclusive Q&A databases to meet consulting inquiries, voice chat, virtual companionship, and vertical scene customer service Q&A.<br><br>

## Source Code Directory Description

```
duix-android: android demo       
duix-ios: ios demo 
```

<br>

## Open Documentation Entry

For android, refer to [README.md](https://github.com/GuijiAI/duix.ai/blob/main/duix-android/dh_aigc_android/README.md)

For ios, refer to [GJLocalDigitalSDK.md](https://github.com/GuijiAI/duix.ai/blob/main/duix-ios/GJLocalDigitalDemo/GJLocalDigitalSDK.md)<br><br>

## Digital Human Avatar Display

<p align="center">
  <img src="res/女.jpg" width=200/>
  <img src="res/男.jpg" width=200/>
</p>

The two built-in models and AI model packages can be downloaded through the public network address. [Female link address](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716034688/bendi1_0329.zip) [Male link address](https://digital-public.obs.cn-east-3.myhuaweicloud.com/duix/digital/model/1716034688/bendi3_20240518.zip)<br><br>

## Version Record

- **3.0.4**: Fixed an issue where some devices’ default gl float low precision caused the avatar to not display properly.
- **3.0.3**: Optimized local rendering<br><br>

## Acknowledgments

- We have drawn on [wenet](https://github.com/wenet-e2e/wenet) for audio features.<br><br>

## Contact Us

```
maoliyan@guiji.ai
```