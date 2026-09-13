# Star Dragon 星龙 - 问题反馈

**[English](https://github.com/Tangwenjun910/star-dragon-issues/blob/main/README.md) | 中文**

---

本仓库**只用于收集 bug 反馈和问题追踪**。这里没有源代码，也不接受 Pull Request。需要下载模组或查看文档，请到项目主页。

**Star Dragon（星龙）** 是 [Dragon Survival（龙之生存）](https://www.curseforge.com/minecraft/mc-mods/dragons-survival) 的附属模组，新增星龙物种。
支持 `Minecraft 1.21.1` 和 `NeoForge 21.1+`。

本仓库是公开的，请不要贴支付信息、私人服务器地址等敏感内容。

## 怎么提 bug

用下面的模板开 Issue，模板会明确提示需要提供哪些信息。

- [提交 Bug](https://github.com/Tangwenjun910/star-dragon-issues/issues/new?template=bug_report-zh.yml) - 崩溃、报错、技能或机制不按预期工作
- [问题与建议](https://github.com/Tangwenjun910/star-dragon-issues/issues/new?template=question-zh.yml) - 玩法疑问、平衡性意见、功能请求
- [所有已有 Issue](https://github.com/Tangwenjun910/star-dragon-issues/issues) - 提问前先搜一下，可能已经有人报过

**更习惯英文？** 请用 [英文主界面](https://github.com/Tangwenjun910/star-dragon-issues/blob/main/README.md)。

## 提交前请自查

这一步能省掉很多来回沟通：

1. **装齐必需依赖**：Dragon Survival 和 GeckoLib 都是必需依赖，缺了会直接崩。兼容版本见 [CurseForge 页面](https://www.curseforge.com/minecraft/mc-mods/star-dragon-dragon-survival-addon)。
2. **先确认更新**：最新文件都会发布在 CurseForge 的 Files 标签。提 bug 前请先更新到最新版。模组面向 Minecraft **1.21.1** + NeoForge。
3. **最小环境复现**：先只装 Dragon Survival + Star Dragon 复现一次。如果问题消失了，说明是模组冲突，请列出你装的模组。
4. **换最新版试试**：如果你用的不是最新版，先升级再复现一次。
5. **搜一下已有 Issue**：避免重复提交。

## 什么值得报

**欢迎报**：游戏崩溃、技能或机制不按预期工作、数值明显异常、多人游戏不同步、与其他模组冲突、渲染或贴图错误。

**请不要在这里报：**

- 龙之生存**本体**的问题 - 请去 [龙之生存官方仓库](https://github.com/DragonSurvivalTeam/DragonSurvival/issues) 反馈。
- 配置文件改坏导致的问题 - 先删掉 config 让游戏重新生成。
- 光影或材质包引起的画面问题 - 先关掉光影、换回原版材质确认一次。

## 标签说明

| 标签 | 含义 |
|---|---|
| `bug` | 已确认是缺陷 |
| `needs-repro` | 已收到报告，但还没复现出来 |
| `needs-info` | 缺日志或版本信息，等待补充 |
| `confirmed` | 已复现，确认是本模组的问题 |
| `fixed` | 已在某个版本修复 |
| `cannot-reproduce` | 按提供的信息无法复现 |
| `planned` | 已排期，等待版本发布 |
| `invalid` | 设计如此、上游问题或超出支持范围 |

## 处理节奏

这是个人业余时间维护的项目，不保证响应时间。但每个 Issue 都会看，也都会回复。版本信息齐全、日志完整、步骤清晰的报告处理最快。