---
title: 测试文章：LaTeX 公式与图片
date: 2026-04-10 00:00:00
categories:
  - blog
tags:
  - test
---

这是一篇用于验证博客功能的测试文章，包含行内公式、块级公式以及图片插入。

## 行内公式

当 $a \\ne 0$ 时，一元二次方程 $ax^2 + bx + c = 0$ 的解为：
$x = \\frac{-b \\pm \\sqrt{b^2 - 4ac}}{2a}$。

## 块级公式

下面是一个块级公式（使用 `$$ ... $$`）：

$$
\\int_{-\\infty}^{+\\infty} e^{-x^2} \\, dx = \\sqrt{\\pi}
$$

再来一个矩阵示例：

$$
\\mathbf{A} =
\\begin{bmatrix}
1 & 2 & 3 \\\\
4 & 5 & 6
\\end{bmatrix}
$$

## 图片

下面插入一张图片（复用站点已有头像资源）：

![](/img/avatar.png)

如果图片未显示，请确认文件存在于 `source/img/avatar.png`，并重新生成站点。
