---
title: "EmfPlusTextRenderingHint 枚举"
type: docs
weight: 430
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---

该 TextRenderingHint 枚举定义了文本提示和抗锯齿的类型，这会影响文本渲染的质量。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusTextRenderingHint

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| TEXT_RENDERING_HINT_ANTIALIAS | 指定每个文本字符使用其抗锯齿字形位图绘制且不进行 hinting。抗锯齿可获得更好的质量，但由于关闭了 hinting，字符笔画宽度差异可能会显现。 |
| TEXT_RENDERING_HINT_ANTIALIAS_GRID_FIT | 指定每个文本字符应使用其带平滑的抗锯齿字形位图绘制。由于抗锯齿，渲染质量很高，但会带来更高的性能开销。 |
| TEXT_RENDERING_HINT_CLEAR_TYPE_GRID_FIT | 指定每个文本字符应使用其带平滑的 ClearType 字形位图绘制。这是最高质量的文本 hinting 设置，用于利用 ClearType 字体特性。 |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL | 指定每个文本字符应使用其字形位图绘制。不使用平滑。 |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL_GRID_FIT | 指定每个文本字符应使用其字形位图进行绘制。可以使用平滑来改善字符字形的笔干和曲线外观。 |
| TEXT_RENDERING_HINT_SYSTEM_DEFAULT | 指定每个文本字符应使用操作系统上配置的任何字体平滑设置进行绘制。 |
