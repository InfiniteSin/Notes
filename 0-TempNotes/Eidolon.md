---
title: "Eidolon: Repraised"
aliases: 幻梦
tags: 我的世界/模组
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm:ss") %>
modified: <% tp.file.last_modified_date("YYYY-MM-DD HH:mm:ss") %>
---
# 基础流程
1. 合成模组说明书 "秘仪教典(Ars Ecclesia)"
2. 解锁两个基础符文
	- 邪恶符文(Wicked Sign)：将秘仪教典扔给女巫阅读并返回
	- 神圣符文(Sacred Sign)：将秘仪教典扔给主教(村民职业)阅读并返回
3. 合成稻草塑像(Straw Effigy)和木制祭坛(Wooden Alter)，将稻草塑像放于祭坛上
	- 极限配置：灯笼 + 蜡烛 + 凋零骷髅头 + 凋零玫瑰 + 高脚杯/香炉(11威能 + 6容量)
4. 每天(间隔 21000 ticks / 约 17.5 min)分别进行1次暗黑颂词和光明祷词
	- 暗黑颂词：邪恶符文 - 邪恶符文 - 邪恶符文
	- 光明祷词：神圣符文 - 神圣符文 - 神圣符文
5. 消耗资源做出以下物品
	- 白镴锭(Pewter Ingot)
	- 白镴嵌材(Pewter Inlay)：用于后续通过暗黑之触(Touch of Darkness)转化亵渎象征符(Unholy Symbol)
	- 秘金锭(Arcane Gold Ingot)
	- 金嵌材(Gold Inlay)：用于后续通过光明之触(Touch of Light)转化圣洁象征符(Holy Symbol)
	- 高脚杯(Goblet)
	- 香炉(Censer)
	- 仪式火盆(Brazier)
	- 石之手(Stone Hand)
	- 暗蚀焦点(Necrotic Focus)
	- 魔力工作台(Magic Workbench)
	- 坩埚(Crucible)
6. 黑暗/光明阵营声名达到 3 时(提示需要新的知识)获得血液符文(Blood Sign)和火焰符文(Flame Sign)，同时解锁新的颂歌/供奉，通过新颂歌/供奉解锁声名上限至 15，并获得魂魄符文(Soul Sign)
	- 黑暗阵营解锁动物牲祭(Sacrifice Animal)：杀死一只动物使高脚杯装满动物血液，念出颂词：邪恶符文 - 血液符文 - 邪恶符文
	- 光明阵营解锁香炉祭献(Censer Offer) ：合成祭献熏香(Offering Incense)并右键放入香炉中，主手打火石点燃香炉
7. 继续每天分别进行颂歌与供奉，待黑暗/光明阵营声名达到 10 解锁暗黑之触与光明之触，并使用转化后的亵渎象征符/圣洁象征符制作石质祭坛(Stone Alter)与长者雕像(Elder Statue)，替换木制祭坛与稻草塑像
	- 暗黑之触(Touch of Darkness)：邪恶符文 - 魂魄符文 - 邪恶符文 - 魂魄符文
	- 光明之触(Touch of Light)：神圣符文 - 魂魄符文 - 神圣符文 - 魂魄符文
8.  黑暗/光明阵营声名达到 15 时(提示需要新的知识)，解锁新颂歌/供奉，完成后解锁声名上限至 35，并获得心灵符文(Mind Sign)
	- 黑暗阵营解锁村民生祭(Sacrifice Villager)：杀死一个村民使高脚杯装满村民血液，念出颂词：血液符文 - 邪恶符文 - 血液符文 - 魂魄符文，增加 (6 + 威能) 黑暗神祈声名，获得 (声名 + 威能 * 2) 魔能
	- 光明阵营解锁圣疗术(Lay on Hands)：念出颂词：火焰符文 - 魂魄符文 - 神圣符文 - 魂魄符文 - 神圣符文，消耗 15 魔能，恢复视线处生物/玩家 5 + 0.05 * 光明神祗声名 的生命值并解除异常状态，治疗其他生物时增加 3 光明神祗声名
9. 黑暗/光明阵营声名达到 35 时(提示需要新的知识)，解锁新符文及新颂歌/供奉，完成后解锁声名上限至 50
	- 黑暗阵营解锁死亡符文(Death Sign)
	- 光明阵营解锁和谐符文(Harmony Sign)
	- 黑暗阵营解锁僵尸化(Zombify)：念出颂词：死亡符文 - 血液符文 - 邪恶符文 - 死亡符文 - 魂魄符文 - 血液符文，将视线处的村民变成僵尸村民，增加 (8 + 1.25 \* 威能) 黑暗神祈声名，获得 (声名 + 威能 * 2) 魔能
	- 光明阵营解锁圣疗术(Lay on Hands)：念出颂词：神圣符文 - 魂魄符文 - 心灵符文 - 和谐符文 - 火焰符文 - 魂魄符文，将视线处的僵尸村民转化为正常村民(视为玩家治愈，==可打折?==)，，增加 (8 + 1.25 \* 威能) 光明神祈声名，获得 (声名 + 威能 * 2) 魔能
10. 黑暗/光明阵营声名达到 50 时(提示需要新的知识)，解锁新符文及新==法术==，完成后解锁声名上限至 100(max)
	- 解锁魔法符文(Magic Sign)
	- 黑暗阵营解锁奴役(Enthrall)：念出颂词：邪恶符文 - 心灵符文 - 魔法符文 - 魔法符文 - 心灵符文，消耗 100 \* 目标生命值% 魔能，奴役玩家视线处的亡灵生物
	- 光明阵营解锁圣惩(Smith)：念出颂词：火焰符文 - 魔法符文 - 神圣符文 - 死亡符文 - 魔法符文 - 神圣符文，对玩家视线处的亡灵生物造成 10 点伤害并赋予 10s 虚弱 III 效果

# 参考资料
1. [Eldolon 声名系统](https://www.mcmod.cn/item/828725.htmlr)
2. [Eldolon 祭坛及可放置的神秘物品](https://www.mcmod.cn/item/821643.html)
3. [Eldolon 游戏设定](https://www.mcmod.cn/item/list/15864-10.html)
4. [Eldolon 仪式火盆及仪式](https://www.mcmod.cn/item/821657.html)