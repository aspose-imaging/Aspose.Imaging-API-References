---
title: "WmfTextAlignmentModeFlags 枚举"
type: docs
weight: 270
url: /zh/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---

TextAlignmentMode 标志指定参考点与边界<br/>                矩形之间的关系，用于文本对齐。这些标志可以组合以指定多个选项，但限制只能选择一个会改变回放设备<br/>                上下文中绘制位置的标志。<br/>                当字体具有水平默认基线时，执行水平文本对齐。

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfTextAlignmentModeFlags

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| BASELINE | 参考点必须位于文本的基线位置。 |
| BOTTOM | 参考点必须位于边界矩形的底部边缘。 |
| CENTER | 参考点必须水平对齐到边界矩形的中心。 |
| HORIZONTAL | 表示水平文本对齐集合（Left | Right | Center) |
| LEFT | 参考点必须位于边界矩形的左侧边缘。 |
| NOUPDATECP | 在回放设备上下文中，绘图位置在每次<br/>                文本输出调用后必须不被更新。必须将参考点传递给文本输出函数。 |
| RIGHT | 参考点必须位于边界矩形的右侧边缘。 |
| RTLREADING | 文本必须以从右到左的阅读顺序布局，而不是默认的从左到右顺序。此应<br/>                仅在回放设备上下文中定义的字体为希伯来语或阿拉伯语时应用。 |
| TOP | 参考点必须位于边界矩形的顶部边缘。 |
| UPDATECP | 在回放设备上下文中，绘图位置必须在每次文本<br/>                输出调用后更新。它必须用作参考点。 |
| VERTICAL | 表示垂直文本对齐集合（Top | Bottom | Baseline) |
