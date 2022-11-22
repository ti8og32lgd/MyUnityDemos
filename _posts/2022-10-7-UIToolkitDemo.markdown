---
layout: default
title: In Game UIToolkit Demo
intro: 使用UIToolkit制作的游戏内UI实例
---

<div class="top">
      <div class="gameBox">
          <iframe id="game" width="1920" height="1080" src="https://donald-trump.cyou/games/UiToolkitDemo/"></iframe>
      </div>
</div>
# 简介
使用UIToolkit实现实例游戏内菜单UI
- 绑定StandaloneInputModule，可以支持键鼠/手柄控制（未实现）
- 每一个标签页面由代码动态生成，支持扩展
![UiToolkitDemoIntro1](assets/images/UItoolkitIntro1.jpg)

<style>
        .top {
            height: 555px;
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
