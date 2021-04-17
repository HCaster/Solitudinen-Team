# Solitudinem

Language : [English](./README-English.md) | [简体中文](./README.md)

## 基本介绍



1. 这个整合包是我朋友因为学业原因转交于我的。（可是我要上学啊喂）
2. 取名源自拉丁语：Solitudinem，但是我根本不懂拉丁文，我猜测原作者命名时大概是想要取英语中的Solitude之意。
3. 主作者([FaulknerWu](https://github.com/FaulknerWu))冲刺NOIP中，暂不更新。



作者：***Ruang_Feng & [Skye Taylor](https://github.com/cyciling) & [FaulknerWu](https://github.com/FaulknerWu)***

Minecraft版本：**1.12.2**

Forge版本：**2847**

语言支持：**美国英语 & 简体中文**



## 已知问题

1. UI冲突，已通过配置将问题最小化，如果发现比较严重的UI冲突请反馈或PR，对于信息显示（ingameinfoxml）感到碍眼的玩家可以键入命令`/igi disable`。
2. 根据一些测试人员的反馈，存在滞后问题，但是当作者测试该问题时并未发现。 请保持警惕，如果出现滞后，请比较完整地记住发生滞后的环境，以便作者进行测试和修复。
3. 使用死亡后重生附带的“讣告”（gravestone:death_info）会有几率发生崩端，已通过配置禁止重生附带“讣告”。



## FAQ

### 哪些键位被更改为NONE？

它们的原键位会引起键位冲突，作者选择了重要性相对较小的键位设置为NONE。你可以自己为这些NONE键位设置一个合适的键，有些是必须有些无须，取决于个人需求，推荐多设置组合键防止冲突。如有作者未发现的键位冲突请反馈。

| MOD                    | 原键位 | 作用                            |
| ---------------------- | ------ | ------------------------------- |
| Journey Map            | B      | 新建路径点                      |
| Journey Map            | Ctrl+B | 路径点管理器                    |
| Journey Map            | 反斜杠 | 切换小地图预设样式              |
| Journey Map            | Z      | 开启所有导航点                  |
| Journey Map            | 左括号 | 调整地图类型                    |
| Better Builder's Wands | F      | 转换流体模式                    |
| Better Builder's Wands | M      | 转换模式                        |
| Ender IO               | G      | 关闭/开启玄钢盔甲鞘翅或滑翔功能 |
| Minecraft原版          | C      | 保存物品工具栏                  |
| Minecraft原版          | X      | 加载物品工具栏                  |
| Advanced Rocketry      | C      | 打开火箭界面                    |
| Mekanism               | H      | 足部装备模式切换                |
| Mekanism               | U      | 步话机语音                      |
| Draconic Evolution     | P      | 在世界中放置物品                |



## 关于SolitudinemUtils

SolitudinemUtils会在开发过程中持续更新，当它成为了一个成熟的Utils时它会被正式发布。



## 更新日志

备注：

1. Beta版本放出的之前Alpha版本改动日志由于更新较为频繁所以不以版本号而是以日期形式呈现。
2. 更新日志仅仅只是大纲，详细更新内容请查看GitHub。
3. 更新日志中若未特别标明模组版本则为最新稳定版。
4. 自2021/3/14以后不再写明mod添加或移除的详细记录，如果发生改动只会写“mod变动”。

***2020/12/11***

1. 删除Mod CustomLoadingScreen
2. 删除Mod Galacticraft
3. 删除Mod Galacticraft Planets
4. 删除Mod MicdoodleCore
5. 删除Mod GalaxySpace
6. 删除Mod AsmodeusCore
7. 删除Mod InGameInfoXML BloodMagic附属
8. 删除Mod InGameInfoXML Thaumcraft附属
9. 添加Mod Advanced Rocketry
10. 添加Mod Advanced Rocketry Tweaker
11. 添加Mod Libvulpes
12. 删改InGameInfoXML配置文件

***2020/12/12***

1. 删除Mod Journeymap
2. 键位更变
3. 删除Mod Sound Filters
4. 添加Mod Xaeros Minimap
5. 添加Mod Xaeros WorldMap
6. 添加Mod Sound Physics
7. 添加Mod In Game Wiki
8. 更改Dynamic Surroundings配置文件

***2020/12/31***

1. 删除Mod Topography
2. 删除Mod TConstruct
3. 删除Mod ArmoryExpansion
4. 删除Mod Construct's Armory
5. 删除Mod Tinkers' Evolution
6. 删除Mod Tinkers' Addons
7. 删除Mod Tinkers' Complement
8. 删除Mod Tinkers' JEI
9. 调整Config

***2021/1/1***

2. 更新**CraftTweaker Utils**
3. 添加Mod Advanced Mortars
4. 添加Mod Pyrotech
5. 添加Mod Water Power
6. 更新Mod Athenaeum
7. 添加Mod dropt
7. 添加Mod AquaAcrobatics
8. 调整config
9. 由于Xaeros Minimap中出现闪退问题，小地图类型模组恢复为Journeymap
10. 添加Mod TellMe
11. 删除Mod MagicBees
12. 删除Mod JEI Bees
13. 删除Mod BeeBetterAtBees

***2021/1/3***

1. 脚本在原作者基础上进行改写
2. 添加Mod BloodArsenal
3. 添加Mod Animus
4. 添加Mod ArmoreableMobs

***2021/1/22（此次更新可能条目错漏，原因是事先未做统计）***

1. 添加Mod Better Questing
2. 添加Mod Better Questing - Standard Expansion
3. 添加Mod Better Questing - RF Expansion
4. 添加Mod Valkyrie Lib
5. 添加Mod Mystical Agradditions
6. 添加Mod IvToolkit
7. 添加Mod Etlunar
8. 添加Mod MysticalLib
9. 添加Mod Tool Progression
10. 添加Mod RFTools Control
11. 添加Mod RFTools Dimensions
12. 添加Mod RecurrentComplex
13. 添加Mod PlaneFix
14. 添加Mod Overloaded Armor Bar
15. 添加Mod OldJavaWarning
16. 添加Mod NoNVFlash
17. 添加Mod NoMobSpawningOnTrees
18. 添加Mod Neat+
19. 添加Mod MystAgrad Cloche Compat
20. 添加Mod MysticalAgriculture
21. 添加Mod More Overlays
22. 添加Mod KleeSlabs
23. 添加Mod RebornCore
24. 添加Mod JustSleep
25. 添加Mod JustEnoughPetroleum
26. 添加Mod HungerPersistence
27. 添加Mod HorseTweaks
28. 添加Mod Flat Colored Blocks
29. 添加Mod Fence Jumper
30. 添加Mod Environmental Tech
31. 添加Mod Engineer's Doors
32. 添加Mod Demagnetize
33. 添加Mod DefaultOptions
34. 添加Mod CosmeticArmorReworked
35. 添加Mod CookingForBlockheads
36. 添加Mod CompactSolars
37. 添加Mod Colytra
38. 添加Mod ClayBucket
39. 添加Mod Chisels & Bits
40. 添加Mod Broken Wings
41. 添加Mod Blockcraftery
42. 添加Mod BiblioCraft
43. 添加Mod BetterBuildersWands
44. 添加Mod BetterAdvancements
45. 添加Mod Backpack
46. 添加Mod RandomPatches
47. 添加Mod WaterMechanicsBackport
48. 添加Mod AquaAcrobatics
49. 添加Mod Dropt
50. 添加Mod WaterPower
51. 添加Mod Bowered
52. 添加Mod Pyrotech
53. 脚本更新

***2021/1/29***

1. 删除Mod InGameWiki
2. 删除Mod Colytra
3. 删除Mod Better Foliage
4. 删除Mod AgriCraft
5. 删除Mod MysticalAgriculture
6. 删除Mod MysticalAgradditions
7. 删除Mod MystAgrad Cloche Compat
8. 脚本更新
9. config调改

***2021/2/1*** ~~（最水的一次）~~

1. 脚本更新
2. 删除Mod Backpacks
3. 删除Mod GraveStone
4. 键位调整

***2021/2/2***

1. 删除Mod ChestTransporter

***2021/2/7***

1. 添加Mod probe
2. 更新Mod CraftTweaker2到4.1.20.616

***2021/2/9***

1. 键位调整
2. 脚本更新

***2021/2/10***

1. 添加mod：zombieawareness
2. 添加mod：Quantum Minecraft Dynamics
3. 添加mod：Worley's Caves
4. 删除Mod Extra Utilities 2
5. 更新NuclearCraft到2o.4.7
6. config调改

***2021/2/11***

1. 删除Mod DynamicSurroundings [测试到崩端问题]
2. 删除Mod DynamicSurroundingsHuds
3. 添加mod：Just Enough Dimensions
4. config调改

***2021/2/12***

1. 添加mod：ToughExpansion
2. 添加mod：Ore veins
3. 添加mod：ForgeEndertech
4. config调改

***2021/2/14***

1. 添加mod：Zen Utils
2. 删除Mod Recurrent Complex
3. 删除Mod BiblioCraft
4. 添加mod：Ruins
5. config调改

***2021/2/15***

1. 更新mod：FoamFix到0.10.11
2. 删除Mod CompactSolars
3. 删除Mod BNBGamingCore
4. 删除Mod BNBGamingLib
5. 删除Mod IvToolkit
6. 删除Mod Gas Conduits
7. 删除Mod Just A Ore Processing Compatibility Attempt
8. 删除Mod MekanismGenerators
9. 删除Mod OreLibs
10. 删除Mod Reactor Turbines Mod for IC2
11. 删除Mod Rex's Additional Structures
12. 删除Mod Thaumic Wands
13. 删除Mod WrapUp
14. 删除Mod Modular Diversity
15. 更新mod：ModularMachinery到1.11.1
16. 添加mod：GuGu Utils
17. config调改

***2020\2\17***

1. 删除Mod Worley's Caves

***2020\3\14***

1. mod变动



## 鸣谢

- [MinecraftForge](https://github.com/MinecraftForge)团队。
- 所有Mod的发起者以及贡献者，无论作品好坏。
- [Minecraft-Mod-Language-Package](https://github.com/CFPAOrg/Minecraft-Mod-Language-Package)项目发起者以及贡献者。
- Mod Coder Pack反混淆项目
- Mojang公司
- 部分尚未提及者

