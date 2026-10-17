# 投研分析三件套（Investment Research Skills）

三大投研分析 Agent Skills 备份仓库。

## 包含的 Skill

| 目录 | 说明 |
|------|------|
| `exponential-growth-stock-research/` | 多层面指数增长·科技革命投研（五层因果链 + 八张后台作业卡，2026-10-08 并入技术革命式成长 v3.0） |
| `fx-bond-research/` | 外汇和债券投研分析与新闻数据解读：横向多国比较、纵向历史时间轴、历史同类场景（2026-10-13 读者体验版） |
| `stock-research/` | 股票投研分析：四条收益主轴 |

## 安装方式

把三个文件夹整个复制到对应程序的 skills 目录即可。例如：

```bash
# macOS / Linux
cp -r exponential-growth-stock-research fx-bond-research stock-research ~/.agents/skills/

# 或 Windows（PowerShell）
Copy-Item -Recurse -Destination "$env:USERPROFILE\.agents\skills\" exponential-growth-stock-research, fx-bond-research, stock-research
```

安装后目录结构示意：

```
~/.agents/skills/
├── exponential-growth-stock-research/
│   └── SKILL.md
├── fx-bond-research/
│   └── SKILL.md
└── stock-research/
    └── SKILL.md
```

## 备份日期

2026-10-18（三个技能同步升级：关键结论要外部验收，决定结论的前提要从原始数据复现，深度和动仓题由独立 agent 复核；开工前先写顶尖从业者四问，个股类加做空者和法务会计师核查；锁范围时写明服务的决定，结论落到该决定上，带失效条件和触发条件）

2026-10-08（exponential-growth-stock-research 升级；stock-research 仅同步一处引用；fx-bond-research 重构：主轴改为三问，模块按干活顺序重排，去重后体量约为原来的一半）
