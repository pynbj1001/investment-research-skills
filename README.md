# 投研分析四件套（Investment Research Skills）

四个投研分析 Agent Skills 备份仓库。

## 包含的 Skill

| 目录 | 说明 |
|------|------|
| `exponential-growth-stock-research/` | 多层面指数增长·科技革命投研（五层因果链 + 八张后台作业卡，2026-10-08 并入技术革命式成长 v3.0；2026-10-25 新增纪实研究模式） |
| `fx-bond-research/` | 外汇和债券投研分析与新闻数据解读：横向多国比较、纵向历史时间轴、历史同类场景（2026-10-13 读者体验版） |
| `stock-research/` | 股票投研分析：一步判清靠哪种钱，主体是关键变量驱动模型、共识分歧、行业模块、法证排查（2026-10-25 重写） |
| `safety-margin-titans/` | 安全边际价值研究：格雷厄姆与董宝珍、散户乙、丁宁、卡拉曼四位投资者的思考为主体，成稿借历史纪实笔法（2026-10-25 v3.1） |

## 安装方式

把三个文件夹整个复制到对应程序的 skills 目录即可。例如：

```bash
# macOS / Linux
cp -r exponential-growth-stock-research fx-bond-research stock-research safety-margin-titans ~/.agents/skills/

# 或 Windows（PowerShell）
Copy-Item -Recurse -Destination "$env:USERPROFILE\.agents\skills\" exponential-growth-stock-research, fx-bond-research, stock-research, safety-margin-titans
```

安装后目录结构示意：

```
~/.agents/skills/
├── exponential-growth-stock-research/
│   └── SKILL.md
├── fx-bond-research/
│   └── SKILL.md
├── stock-research/
│   └── SKILL.md
└── safety-margin-titans/
    └── SKILL.md
```

## 备份日期

2026-10-25：新增 safety-margin-titans（v3.1）；stock-research 重写；fx-bond-research 更新为账户当前版本。exponential-growth-stock-research 在 2026-10-18 版本上新增纪实研究模式（9.12）：五层判断各由一件有出处的历史事实支撑，关键人物与关键决策按历史纪实笔法写成长篇报告。

2026-10-18（三个技能同步升级：关键结论要外部验收，决定结论的前提要从原始数据复现，深度和动仓题由独立 agent 复核；开工前先写顶尖从业者四问，个股类加做空者和法务会计师核查；锁范围时写明服务的决定，结论落到该决定上，带失效条件和触发条件）

2026-10-08（exponential-growth-stock-research 升级；stock-research 仅同步一处引用；fx-bond-research 重构：主轴改为三问，模块按干活顺序重排，去重后体量约为原来的一半）
