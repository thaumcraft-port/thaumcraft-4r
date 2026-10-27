# Thaumcraft 4R

**让神秘时代 4 的探索与魔法，在现代 Minecraft 中延续。**

[English](README.md) · 简体中文

[下载与版本发布](https://github.com/thaumcraft-port/thaumcraft-4r/releases)

Thaumcraft 4R 将神秘时代 4 围绕研究、发现与魔法实验展开的玩法带到现代 Minecraft。用魔导透镜观察世界，认识万物蕴含的要素，在魔导手册中解锁知识；制作法杖、研究灵气节点、搭建炼金工坊，再通过注魔打造更强大的工具与装备。随着研究深入，咒波、腐化与扭曲也会让你体会追求禁忌知识的代价。

这里是 **Thaumcraft 4R 成品构建与配套附属的下载入口**。构建发布后会出现在 Releases 页面：玩家选择运行包，开发者可以下载同批次的 API 与源码包。

## 你可以体验什么

- **研究与发现**：扫描世界中的物品与生物，认识要素，沿着魔导手册逐步拓展自己的魔法知识。
- **法杖与灵气节点**：收集魔力，尝试不同的杖柄与杖端，使用法杖核心将研究成果变为实际能力。
- **炼金与注魔**：提取和运输源质，搭建工坊，通过注魔仪式制作魔法工具与装备。
- **探索与风险**：接触魔法生物和特殊区域，也要面对腐化蔓延与扭曲带来的影响。
- **配套附属生态**：通过神秘工匠、禁忌魔法、污秽魔法、节点力学、神秘扭曲学、神秘基础学等附属扩展玩法。每次发布具体包含哪些模组，以该版本的说明为准。

## 选择适合你的版本

| Minecraft | 加载器 | Java | 运行包文件名 |
| --- | --- | --- | --- |
| 1.20.1 | Forge | 17 | `1.20.1-forge-<构建编号>.zip` |
| 1.21.1 | NeoForge | 21 | `1.21.1-neoforge-<构建编号>.zip` |

打开[发布页](https://github.com/thaumcraft-port/thaumcraft-4r/releases)，下载与你的 Minecraft 版本和加载器对应的运行 ZIP。运行包内直接放置已经编译好的模组 JAR；包含的模组及文件校验和会列在发布说明中。

同批次还提供 **API 与源码包**，文件名为 `<平台>-<构建编号>-dev.zip`，内部按模组保留开发 JAR 子目录，供附属开发与查阅使用。普通玩家安装运行包即可。

## 安装方法

1. 按上表创建对应游戏版本与加载器的实例，并使用相应的 Java 版本。
2. 为该实例安装下表所列的 **Curios** 和 **TerraBlender**。这两个前置不在 ZIP 内；其他联动模组按需安装，并补齐它们各自的前置。
3. 下载并解压对应的运行包，将其中的 JAR 放入实例的 `mods` 文件夹。
4. 本体与附属尽量使用同一次发布中的配套版本。更新时移除它们的旧 JAR，避免重复安装，然后重启游戏或服务器。

这里提供的是 Thaumcraft 4R 与若干附属的模组合集，整合包所需的其他内容可自行搭配。只想体验本体时，安装 `thaumcraft` JAR 和必要前置即可。附属可以按需选择；其中禁忌魔法和神秘基础学还需要神秘工匠。实例中的其他模组可以保留。

Thaumcraft 4R 仍在持续开发。更新已有存档前请先备份，并留意发布说明中的变化与已知问题。

## 前置与联动版本

核对日期：**2026-10-27**。下表结合实际使用的接口、官方已发布 JAR 和模组的加载器依赖要求整理。范围含两端，只覆盖对应 Minecraft／加载器的已发布文件；右端是本次核对到的版本，不代表后续版本一定不兼容。**接口核对不等于所有功能和整合包组合均已运行实测。**

| 模组 | Minecraft 1.20.1 · Forge | Minecraft 1.21.1 · NeoForge | 用途与条件 |
| --- | --- | --- | --- |
| [Curios](https://modrinth.com/mod/curios/versions) | **5.14.1+1.20.1** | **9.5.1+1.21.1** | 本体必需前置 |
| [TerraBlender](https://modrinth.com/mod/terrablender/versions) | **3.0.1.10–3.0.1.11** | **4.1.0.8** | 本体必需前置 |
| [JEI](https://modrinth.com/mod/jei/versions) | **15.56.0.202–15.74.0.230** | **19.36.0.360–19.70.0.460** | 配方、要素与方块预览；范围包含上游标记为 Beta 的版本 |
| [Jade](https://modrinth.com/mod/jade/versions) | 本体 **11.13.0–11.13.3**；装神秘工匠时 **11.13.2–11.13.3** | 本体 **15.10.5–15.10.6**；装神秘工匠时 **15.10.6** | 方块信息与自定义渲染；选择对应加载器文件 |
| [Crafting Tweaks](https://modrinth.com/mod/crafting-tweaks/versions) | **18.2.0–18.2.9** | **21.1.1–21.1.11** | 工作台按钮；需要对应版本的 Balm |
| [KubeJS](https://modrinth.com/mod/kubejs/versions) | **2001.6.3-build.18–2001.6.5-build.26** | **2101.7.2-build.270–2101.7.2-build.377** | 配方与脚本接口；包含部分预发布版本 |
| [Rhino](https://modrinth.com/mod/rhino/versions) | **2001.2.2-build.6–2001.2.3-build.10** | 配合最新 KubeJS：**2101.2.7-build.81–2101.2.8-build.91** | KubeJS 的前置；build.91 是 Beta。Forge KubeJS 还需要 Architectury **9.1.12 或更高** |
| [Applied Energistics 2](https://modrinth.com/mod/ae2/versions) | **15.4.10–15.4.11** | **19.2.17–19.2.18** | 神秘工匠、神秘能源等联动；需要 GuideME（分别为 **20.1.7–<20.2**、**21.1.1 或更高**） |
| [Botania](https://modrinth.com/mod/botania/versions) | **1.20.1-450–1.20.1-456** | **暂无已发布的对应版本** | 神秘工匠、禁忌魔法联动。Forge 需 Patchouli **1.20.1-83 或更高**；NeoForge 开发快照不计为可安装发行版 |
| [CC: Tweaked](https://modrinth.com/mod/cc-tweaked/versions) | **1.116.1–1.120.2** | **1.120.2** | 神秘工匠计算机外设；1.120.2 被上游标为 Alpha |
| [Blood Magic](https://modrinth.com/mod/blood-magic/versions) | **3.3.4-46–3.3.8-50** | 使用下行 NeoVitae | 禁忌魔法联动 |
| [NeoVitae](https://modrinth.com/mod/neovitae/versions) | — | **1.1.34–1.1.48** | 禁忌魔法联动 |
| [Mana and Artifice](https://modrinth.com/mod/mana-and-artifice/version/odH1eB1x) | **3.1.11** | — | 禁忌魔法联动 |

## 更多附属

[Thaumcraft 4R 附属分发与索引](https://github.com/thaumcraft-port/thaumcraft-addons)收录了更多配套附属和联动模组。额外安装时，请同时核对 Minecraft 版本、加载器以及所需的 Thaumcraft 4R 构建版本。

## 致谢

神秘时代的原作者为 **Azanor**。感谢所有参与 Thaumcraft 4R 与配套附属的开发者和贡献者。原模组、美术资源及各个附属的贡献，归属于相应的原作者与参与者。
