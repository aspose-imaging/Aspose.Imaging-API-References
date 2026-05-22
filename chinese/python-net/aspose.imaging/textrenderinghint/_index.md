---
title: "TextRenderingHint 枚举"
type: docs
weight: 11260
url: /zh/python-net/aspose.imaging/textrenderinghint/
---

指定文本渲染的质量。

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.TextRenderingHint

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| ANTI_ALIAS | 每个字符使用其抗锯齿字形位图绘制，且不进行 hinting。由于抗锯齿，质量更好。由于关闭了 hinting，茎宽差异可能会更明显。 |
| ANTI_ALIAS_GRID_FIT | 每个字符使用带有提示的抗锯齿字形位图绘制。由于抗锯齿，质量大幅提升，但性能开销更高。 |
| CLEAR_TYPE_GRID_FIT | 每个字符使用带有提示的 ClearType 字形位图绘制。最高质量设置。用于利用 ClearType 字体特性。 |
| SINGLE_BIT_PER_PIXEL | 每个字符使用字形位图绘制。未使用提示。 |
| SINGLE_BIT_PER_PIXEL_GRID_FIT | 每个字符使用字形位图绘制。使用提示来改善字符在笔画和曲线上的外观。 |
| SYSTEM_DEFAULT | 每个字符使用字形位图绘制，并使用系统默认的渲染提示。文本将按照用户在系统中选择的字体平滑设置进行绘制。 |
