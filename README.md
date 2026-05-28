# 计算机组成与设计 · 知识库

> 李伯成、顾新《计算机组成与设计》（清华大学出版社·2011版）
>
> 基于 **LLM + Wiki** 四层架构的课程知识库，可人读、可 AI 检索、可追溯修正。

[![GitHub](https://img.shields.io/badge/GitHub-仓库-blue?logo=github)](https://github.com/why360402-wyh/XDU-CO-Knowledge-Base)
![Markdown](https://img.shields.io/badge/语言-Markdown-brightgreen)
![License](https://img.shields.io/badge/许可证-MIT-green)

---

## 📖 这是什么？

这是一个面向《计算机组成与设计》课程的 **Markdown-first 知识库**，覆盖**数值转换、存储系统、指令系统、CPU 设计**等核心章节。

与传统的"课本笔记"不同，这里采用 **Karpathy 风格的四层架构**：

```
原始层 (sources/)    → 教材原文、试卷原件（不可改写）
   ↓
证据层 (materials/) → 整理稿、图表解读（保留出处）
   ↓
规范层 (knowledge/) → 知识点页（教材骨架，AI 主要读取）
   ↓
演化层 (evolvement/) → 个人理解、笔记、口诀（你的地盘）
```

---

## 🗂️ 内容目录

| 章节 | 知识点 | 考点等级 |
|:----:|:-------|:--------:|
| 第2章 · 数据表示 | 进制转换 · 原码/反码/补码 · 定点浮点 · BCD码 | ⭐⭐⭐⭐⭐ |
| 第3章 · 存储系统 | SRAM vs DRAM · 6264+8086接口 · 地址译码 | ⭐⭐⭐⭐⭐ |
| 第4章 · 指令系统 | 扩展操作码 · 7种寻址方式 · MOV/LEA指令 | ⭐⭐⭐⭐⭐ |
| 第5章 · CPU设计 | 微程序控制器 · 微指令格式 · 数据通路 · 触发逻辑 | ⭐⭐⭐⭐⭐ |

### 📂 目录结构

```
├── CODEX.md                    # 知识库操作宪章
├── AGENTS.md                   # AI 工作约束
├── index.md                    # 总索引（考点导航）
│
├── knowledge_points/           # ⭐ 规范层：核心知识点
│   ├── ch02_data_representation/
│   ├── ch03_memory/
│   ├── ch04_instruction_set/
│   └── ch05_cpu/
│
├── materials/                  # 证据层：整理稿
│   └── ch03_memory/
│       └── quiz_457_analysis.md
│
├── exams/                      # 🎯 考试专项
│   ├── quiz_457_full_solution.md    # 随堂测验完整解析
│   ├── practice_number_conversion.md # 数值转换专项练习
│   ├── practice_mock_exam.md        # 模拟试卷
│   └── exam_quick_reference.md      # 考前速查手册
│
├── evolvement/                 # 🌱 演化层：你的个人笔记
│   └── README.md
│
└── sources/                    # 原始层：原始资料（待填充）
```

---

## 🚀 怎么用

### 给人类看

从 [`index.md`](./index.md) 开始，按章节导航浏览知识点。

### 给 AI 看

```markdown
请先阅读 index.md 了解知识库结构，
然后按需要读取对应章节的知识点页。
如需追溯原始出处，再读取 materials/ 中的整理稿。
```

---

## 🧪 知识点特色

每个知识点页都包含：

- ✅ **元数据**（编号、出处、标签、考点等级）
- ✅ **核心原理**（以教材表述为骨架）
- ✅ **对比表格**（SRAM vs DRAM、寻址方式对比等）
- ✅ **解题模板**（五步法、通用公式等）
- ✅ **典型例题**（随堂测验原题解析）
- ✅ **常见陷阱**（"这里最容易错"）
- ✅ **练习题**（含可展开的详细解析）

---

## 🛠️ 本地维护

```bash
# 克隆仓库
git clone https://github.com/why360402-wyh/XDU-CO-Knowledge-Base.git

# 修改内容后提交
git add -A
git commit -m "更新说明"
git push
```

---

## 📌 后续计划

- [ ] 补充第1章（绪论）
- [ ] 补充第6~8章（总线 · I/O · 外设）
- [ ] 添加更多模拟试卷和真题解析
- [ ] 完善 evolvement/ 个人笔记

---

## 📄 许可证

本项目采用 MIT 许可证。
