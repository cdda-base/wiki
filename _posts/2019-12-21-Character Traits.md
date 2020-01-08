---
layout: post
title: 角色-特性
date: 2020-01-06 21:00:00
category: 角色
tags: [入门,特性,突变]
keywords: 特性
translator: 深白senba
description: “--你，天生如此。” 也可以叫作天赋，可以自定义特性来让你的角色惟妙惟肖·栩栩如生·生龙活虎·以一敌四·废材如屎。
---



# 特性

特性是在角色建立时可以选择的一种人物特征。在游戏中它们不仅和[突变](https://cddabase.site/wiki/posts/%E8%A7%92%E8%89%B2%E7%89%B9%E6%80%A7/%E7%AA%81%E5%8F%98/index.html)一样发挥作用，还在“角色状态”界面中与突变混在一起。在游戏代码中，特性实际上就是一种突变，不过它们还会带有一个标签来表明它们是角色建立时选择的“特性”。

在特性页面，特性被分为正面特性和负面特性，选择正面特性会消耗点数，选择负面特性则获得点数，越强的特性点数越高。可以选择的正/负面特性最大点数均为12点。

有些初始[职业](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Professions)带有这些职业在灾变前拥有的“职业特性”，能够让你使用一些在其他条件下无法使用的装备和场所。

## 特性和突变的区别

- 特性只能在角色建立时选择，在开始游戏后无法获取特性，但是可以获得具有相同效果的突变。

- 特性极难去除，只有在[界限突破](https://cddabase.site/wiki/posts/%E8%A7%92%E8%89%B2%E7%89%B9%E6%80%A7/%E7%AA%81%E5%8F%98/index.html)等少数的特殊条件下才会发生改变。

- 有些特性在游戏开始之后就再也无法获取了，比如说各种[职业](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Professions)特性。

- 来一杯神清气爽的[净化剂](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Purifier)能去除游戏过程中获得的突变，但是却能帮你找回失去的初始特性。

p.s.：在0.C版本（旧版本）中，一些[初始场景](https://cddabase.site/wiki/posts/%E8%A7%92%E8%89%B2%E5%88%9B%E5%BB%BA/Character-Scenarios/index.html)也提供了不同的初始特性。比如“挑战-实验室”场景中你可以选择获得几种初始突变，比如，鳃。因为你的角色在大灾变之前就因试验突变了，或者你本身就是个什么东西的……克隆体，这些初始选择的突变带有标签，被游戏认定为“特性”，因而无法被净化，也不用于计算界限突破。

## 改变初始特性

正常情况下在游戏中无法抹去初始特性的标签，净化剂会据此试图帮你找回失去的特性。如果你真的想要修改初始特性，可以试试[调试菜单](http://cddawiki.chezzo.com/cdda_wiki/index.php?title=Debug_Menu)里的突变选项。