---
layout: default
title: Space Fight Demo 太空大战Demo
intro: 具有武器系统和技能系统的小游戏
---
### {{page.title}}
> {{page.intro}}

<div class="top">
      <div class="gameBox">
          <iframe id="game" width="1080" height="1920" src="https://donald-trump.cyou/games/SpaceFightDemo/"></iframe>
      </div>
</div>
# 简介
### 游戏操作
  1. 拖动屏幕控制飞船跟随移动，同时自动开火射击敌人。
  2. 拾取随机掉落的道具，获取【提升生命值/提升伤害/提升速度/增加武器】的效果
  3.  击杀完所有敌人后，通过关卡，到达补给站，选择一项技能【护盾/受伤时间减缓/生命恢复/子弹自动跟踪/僚机】


### 特点：
  1. 武器系统：可变武器数量、不同武器种类
  2. 道具系统：不同效果、增益数值可配置
  3. 技能系统：不同技能种类
  4. 敌人AI：由（模型 移动方式 射击方式）组装生成
  5. 扩展性：所有模块支持扩展
  6. 数值：所有数值均可配置，使用ScriptableObject存储
  7. 仿《守望先锋》血条动画
  8. 使用InputSystem, 适配多种类型输入（键鼠、手柄）



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
            scale: 30%;
            border: 1px solid #73AD21;
            padding: 10px;
        }
    </style>
