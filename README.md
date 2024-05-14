# yzmeeting-sdk-android

# 概述

随着云视频会议的越来越普及，企业沟通中随时拉会的场景越来越多，云舟会议赋能企业内部各种应用随时拉起视频通话或者视频会议，让您的应用轻松插上即时通话和会议的翅膀。

红鲸会议SDK是自带UI功能的音视频通话和音视频会议SDK，具有如下特点：

集成简单：用户只需简单几行代码就可以拥有私有化部署的音视频通话和音视频会议的功能；
功能全面：具备了会议创建，会议加入，呼叫，被叫，共享桌面，录制，会控等音视频会议的常用功能；
平台能力稳定：音视频会议基于稳定的RTC平台构建，具备网络切换，断网重连，弱网重传等功能。支持H264和AV1等先进的编码方式，保证了低码率和画质。
私有化部署：满足企业安全需求，方便企业资产结算。


# 集成必读

在集成SDK之前，需要做如下提前准备：

需要部署好音视频服务端，确认好会议服务器的地址和端口;
集成本SDK的APP需要有用户体系，调用SDK时需要指定用户名，用户ID，用户头像地址这些用户信息；
集成会议功能时，集成本SDK的APP需要提供创建会议或者加入会议的入口交互能力，如果是加入会议则需要提供会议号;
集成通话功能时，集成本SDK的APP的系统需要具备推送机制，APP需要具备呼叫入口交互能力，接收呼叫推送后调起本SDK的被叫接口。

# 快速开始

请参考yzmeeting-example-android的README,进行sdk的集成 https://github.com/yunzhoucomm/yzmeeting-example-android/blob/main/README.md
