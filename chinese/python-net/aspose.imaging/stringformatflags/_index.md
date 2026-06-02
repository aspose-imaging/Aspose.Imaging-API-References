---
title: "StringFormatFlags 枚举"
type: docs
weight: 11220
url: /zh/python-net/aspose.imaging/stringformatflags/
---

指定文本字符串的显示和布局信息。

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormatFlags

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | 文本从右到左显示。 |
| DIRECTION_VERTICAL | 文本垂直对齐。 |
| DISPLAY_FORMAT_CONTROL | 控制字符（例如从左到右标记）在输出中显示为代表性的字形。 |
| EXACT_ALIGNMENT | 精确对齐，正确的 GDI+ 填充 |
| FIT_BLACK_BOX | 允许字符的部分超出字符串布局矩形。默认情况下，字符会重新定位以避免任何超出。 |
| LINE_LIMIT | 仅在格式矩形中布局完整的行。默认情况下，布局会持续到文本结束，或直到由于裁剪而没有更多行可见，以先到者为准。<br/>            请注意，默认设置允许最后一行被格式矩形部分遮挡，该矩形的高度不是行高的整数倍。为确保只显示完整的行，<br/>            请指定此值，并注意提供的格式矩形高度至少与一行的高度相同。 |
| MEASURE_TRAILING_SPACES | 包括每行末尾的尾随空格。默认情况下，MeasureString 方法返回的边界矩形会排除每行末尾的空格。设置此标志即可在测量时包含该空格。 |
| NO_CLIP | 允许显示超出格式矩形的字形悬挂部分和未换行的文本。默认情况下，所有超出格式矩形的文本和字形部分都会被裁剪。 |
| NO_FONT_FALLBACK | 已禁用对请求字体不支持的字符进行备用字体回退。任何缺失的字符将使用字体的缺失字形显示，通常表现为一个空方框。 |
| NO_WRAP | 在矩形内进行格式化时，行间换行被禁用。当传入点而非矩形，或指定的矩形行长度为零时，会隐含此标志。 |
