---
title: "EmfPlusStringFormatFlags 枚举"
type: docs
weight: 410
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

该 StringFormat 标志指定了图形文本布局的选项，包括方向、裁剪和字体处理。这些标志可以组合以指定多个选项。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | 此标志可用于指定实现特定的文本呈现过程。 |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | 如果设置，则字符串的阅读顺序应为从右到左。对于水平文本，这意味着字符从右向左读取。对于垂直文本，这意味着列从右向左读取。<br/>            如果清除，则水平或垂直文本应从左向右读取。 |
| STRING_FORMAT_DIRECTION_VERTICAL | 如果设置，则应在显示设备上垂直绘制文本的各行。<br/>            如果清除，则应水平绘制文本的各行，每一新行位于前一行下方。 |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | 如果设置，则控制字符应在输出中显示为相应的 Unicode 字形。 |
| STRING_FORMAT_LINE_LIMIT | 如果设置，则应输出整行文本，并且不应被字符串的布局矩形裁剪。<br/>            如果清除，则文本布局应继续，直到所有行都输出，或直到由于裁剪导致额外的行不可见。<br/>            此标志可用于拒绝或允许文本行被布局矩形（其高度不是行高的整数倍）部分遮挡。要使所有文本可见，布局矩形的高度至少应等于一行的高度。 |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | 如果设置，则每行末尾的空格必须计入字符串长度的测量。<br/>            如果未设置，则每行末尾的空格必须从字符串长度的测量中排除。 |
| STRING_FORMAT_NO_CLIP | 如果设置，则超出字符串布局矩形的文本应允许显示。<br/>            如果未设置，则所有超出布局矩形的文本应被裁剪。 |
| STRING_FORMAT_NO_FIT_BLACK_BOX | 如果设置，则字符的部分必须允许超出文本布局矩形。<br/>            如果未设置，则超出文本布局矩形边界的字符必须重新定位以避免超出。<br/>            斜体的“f”就是可能具有超出部分的字符示例。 |
| STRING_FORMAT_NO_FONT_FALLBACK | 如果设置，则应为请求的字体不支持的字符使用替代字体。<br/>            如果未设置，则请求的字体中缺失的字符应显示为“缺少字体”字符，可能是一个空方框。 |
| STRING_FORMAT_NO_WRAP | 如果设置，则超出文本布局矩形末端的字符串不得换行到下一行。<br/>            如果未设置，则超出文本布局矩形末端的字符串必须在边界矩形内的最后一个单词边界处断开，剩余部分必须换行到下一行。 |
