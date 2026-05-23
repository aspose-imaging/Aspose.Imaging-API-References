---
title: "Перечисление SampleRoundingMode"
type: docs
weight: 80
url: /ru/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

Определяет способ, которым n‑битное значение преобразуется в 8‑битное значение.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| EXTRAPOLATE | Экстраполировать 8-битное значение, чтобы разместить его в n битах, где 1 &lt; n &lt; 8.<br/>            Количество всех возможных 8-битных значений равно 1 &lt;&lt; 8 = 256, от 0 до 255.<br/>            Количество всех возможных n-битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1.<br/>            Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Обрезать 8-битное значение, чтобы разместить его в n битах, где 1 &lt; n &lt; 8.<br/>            Количество всех возможных n-битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1.<br/>            Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
