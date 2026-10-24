# campus-ppt-helper

**校园演示帮手团** · v1.0.3 · `team`

> Campus presentation helper — slide building for teaching and academic settings


Part of the [WorkBuddy Experts](https://github.com/Lucewalk/lucewalk-experts) collection.


## What it does

- **Content architect** — structures the storyline before any slide exists
- **Collector & asset retriever** — gathers and organizes source material and media assets
- **Slide maker** — produces the deck itself
- **QA reviewer** — reviews the deck for logic, layout and audience fit before you present

## How it works

- A six-member assembly line: collect → architect → retrieve assets → make → QA
- Six dedicated skills (collect / core / design / make / media / qa) map one-to-one to the pipeline
- QA is a separate agent, so the reviewer is never the author

## Agent roster

| Agent | Role |
|---|---|
| `campus-ppt-asset-retriever` | 检索员·甄库 |
| `campus-ppt-collector` | 采集员·采真 |
| `campus-ppt-content-architect` | 设计师·立纲 |
| `campus-ppt-lead` | 校园演示帮手团 - 主理人 |
| `campus-ppt-maker` | 制作员·成章 |
| `campus-ppt-qa` | 质检员·严检 |

## Skills

`campus-ppt-collect` · `campus-ppt-core` · `campus-ppt-design` · `campus-ppt-make` · `campus-ppt-media` · `campus-ppt-qa`

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/campus-ppt-helper/releases) or clone this repo;
2. Unzip keeping the `.codebuddy-plugin/` manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v1.0.3**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).


---

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# 校园演示帮手团

**校园演示帮手团:六成员流水线,从大纲到可讲演的教学课件**

- 版本:v1.0.3 · 类型:team
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[WorkBuddy Experts 门户](https://github.com/Lucewalk/lucewalk-experts)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk/campus-ppt-helper/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
