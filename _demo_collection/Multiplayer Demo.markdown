---
layout: default
title: 多人网络对战坦克游戏Demo
intro: 多人网络对战坦克游戏的客户端、服务器（.net)
---

### {{page.title}}
> {{page.intro}}

<video src="https://user-images.githubusercontent.com/17761040/207265406-dab2eb4e-04c8-47ef-8977-74f68b6b66f0.mp4" data-canonical-src="https://user-images.githubusercontent.com/17761040/207265406-dab2eb4e-04c8-47ef-8977-74f68b6b66f0.mp4" controls="controls" muted="muted" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;"></video>
>  follow:
  [https://github.com/luopeiyu/unity_net_book](https://github.com/luopeiyu/unity_net_book)

# 简介
多人网络对战坦克游戏的客户端、服务器（.net)。
- 基于tcp的客户端-服务器应用层通信协议
- 网络框架使用了select多路复用/json序列化/mysql数据层，具有底层与业务逻辑分离、事件注册/处理、处理粘包分包、自动扩充缓冲区等特性
- 分为3个模块：登录注册模块、房间大厅模块、战斗模块
- 战斗模块使用预测算法帧同步




<style>
        .top {
            height: 700px;
        }


        .gameBox {
            transform-origin: left top;
            top: 8px;
            left: 10px;
            /*widows: %;*/
            width: fit-content;
            height: fit-content;
            /*height: 60%;*/
            scale: 50%;
            border: 1px solid #73AD21;
            padding: 10px;
        }
    </style>
