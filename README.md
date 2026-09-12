# Star Dragon 星龙 · 问题反馈

> 本仓库**只用于收集 bug 反馈和问题追踪**，这里没有源代码，也不接受 Pull Request。
> 需要下载模组或看玩法文档，请到发布页。

<div align="center">

**Star Dragon（星龙）** 是 [Dragon Survival（龙之生存）](https://www.curseforge.com/minecraft/mc-mods/dragons-survival) 的附属模组，新增星龙物种。<br>
支持 `Minecraft 1.21.1` · `NeoForge 21.1+`

</div>

---

## 🐛 怎么提 bug

点下面的按钮开一个 Issue，**按模板填完**（模板会提示你贴哪些信息）：

- **[提一个 Bug](https://github.com/Tangwenjun910/star-dragon-issues/issues/new?template=bug_report.yml)** — 崩溃、报错、游戏内行为异常
- **[问一个问题 / 提建议](https://github.com/Tangwenjun910/star-dragon-issues/issues/new?template=question.yml)** — 玩法疑问、平衡性意见、功能请求
- **[看所有已有 Issue](https://github.com/Tangwenjun910/star-dragon-issues/issues)** — 提问前先搜一下，可能已经有人报过

> 这个仓库是**公开**的，你发的内容所有人都能看到。请不要贴支付信息、私人服务器地址等敏感内容。

## ✅ 提 bug 前请先自查

这一步能省掉一半的来回沟通：

1. **装齐依赖**：`Dragon Survival 2.0.53+` 和 `GeckoLib 4.x` 是**必需**依赖，缺了会直接崩。
2. **版本对得上**：模组只支持 Minecraft **1.21.1** + NeoForge 21.1+，版本不匹配的问题不受理。
3. **只留必须的模组**：先只装 Dragon Survival + Star Dragon 复现一次；如果问题消失了，说明是模组冲突，请把你装了哪些模组列出来。
4. **换最新版试试**：如果你用的不是最新版，先升级再复现一次。
5. **搜一下已有 Issue**：避免重复提交。

## 📋 什么值得报

**欢迎报**：游戏崩溃、技能/机制不按预期工作、数值明显异常、多人游戏不同步、与其他模组冲突、贴图渲染错误。

**先别急着报**（很可能是上游或配置问题）：

- 龙之生存**本体**的功能问题 → 请去 [Dragon Survival 官方仓库](https://github.com/DragonSurvivalTeam/DragonSurvival/issues)
- 你把配置文件改坏了 → 删掉 `config` 里的配置重新生成试试
- 光影/材质包引起的画面问题 → 先关掉光影、换回原版材质复现

## 🏷 标签说明

| 标签 | 含义 |
|---|---|
| `bug` | 已确认是缺陷 |
| `待复现` | 看到了你的报告，但我这边还没复现出来 |
| `需要更多信息` | 缺日志或版本信息，补上之后我会继续看 |
| `已确认` | 复现成功，确认是模组的问题 |
| `已修复` | 已经在某个版本修好了 |
| `无法复现` | 按你给的信息试了但没复现，会先关闭 |
| `不会处理` | 设计如此、上游问题、或超出支持范围 |

## ⏱ 处理节奏

这是个人业余时间维护的项目，**不保证响应时间**。但每个 Issue 我都会看，看到就会回。提交得清楚（版本全、日志全、步骤明确）的会处理得更快。

---

*English: This repository is only for bug reports and issue tracking for the **Star Dragon** Minecraft mod (a Dragon Survival addon). There is no source code here and no pull requests are accepted. Please use the issue templates when opening a ticket.*