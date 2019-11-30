---
layout: post
title: 角色创建-角色属性
date: 2019-11-30 23:59:59 +0800
category: 角色创建
tags: [入门,属性]
keywords: 角色属性
translator: 深白senba
description: 游戏中最重要也是最基础的机制，关乎角色的一举一动（。
---

# 属性

角色总共有四个属性可供调整。每个属性都是独立的，调整属性会影响角色的各个方面，比如最大生命、近战伤害、最大负重量等。

每个属性的最小值均为4，当属性值增加到超过14时，每增加一点需要消耗2点属性点数。属性值达到14是一个非常高的数值，基本上是人类能够达到的极限。属性值当然可以设定得更高，但是玩家应当意识到这样的数值是高得异常的（我不做人类啦！JOJO！！）。

**各项属性为默认值8时的角色数值如下所示:**

|                            力量8                             |                            敏捷8                             |                         智力8                          |     感知8     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------: | :-----------: |
| 基础生命上限： 84<br />最大负重： 99.2磅（45千克）<br />近战伤害加成： 6 | 近战命中加成： +2.00<br />目标每级闪避的投掷惩罚： +25<br />远程惩罚： -6 | 阅读耗时： 100%<br />技能遗忘： 50%<br />制作加成： 8% | 瞄准惩罚： 14 |

**请注意以下数值为属性值从8开始增加时的变化幅度，低于8点属性值时的增减情况可能有所不同。**

|                             力量                             |                             敏捷                             |                             智力                             |                             感知                             |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 每增加1点力量：<br />增加基础生命上限 3<br />增加最大负重 8.8磅（4千克）<br />增加近战伤害加成 0.8<br />[力量值影响详情](http://dev.narc.ro/cataclysm/doxygen/Effects_Stat_Strength.html) | 每增加1点敏捷：<br />增加近战命中加成 0.25<br />减少目标每级闪避的<br />投掷惩罚 2<br />减少远程惩罚 1<br />[敏捷值影响详情](http://dev.narc.ro/cataclysm/doxygen/Effects_Stat_Dexterity.html) | 每增加1点智力：<br />减少阅读耗时 5%<br />减少技能遗忘 3.5%<br />增加制作加成 1%<br />[智力值影响详情](http://dev.narc.ro/cataclysm/doxygen/Effects_Stat_Intelligence.html) | 每增加1点感知：<br />减少瞄准惩罚1<br />感知还影响侦查陷阱和<br />其他事物<br />感知过低将影响视野范围<br />[感知值影响详情](http://dev.narc.ro/cataclysm/doxygen/Effects_Stat_Perception.html) |

## 生命值 (HP)

角色的力量值和玩家所选择的增加/降低生命值的特性决定了角色每个身体部位拥有的生命值上限。默认的8点力量属性值对应每个身体部位拥有84点基础生命值上限。

每个身体部位所拥有的生命值通常是隐藏的，除非你具有“ [自我认知](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Self-aware) ”特性。如果躯干或头部的生命值低于1，角色会 [死亡](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Fun)。如果其他部位（四肢）的生命值低于0，它会[断掉](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Broken_limb)。断掉的话当然就很难[治疗](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Broken_limb#How_to_fix_it)啦。

损失的生命值会随着时间慢慢恢复，也可以通过使用医疗物品快速恢复，[睡眠](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Sleep)期间生命值的恢复速度会加快。如果角色不处于[健康](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Hidden_stats#Health) 状态，恢复的速度会下降。

如果身体部位名称的字体变为<font color='#ff0000'>红色</font>，说明这个身体部位在出血，该部位的生命值会随时间下降。

特别需要注意的是身体部位不光会被破坏，还可能被[感染](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Infection)。感染会用另一种方式要了你的小命（请务必参阅[感染](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Infection)）。感染可能来自咬伤，此时身体部位字体会变为<font color='#0000ff'>蓝色</font>。未及时处理的咬伤很可能会引发感染，此时身体部位名称字体变为<font color='#00d000'>绿色</font>。

## 耐力值

耐力值影响角色的爆发力，更多信息请参阅 [耐力值](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Stamina) 页面。

## 隐藏参数

还有各种各样的隐藏参数不受角色建立过程的影响，但是这些参数会在游戏中展现它们的影响。

更多信息请参阅 [隐藏参数](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Hidden_stats) 页面。
