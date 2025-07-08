<p align="center">
  <img src="https://raw.githubusercontent.com/gzzzzzz-247/Cobblemon-Omega-Showdown/refs/heads/main/bg2.png" />
</p>

# Cobblemon Omega Showdown

<p align="center">
  <img src="https://raw.githubusercontent.com/gzzzzzz-247/Cobblemon-Omega-Showdown/refs/heads/main/icon.png" />
</p>
<p align="center">
   Owener:Gzzzzzz247
</p>
增强原版Cobblemon玩法内容，基于宝可梦官方内容而制作
添加来自中州地区(原型为国内)的方可梦 此世代命名为 Ω

# 预实现项目 / 画饼（

<p align="center">
  <img src="https://raw.githubusercontent.com/gzzzzzz-247/Cobblemon-Omega-Showdown/refs/heads/main/title.png" height="85"/>
</p>

* 新进化道具 (α β γ Ω
* 农业/挖矿获取主要交易货币
* 特殊召唤以召唤神兽/BOSS
* 爬塔副本(1/4) 已完成副本基础
* 全民商店系统，仿造PokeMMO 进行制作
* 挑战式获取宝可梦，掉落宝可梦蛋
* 自创世代地区，丰富生态


# 特色 / Features

<p align="center">
  <img src="https://raw.githubusercontent.com/gzzzzzz-247/Cobblemon-Omega-Showdown/refs/heads/main/title.png" height="85"/>
</p>

## 机制 / System

### 初始 IVS
为你的默认御三家宝可梦设置固定的 IVS 不再是随机数值，为联机/单机有着更好的公平体验。

### 限制捕捉宝可梦最高等级
仿止玩家捕捉到比当前水平高出太多的口袋妖怪。任何对比玩家当前队伍中最高等级的口袋妖怪高出 X 级的口袋妖怪的捕捉尝试都不会成功。
如果玩家处于创造状态、正在使用 大师球 或目标 Pokemon 闪亮，则等级上限将被忽略！

### 传说地域 (未完成)
现在开始每个神兽（原作具有祭坛/召唤的神兽或者幻兽）具有独特的刷新机制,通过钓鱼/寻宝/开战利品/击败BOSS掉落通往地区的船票，你要通过祭坛给予道具或者消耗船票等待特殊时间进行召唤，而不是像随时随地刷新的宝可梦一样

## 物品类 / Items

### 银色瓶盖
一个不知道从哪来的瓶盖，闪耀着银色的光芒。在钓鱼时，有 1/10 的机会也能获得一个瓶盖。单独使用这个瓶盖并没有太大用处，
但如果将它与正确类型的果实一起制作，
你可以根据下面的图表为瓶盖赋予一个属性。
当使用带有属性的瓶盖在训练师的宝可梦身上时，
它将把该属性的IV提升到最大（如果可能的话）。
你可以在宝可梦列表中检查你的宝可梦的IV.

| 物品颜色   | 统计 |
|--------|----|
| Black  | 攻击 |
| Yellow | 防御 |
| Red    | 血量 |
| Blue   | 特攻 |
| Green  | 特防 |
| Pink   | 速度 |

### 金色瓶盖
一个美丽的瓶盖，散发着金色的光泽。
当你钓鱼时，有 1/100 的机会还会获取一个金瓶盖。
当将其用于训练师的宝可梦时，
它会将该宝可梦的所有个体值提升到最大（如果可能的话）。

### 盗版瓶盖
当地黑心工厂制作出来的瓶盖，暗淡无色并散发出刺鼻的味道。在钓鱼时，有 1/80 的机会也能获得一个瓶盖。单独使用这个瓶盖并没有太大用处，
但如果将它与正确类型的果实一起制作，
你可以根据下面的图表为瓶盖赋予一个属性。
当使用带有属性的瓶盖在训练师的宝可梦身上时，
它将把该属性的IV降低为0（如果可能的话）。
你可以在宝可梦列表中检查你的宝可梦的IV.

| 物品颜色   | 统计 |
|--------|----|
| Black  | 攻击 |
| Yellow | 防御 |
| Red    | 血量 |
| Blue   | 特攻 |
| Green  | 特防 |
| Pink   | 速度 |

### 根茎
在草丛中破坏时发现的常见根茎。
在破坏草时，
有1/10的几率获得干根。
对宝可梦使用时，如果可能，
将重置该宝可梦所有属性的努力值。
提供与一根木棍相同的燃料量。

### 洛托姆手机
可以连接到超智能计算机的手机，里面寄宿着洛托姆，(未完成，bug较多)
进行治疗，打开PC，挑战道馆增加段位，传送竞技场，参与每日活动获得奖励，商店系统

<p align="center">
  <img src="https://raw.githubusercontent.com/gzzzzzz-247/Cobblemon-Omega-Showdown/refs/heads/main/p1.png" height="185"/>
</p>

## Dependencies

Cobblemon [Modrinth](https://modrinth.com/mod/cobblemon) / [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cobblemon)

Fabric Language Kotlin [Modrinth](https://modrinth.com/mod/fabric-language-kotlin) / [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin)
