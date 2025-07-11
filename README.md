# Lilith's Throne 中文本地化发布库

---
![Static Badge](https://img.shields.io/badge/Author-Innoxia-purple?link=https%3A%2F%2Flilithsthrone.blogspot.com%2F)
![GitHub release (with filter)](https://img.shields.io/github/v/release/chinese-liliths-throne/liliths-throne-chinese-release?link=https%3A%2F%2Fgithub.com%2Fchinese-liliths-throne%2Fliliths-throne-chinese-release%2Flatest)
![GitHub all releases](https://img.shields.io/github/downloads/chinese-liliths-throne/liliths-throne-chinese-release/total?link=https%3A%2F%2Fgithub.com%2Fchinese-liliths-throne%2Fliliths-throne-chinese-release%2Freleases%2Flatest)
![GitHub Repo stars](https://img.shields.io/github/stars/chinese-liliths-throne/liliths-throne-chinese-release)
![GitHub issues](https://img.shields.io/github/issues-raw/chinese-liliths-throne/liliths-throne-chinese-release)

官方 Discord 交流服务器：

[![](https://dcbadge.limes.pink/api/server/nDRvMXH)](https://discord.gg/nDRvMXH)

汉化 Discord 交流服务器：

[![](https://dcbadge.limes.pink/api/server/hqj7WA7PKp)](https://discord.gg/hqj7WA7PKp)

---

<div align="center">

# 请在下载游玩前首先阅读本说明文档<br>对于在文档中写明的内容仍进行提问的将不作解答

</div>

---

## 目录

* [简介](#简介)
  * [写在最前](#写在最前)
  * [关于本仓库](#关于本仓库)
  * [关于游戏发布下载](#关于游戏发布下载)
  * [关于版本号](#关于版本号)
* [免责声明](#免责声明)
* [致谢名单](#致谢名单)
* [更新日志](#更新日志)

---

## 简介
### 写在最前...
- <img decoding="async" src="https://avatars.githubusercontent.com/u/25914384?v=4" width="24" alt=""> <b>游戏作者</b> $\color{purple} {Innoxia}$

  - [Innoxia 的博客][blog]
  - [游戏维基][wiki]
  - [官方 Discord][discord]
  - [汉化 Discord][discord-zh]
  - [游戏源码仓库][github]

### 关于本仓库

本仓库将在每周一（或许）更新游戏的简体中文本地化版本，仅供交流学习，请于下载后 24 小时内删除。如果你未满 18 岁，请勿下载此游戏。仓库本身不含游戏相关内容，仅作为发布地址。**对在其它平台下载的汉化游戏文件不保证安全性，请谨慎下载。**

游戏完全免费游玩，**严禁**将中文本地化版本**用作商业盈利用途**或**公开大肆传播**，对于商业盈利或公开传播导致的可能法律后果完全由使用者自行承担，与汉化成员无关。

如在游玩过程中遇到任何问题，或对汉化文本有建议，请[发布 issue(议题)][issues] 反馈，反馈时请附上出现问题时的**截图 + 描述 + 游戏存档文件 + 报错文件**，在其它平台反馈问题可能得不到回应。请不要删除自己的议题, 方便后来人查阅相关问题。请注意，本仓库仅解决由于游戏汉化版本导致的问题，如果问题在英文版能复现，请去游戏官方 [Discord][discord] 反映。

### 关于游戏发布下载

本仓库发布的模组加载器和汉化包，与二者各自打包仓库发布的完全相同。自动打包仓库的更新将比本仓库更新更频繁。有需要的玩家也可以自行前往对应仓库下载：

|    汉化包自动打包地址     |
|:----------------:|
| [地址][i18n-build] |

#### 发布下载版
- 本仓库每月一号更新，下载请见右侧/底部的 [releases(发行版)][releases-latest]
- 请根据以下指导选择需要的文件下载：
  - 对于 Windows 系统的用户：
    - 若电脑（CPU 架构）为 64 位（一般来说只要不是太老的电脑，都是64位），请选择 `win-x64` 版本
    - 若电脑（CPU 架构）为 32 位，请选择 `win-x86` 版本
  - 对于 MacOS 系统的用户：
    - 请通过[该教程](https://juejin.cn/post/7112023770247725063)确定电脑的 CPU 架构
    - 若为 x86_64 请选择 `mac` 版本
    - 若为 arm64 请选择 `mac-aarch64` 版本
    - 请务必安装jdk17的最新版本
  - 对于 Linux 系统的用户：
    - 也可以使用上述教程确定 CPU 架构
    - 若为 x86_64 请选择 `linux` 版本
    - 若为 arm64 请选择 `linux-aarch64` 版本
    - 请自行安装jdk

- 在此附上使用手机游玩的[可能性方案](https://github.com/Agreous/liliths-throne-on-android#readme)，比较复杂，且对手机性能有一定要求。

### 关于版本号
汉化版本号的基本结构是 `chs-x.y.z`，如 `chs-1.7.1a`

游戏版本号的基本结构是 `{游戏版本号}-chs-{汉化版本号}`，如 `0.4.10.0-chs-1.0.0a`

汉化版本号的修改遵循如下规则：
1. `a` / `b` / `r` 分别代表：
  - `alpha`: 当前翻译率达到 100%, 可能有漏提取的文本，润色不充分
  - `beta`: 当前翻译率达到 100%, 没有漏提取的文本，润色不充分
  - `release`: 当前翻译率达到 100%, 没有漏提取的文本，已经充分润色
2. 如果游戏版本号发生破坏性更新：如 `0.4.9` => `0.4.10`, 或 `0.4` -> `0.5`，则汉化版本号重置，如：
  - `0.4.10.0-chs-1.7.1a` => `0.4.11.2-chs-1.0.0a`
3. 如果游戏版本号发生小修小补更新：如 `0.4.10.6` => `0.4.10.7`, 或 `0.4.9.0` => `0.4.9.5`，则汉化版本号第一位加一，如：
  - `0.4.10.1-chs-1.0.0a` => `0.4.10.2-chs-2.0.0-a`
4. 常规更新，则汉化版本号第二位加一，如：
  - `0.4.10.0-chs-1.6.0a` => `0.4.10.0-chs-1.7.0a`
5. 出现了导致游戏无法继续进行的恶性问题而临时更新，则汉化版本号末位加一，如：
  - `0.4.10.0-chs-1.7.0a` => `0.4.10.0-chs-1.7.1a`

### Star 数

[![Star History Chart](https://api.star-history.com/svg?repos=chinese-liliths-throne/liliths-throne-chinese-release&type=Date)](https://star-history.com/#chinese-liliths-throne/liliths-throne-chinese-release&Date)

---

## 免责声明

1. 汉化组认可且负责的汉化版唯一发布渠道为 GitHub（即本仓库），其余渠道均不受认可，汉化组也不对来自其他渠道的汉化版本出现或造成的问题负责。自非官方 GitHub 渠道获取的汉化版可能会被篡改，可能会造成不可预料的后果，请务必以 GitHub 渠道发布的汉化版为准。我们可能不会接受使用非官方发布版本的内容反馈。
2. 汉化组不对任何修改后的汉化版本负责，包括但不限于修改游戏本体 html 文件，使用可能改变游戏内容的模组，使用他人发布的整合包等；汉化组也不会为任何第三方发布的模组版/修改版/魔改版/整合包等背书或担保。请在反馈问题前检查游戏是否已被修改，若被修改请勿提交，我们可能不会接受使用修改版本的内容反馈。
3. 请尽量避免重复报告问题。汉化版游戏文件夹根目录会有文件提示当前汉化版本号，反馈问题时请确认自己正使用最新版本的汉化版，请不要提交过时版本中出现的问题。鉴于此，推荐使用 GitHub 的 `issue` 系统提交问题，在提交前请自行寻找 `closed issues` 中是否已存在相同问题。
4. 汉化组仅能忠实将原游戏内容以中文呈现，无法对原游戏内容做出更改，亦无法决定将来的内容变更或更新。一切有关更新计划、游戏机制、剧情、角色、世界观等方面的内容均以原作者 innoxia 为准。汉化组可能会收集有关问题并向 innoxia 反馈，但不做保证，也无法保证 innoxia 会回答。
5. 汉化组的职能仅限于汉化游戏文本，以及修复由汉化所导致的游戏问题。对汉化组人员提出的其他任何需求，汉化组方面均有权拒绝。
6. 本公告的最终解释权由汉化组享有，未尽事宜均以汉化组采取之行为为准。

---

## 致谢名单
* 该 README 文件修改自[DOL汉化发布页][github-dol]
* 其他请见 [致谢名单](CREDITS.md)

---

## 更新日志
<details>
<summary>点击展开</summary>

- 2025.7.11
  - 发布 `0.4.11.3-chs-2.1.0a` 版
    - 修复了高桥、影、婕斯、法埃立绘不显示的问题

- 2025.7.4
  - 发布 `0.4.11.3-chs-2.0.1a` 版
    - 调整了部分文本的翻译
    - 补充部分缺失的汉化
    - 调整了非Windows平台下版本号文件放置位置的问题
    - 放入了原版中存在的 `README`, `disclaimer` 等文件

- 2025.6.27
  - 发布 `0.4.11.3-chs-2.0.0a` 版
    - 完成 0.4.11.3 版本的汉化

- 2025.6.23
  - 发布 `0.4.11.1-chs-1.0.2a` 版
    - 补充部分缺失的汉化

- 2025.6.21
  - 发布 `0.4.11.1-chs-1.0.1a` 版
    - 补充部分缺失的汉化

- 2025.6.21
  - 发布 `0.4.11.1-chs-1.0.0a` 版
    - 完成 0.4.11.1 版本的汉化

- 2025.6.15
  - 发布 `0.4.10.9-chs-1.0.1a` 版
    - 修复了部分情况下对话内容显示错误的问题
    - 修复了获得“疲惫”时会导致侧边栏消失的问题
    - 补全了部分汉化

- 2025.6.10
  - 发布 `0.4.10.9-chs-1.0.0a` 版
    - 完成 0.4.10.9 版本的汉化

- 2025.1.5
  - 发布 `0.4.10.7-chs-1.0.1a` 版
    - 修复了部分情况下出现乱码的问题

- 2025.1.3
  - 发布 `0.4.10.7-chs-1.0.0a` 版
    - 完成对应版本的汉化

- 2024.12.30
  - 发布 `0.4.10.3-chs-1.0.0a` 版
    - 完成对应版本的汉化

- 2024.9.12
  - 发布 `0.4.10.0-chs-1.0.0a` 版
    - 基本完成了提取，仅有部分文本遗漏，完全汉化，未润色

</details>

[blog]: https://lilithsthrone.blogspot.com/
[wiki]: http://tptiap.co.uk/index.php/Main_Page
[github]: https://github.com/Innoxia/liliths-throne-public
[github-dol]: https://github.com/Eltirosto/Degrees-of-Lewdity-Chinese-Localization/tree/main
[discord]: https://discord.gg/nDRvMXH
[discord-zh]: https://discord.gg/hqj7WA7PKp
[releases-latest]: https://github.com/chinese-liliths-throne/liliths-throne-chinese-release/releases/latest
[i18n-mod]: https://github.com/Lyoko-Jeremie/Degrees-of-Lewdity_Mod_i18nMod
[i18n-build]: https://github.com/chinese-liliths-throne/liliths-throne-chinese-localization
[issues]: https://github.com/chinese-liliths-throne/liliths-throne-chinese-release/issues
