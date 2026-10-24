# course-tutor

**课程伴学精灵(蒲公英)** · v2.4.0 · `agent`

> Course companion agent (teacher edition) with full build source — roster, analytics, weekly reports


Part of the [Lucewalk Lumen](https://github.com/Lucewalk-Lumen/about-me) collection.


## What it does

- **Roster import & learning analytics** — class rosters in, participation and mastery analytics out
- **Nine audit-ready Python modules** — calendar, datakit, mastery, points, report, tdoc, usage-log, viz, warn
- **Weekly teaching briefings** — what happened, who is falling behind, what to do next
- **Data hub config** — `data_hub_config.json` makes the data plane explicit and extensible
- **Student-edition build pipeline** — `scripts/` includes build_student.py and the full student-variant source

## How it works

- Single agent, nine composable modules — each module is a readable, auditable Python file
- The data hub keeps the agent stateless: files in, structured state out
- Full source ships with the package, so every computation can be checked

## Agent roster

| Agent | Role |
|---|---|
| `course-tutor` | 课程伴学专家 |

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk-Lumen/course-tutor/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v2.4.0**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).


---

## How to use / 如何使用

This is an **expert package / skill for the WorkBuddy AI assistant**.

**Prerequisites · 前置条件**
- WorkBuddy installed and signed in (latest version recommended).
- Prepare your own materials first (e.g. your literature library / course outline) — the agent works under a "stay faithful to the source, cite the page" rule.

**Import / enable · 导入 / 启用**
1. Download the package zip from this repo's **Releases**, or clone the repo; keep the `.codebuddy-plugin/` manifest intact.
2. In WorkBuddy, *custom connector → trust & enable*, or import the expert / enable the skill from the skill center.
3. Run one minimal example below to confirm the output matches your standards.

**Minimal example · 最小示例**
> 导入我的学生花名册,生成本周学情周报与预警。

**More · 更多**
Full onboarding & per-line guidance: portal [Lucewalk Lumen · 沐光行客](https://github.com/Lucewalk-Lumen/about-me) → "How to use". Issues: open one on this repo.

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# 课程伴学精灵(蒲公英)

**课程伴学精灵·教师版(含完整源码):花名册、学情分析、周报,九个可审计 Python 模块**

- 版本:v2.4.0 · 类型:agent
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[Lucewalk Experts 门户](https://github.com/Lucewalk-Lumen/about-me)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk-Lumen/course-tutor/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
