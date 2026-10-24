# course-tutor

**课程伴学精灵(蒲公英)** · v2.4.0 · `agent`

> Course companion agent (teacher edition) with full build source — roster, analytics, weekly reports


Part of the [WorkBuddy Experts](https://github.com/Lucewalk/lucewalk-experts) collection.


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

1. Download the package zip from [Releases](https://github.com/Lucewalk/course-tutor/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v2.4.0**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).

