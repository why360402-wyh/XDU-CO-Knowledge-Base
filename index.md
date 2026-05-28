# 《计算机组成与设计》知识库总索引

> 教材：李伯成、顾新 编著，清华大学出版社，2011版
> 课程：计算机组成原理 I（XDU）

---

## 📖 章节导航

### [第2章 计算机中的数据表示](./knowledge_points/ch02_data_representation/index.md)
数值转换、原码/反码/补码、定点数、浮点数、BCD码

| 知识点 | 考点等级 |
|--------|:--------:|
| [数制与进制转换](./knowledge_points/ch02_data_representation/number_system_conversion.md) | ⭐⭐⭐⭐⭐ |
| [原码表示](./knowledge_points/ch02_data_representation/original_code.md) | ⭐⭐⭐⭐ |
| [补码表示](./knowledge_points/ch02_data_representation/twos_complement.md) | ⭐⭐⭐⭐⭐ |
| [反码表示](./knowledge_points/ch02_data_representation/ones_complement.md) | ⭐⭐⭐ |
| [定点数与浮点数](./knowledge_points/ch02_data_representation/fixed_and_float_point.md) | ⭐⭐⭐⭐ |
| [BCD码](./knowledge_points/ch02_data_representation/bcd_code.md) | ⭐⭐⭐ |

### [第3章 存储系统](./knowledge_points/ch03_memory/index.md)
SRAM、DRAM、存储器芯片与CPU连接

| 知识点 | 考点等级 |
|--------|:--------:|
| [SRAM vs DRAM](./knowledge_points/ch03_memory/sram_vs_dram.md) | ⭐⭐⭐⭐⭐ |
| [存储器芯片与8086接口](./knowledge_points/ch03_memory/memory_chip_interface.md) | ⭐⭐⭐⭐⭐ |
| [内存地址映射与译码](./knowledge_points/ch03_memory/address_decoding.md) | ⭐⭐⭐⭐ |

### [第4章 指令系统](./knowledge_points/ch04_instruction_set/index.md)
指令格式、扩展操作码、寻址方式、8086/8088指令

| 知识点 | 考点等级 |
|--------|:--------:|
| [指令格式与扩展操作码](./knowledge_points/ch04_instruction_set/instruction_format.md) | ⭐⭐⭐⭐⭐ |
| [8086/8088寻址方式](./knowledge_points/ch04_instruction_set/addressing_modes.md) | ⭐⭐⭐⭐⭐ |
| [MOV指令与数据传送](./knowledge_points/ch04_instruction_set/mov_instruction.md) | ⭐⭐⭐⭐⭐ |
| [LEA指令与有效地址](./knowledge_points/ch04_instruction_set/lea_instruction.md) | ⭐⭐⭐⭐ |

### [第5章 CPU与控制器](./knowledge_points/ch05_cpu/index.md)
微程序控制器、微指令格式、数据通路、微操作

| 知识点 | 考点等级 |
|--------|:--------:|
| [微程序控制器原理](./knowledge_points/ch05_cpu/microprogrammed_control.md) | ⭐⭐⭐⭐⭐ |
| [微指令格式设计](./knowledge_points/ch05_cpu/microinstruction_format.md) | ⭐⭐⭐⭐⭐ |
| [数据通路与微操作流程](./knowledge_points/ch05_cpu/data_path.md) | ⭐⭐⭐⭐⭐ |
| [触发逻辑与时序](./knowledge_points/ch05_cpu/control_logic.md) | ⭐⭐⭐⭐ |

---

## 📂 目录结构

```
计组知识库/
├── index.md              ← 总索引（你在这里）
├── CODEX.md              ← 知识库操作宪章
├── AGENTS.md             ← Agent 工作约束
├── sources/              ← 原始层（教材原文、试卷原件）
├── materials/            ← 证据层（整理稿、图表解读）
│   ├── ch02_data_representation/
│   ├── ch03_memory/
│   ├── ch04_instruction_set/
│   └── ch05_cpu/
├── knowledge_points/     ← 规范层（知识点页）
│   ├── index.md          ← 知识点总索引
│   ├── ch02_data_representation/
│   ├── ch03_memory/
│   ├── ch04_instruction_set/
│   └── ch05_cpu/
├── evolvement/           ← 演化层（个人理解、笔记）
└── exams/                ← 试题分析与解答
```

---

## 🎯 当前重点

1. **数值转换**（常考基础，已优先整理）
2. **第3章 存储系统**（随堂测验覆盖）
3. **第4章 指令系统**（随堂测验覆盖）
4. **第5章 CPU与控制器**（随堂测验覆盖）
