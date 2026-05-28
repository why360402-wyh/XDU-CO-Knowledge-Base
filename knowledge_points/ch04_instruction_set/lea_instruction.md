---
id: kp-04-04
title: LEA指令与有效地址
source: 教材第4章
tags: [LEA, 有效地址, 寻址]
exam_related: true
---

# LEA指令与有效地址

## 1. LEA指令格式

```
LEA  REG, MEM    ; REG ← 有效地址(EA)
```

**注意**：LEA 取的是**有效地址**，而不是地址中的内容！

## 2. MOV vs LEA 对比

| 指令 | 含义 | 示例 | 结果 |
|:----:|:----|:----|:----:|
| `MOV AX, [BX]` | 取 BX 指向的内存内容送 AX | (BX)=0100H, (20100H)=3412H | AX=3412H |
| `LEA AX, [BX]` | 取 BX 的值（有效地址）送 AX | (BX)=0100H | AX=0100H |

## 3. 典型用法

```
LEA  AX, 1100H[BX][SI]
; AX = 1100H + BX + SI（不访问内存）
```

## 4. 常考陷阱

> **LEA 指令不访问内存**，只是计算有效地址。
> 而 `MOV AX, [addr]` 需要访问内存读取数据。
