# 投研分析三件套（Investment Research Skills）

三大投研分析 Agent Skills 备份仓库。

## 包含的 Skill

| 目录 | 说明 |
|------|------|
| `exponential-growth-stock-research/` | 多层面指数增长·科技革命投研（v2 三段八道关） |
| `fx-bond-research/` | 外汇和债券投研分析 |
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

2026-10-07
