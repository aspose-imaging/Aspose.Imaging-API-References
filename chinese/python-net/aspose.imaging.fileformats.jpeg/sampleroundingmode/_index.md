---
title: "SampleRoundingMode 枚举"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

定义将 n 位值转换为 8 位值的方式。

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| EXTRAPOLATE | 将 8 位值外推以适配 n 位，其中 1 &lt; n &lt; 8。<br/>            所有可能的 8 位值的数量为 1 &lt;&lt; 8 = 256，范围为 0 到 255。<br/>            所有可能的 n 位值的数量为 1 &lt;&lt; n，范围为 0 到 (1 &lt;&lt; n) - 1。<br/>            对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 &gt;&gt; (8 - n)。 |
| TRUNCATE | 将 8 位值截断以适配 n 位，其中 1 &lt; n &lt; 8。<br/>            所有可能的 n 位值的数量为 1 &lt;&lt; n，范围为 0 到 (1 &lt;&lt; n) - 1。<br/>            对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 &amp; ((1 &lt;&lt; n) - 1)。 |
