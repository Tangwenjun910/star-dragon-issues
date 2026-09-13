# Star Dragon - Issue Tracker

**English** | [中文](https://github.com/Tangwenjun910/star-dragon-issues/blob/main/README.zh.md)

---

This repository is **only for bug reports and issue tracking**. There is no source code here, and pull requests are not accepted. For downloads or documentation, use the project page.

**Star Dragon** is an addon for [Dragon Survival](https://www.curseforge.com/minecraft/mc-mods/dragons-survival) that adds the Star Dragon species.
Supported on `Minecraft 1.21.1` and `NeoForge 21.1+`.

This repository is public. Please do not post payment details, private server addresses, or other sensitive information.

## How to report a bug

Open an issue using one of the forms below. The forms tell you exactly which information to provide.

- [Bug report](https://github.com/Tangwenjun910/star-dragon-issues/issues/new?template=bug_report.yml) - crashes, errors, skills or mechanics not working as expected
- [Question / Suggestion](https://github.com/Tangwenjun910/star-dragon-issues/issues/new?template=question.yml) - gameplay questions, balance feedback, feature requests
- [All existing issues](https://github.com/Tangwenjun910/star-dragon-issues/issues) - please search before posting, your problem may already be reported

**Prefer Chinese?** Use the [Chinese interface](https://github.com/Tangwenjun910/star-dragon-issues/blob/main/README.zh.md), or open the [Chinese bug report form](https://github.com/Tangwenjun910/star-dragon-issues/issues/new?template=bug_report-zh.yml) directly.

## Before you report

This checklist saves a lot of back and forth:

1. **Install the required dependencies.** Dragon Survival and GeckoLib are both required - the game will crash without them. The [CurseForge page](https://www.curseforge.com/minecraft/mc-mods/star-dragon-dragon-survival-addon) lists the compatible versions.
2. **Check for updates.** Newest files are always published on the CurseForge Files tab. Please update to the newest one before reporting. The mod targets Minecraft **1.21.1** with NeoForge.
3. **Test with a minimal setup.** Try reproducing with only Dragon Survival + Star Dragon installed. If the problem disappears, it is a mod conflict - please list the mods you use.
4. **Try the latest version.** If you are not on the latest Star Dragon build, update first and try again.
5. **Search existing issues.** Avoid duplicates.

## What is worth reporting

**Please report:** crashes, skills or mechanics not working as intended, clearly wrong numbers or values, multiplayer desync, mod conflicts, rendering or texture problems.

**Please do not report here:**

- Problems with the **base** Dragon Survival mod - use the [Dragon Survival issue tracker](https://github.com/DragonSurvivalTeam/DragonSurvival/issues) instead.
- Problems caused by broken config files - delete your config and let the game regenerate it first.
- Visual problems caused by shaders or resource packs - disable them and check with vanilla assets first.

## Labels

| Label | Meaning |
|---|---|
| `bug` | confirmed defect |
| `needs-repro` | report received, not reproduced yet |
| `needs-info` | missing log or version information, waiting on the reporter |
| `confirmed` | reproduced, confirmed to be a problem in this mod |
| `fixed` | fixed in a released version |
| `cannot-reproduce` | could not reproduce with the information given |
| `planned` | scheduled to be fixed, waiting for a release |
| `invalid` | works as intended, upstream problem, or out of scope |

## Response times

This is a hobby project maintained in my spare time, so there is no guaranteed response time. Every issue is read, and you will get an answer. Reports with complete versions, logs and clear steps are handled fastest.