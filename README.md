# AutoDuty

<img align="right" width="150" height="150" src="logo.png">

AutoDuty (简译自动副本 简写AD) 是一款为 FFXIV 设计的卫月插件，可以编写副本中自动寻路和战斗的的工具。请勿用于与真人玩家匹配使用！！！！！！

Puni.sh的discord频道[链接](https://discord.com/channels/1001823907193552978/1236757595738476725) of the [Puni.sh Discord server](https://discord.gg/punishxiv).

请尊重作者的版权 [版权条例](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#choosing-the-right-license)

# Dungeon Paths

<img align="right" height="250" src="Assets/paths.png">

每个AutoDuty支持的副本都预先配置了路径，正常情况下一般不会出现问题。如果遇到任何问题，请在Discord频道中反馈。[Discord链接](https://discord.gg/punishxiv).

副本支持表格在paths栏目（个人实测1193的path有一点小问题，请自行决定是否删除）

你可以自行在`Build`标签创建副本支持。并[分享到DC](https://discord.com/channels/1001823907193552978/1236757595738476725/1243059104528994334) [AutoDuty channel](https://discord.com/channels/1001823907193552978/1236757595738476725) 参阅开发文档。

# Automatic Leveling（自动升级切本）

<img align="right" height="250" src="Assets/leveling.png">

可以实现持续的自动化升级你的副战职。
以下原文太长，不想翻译了^_^大意为可以开启自动一键最强装备（需安装额外的插件，在下文），并且自动化选择当前装等及等级可以打的最高级副本。（请确保你的paths中已经把有问题的副本文件删除了）
<details>
  <summary>点击展开/原文</summary>
  
  （原文）With AutoDuty, you can level a job from 15 to the max level very quickly and fully AFK, provided you have the correct gear and the option in the AD configuration to automatically equip the best gear.

This plugin can also level trusts for you in the same way it levels your jobs. It can intelligently select trust members and level them all to max, fully AFK.
</details>

# Automations（自动化的功能）

可以自动化的一些功能（保留原文用于对照）:

| Before runs（循环前） | During the run | Between runs（副本及循环中） | After the runs |
| -------- | -------- | -------- | -------- |
| Move to an inn, house, or FC house（移动到旅馆，个人房屋或部队房） <br /> Auto self- or NPC- repair（自动修理或找npc修理） <br /> Execute commands（执行命令） (例如：SND脚本) <br /> Auto consume items（自动使用物品） | Loot treasure coffers（自动开启宝箱） <br /> Manage plugin states（托管插件） | Auto extract materia（自动拿材料） <br /> Auto desynth loot（自动开宝箱） <br /> Auto turn in loot to GC（自动交互） <br /> Use AutoRetainer（自动雇员） <br /> Auto equip best gear（自动一键最强） | Stop looping at a level（满级自动停止） <br /> Stop looping when you run out of rested XP（经验蓝条耗尽时停止） <br /> Turn on AutoRetainer multi mode（自动打开雇员收取模块的挂机收雇员模式） <br /> Shut down your computer（关机） |

<hr />

# Installation（安装教程）

把 `https://puni.sh/api/repository/herc` 添加到您的插件仓库中（不会的回家喝奶去！） `AutoDuty` 搜索并启用。

打开插件或者在聊天栏输入命令打开 `/ad`.

## Required Plugins（必要的支持插件）

以下插件自行导入。

- [vnavmesh](https://puni.sh/api/repository/veyn): 自动寻路插件（看不懂设置的自己找中文库食用）
- [Rotation Solver Reborn](https://raw.githubusercontent.com/FFXIV-CombatReborn/CombatRebornRepo/main/pluginmaster.json): （秋蝗的自动输出模块，十万行优质代码，笑死，有瓜）可以用别的插件替代，自行寻找并自行配置。
- [BossmodReborn](https://raw.githubusercontent.com/NiGuangOwO/DalamudPlugins/main/pluginmaster.json): 自动躲避机制（谢谢支持逆光喵~）逆光库友链

## Optional Plugins（选用插件）

The following plugins are optional. They integrate with AutoDuty well and in some cases can be triggered by AD itself.

- [Deliveroo](https://plugins.carvel.li): <s>自动交军票，别用，别问为什么</s>
- [Gearsetter](https://plugins.carvel.li): 自动一键最强（在兵装库和背包中寻找）
- [AutoRetainer](https://love.puni.sh/ment.json): 自动雇员模块（喜欢就用，不喜欢就去用DR）

# Getting help（以下是help，不翻译了）

<details>
  <summary>点击展开/折叠</summary>
  
  When you've found a bug or think you have an issue with the plugin, please ask in [this channel](https://discord.com/channels/1001823907193552978/1236757595738476725) in the [Puni.sh Discord server](https://discord.gg/punishxiv). It might be a known issue or people might be able to help you quickly. Additionally, sometimes it might be an issue with one of the required plugins. Users in Discord will be able to help triage the issue and send you to the right place.

Best practice is to not say "I died in this dungeon and I don't know why." Please make sure to include as much detail as possible. What boss were you on? Did you get stuck in a specific spot?

For support with Veyn's Boss Mod and vnavmesh, please ask in [this channel](https://discord.com/channels/1001823907193552978/1191076246860349450) in the [Puni.sh Discord server](https://discord.gg/punishxiv). For support with BossModReborn and Rotation Solver Reborn, please ask in the [Combat Reborn Discord server](https://discord.gg/p54TZMPnC9).

Lastly, feel free to create issues with feature requests and bug reports.
</details>
