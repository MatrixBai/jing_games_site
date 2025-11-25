---
date: 2025-11-17
title: 《异路浮生》角色设计
authors:
- loomi
---

关于角色的表达设计，是一个游戏视觉里面最贴近玩家感受的一个部分。在推进角色视觉设计时，我把重心放在了“身体比例”这个最基础却也最决定性的变量上。比例一旦定型，后续的服装、表情、动画乃至整个美术风格都会被彻底牵引。<!-- more -->

# 第一阶段：五头身写实比例的尝试
最开始我用了比较常规的五头身比例，四肢也接近真实人体。草稿阶段就发现问题：

在这个比例下，服装配件的细节必须非常精致，否则就会显得“小而碎”。
两层服装（内层基础服饰 + 外层功能装备）的层次感很难拉开，视觉空间被严重压缩。
这套方案虽然“看得懂”，但完全没有给我们想要的那种“一眼就能记住”的独特气质。

![](http://jing.games/assets/blog/devlog-2025-11-25/4_types.png)

# Phase 2: Extremely Elongated Limbs ("Comedy" Version)

![](http://jing.games/assets/blog/devlog-2025-11-25/thin_leg.png)

后来我尝试把四肢拉到极致细长，只突出身体的部分。 这个版本一下子就有了个性：

- 视觉上非常幽默，动作幅度一大就自带喜感；
- 快速做了几段小动画，角色走路、挥手都可爱得要命。

![](http://jing.games/assets/blog/devlog-2025-11-25/complain.gif)

但问题很快暴露：

- 服装被极度简化后，很多原本想通过服饰传达的文化信息和功能信息彻底丢失；
- 细长的四肢让挂件、护甲、工具的视觉呈现变得异常困难，几乎没法“穿”出层次；
- 对后续可能的游戏机制（比如装备系统、职业差异化）造成了致命限制。

可爱归可爱，却牺牲了太多我们真正需要表达的东西，这个方向只能忍痛放弃。

# 第三阶段：乐高式“大腹便便玩偶比例”的最终落地

![](http://jing.games/assets/blog/devlog-2025-11-25/lego_body.png)

在反复试错后，我把目光转向了乐高小人那种“粗短四肢 + 大肚子”的比例，刻意做成一种“布娃娃”质感。 这个比例带来的变化是颠覆性的：

- 身体变得紧凑，服装、装备、挂件终于有了足够的“展示面积”；
- 两层服装的层次感立刻变得清晰，外层披风、护甲、工具腰带都能一目了然；
- 四个文化来源的差异化终于有了发挥空间：原住民的编织披肩、殖民者后代的旧时代皮衣、公司员工的制式防护服……都能在同一个比例下共存，又互不打架。

当然，一开是参考的美式卡通画法，但似乎有些“缺少个性”。 为了解决这个问题，我去罗曼式壁画里找了面部表情参考：

- 压扁的五官、极简的线条；
- 所有情绪几乎完全靠眼睛承载（睁大、眯起、半闭、死鱼眼……）避开的美式圆眼风格。

至此，角色视觉雏形彻底定型。

![](http://jing.games/assets/blog/devlog-2025-11-25/romansque.jpg)

# 生产阶段：一套可按需求生成的角色创建流程
在确定比例的同时，我写了一套角色生成逻辑： 根据当前游戏世界的地貌 → 角色种族/文化来源（上述四类） → 触发的人物类型 → 自动组合出对应的服装层级、服装配件等细节。

为了验证这套流程的可玩性，我昨晚用《Firefly》里的两个角色做了第一批测试：

- Kaylee：原住民混血 + 殖民者后代基因 → 热情的橙红配色 + 大量手工改装零件
- Wash：公司前员工 → 依旧残留制式衬衫，但外面套满了自制飞行员夹克和夏威夷花衬衫的混搭

效果意外地好，两种完全不同的气质在同一套比例系统里都站得住脚。
目前这就是我们角色设计的最终方向： **一个看上去像乐高小人、却能承载复杂文化符号和服装层次的“玩偶化”风格。

![](http://jing.games/assets/blog/devlog-2025-11-25/keylee_and_wash.png)

# Current Final Direction

A plush-toy-like, Lego-minifig-inspired proportion that looks simple and approachable at first glance, but has enough canvas and structure to carry rich cultural details, deep clothing layering, and strong visual identity.

It’s cute without being childish.
It’s stylized without being limiting.
It’s finally ours.

That’s where we are now. More updates as we start animating and putting them into the world. Thanks for reading.