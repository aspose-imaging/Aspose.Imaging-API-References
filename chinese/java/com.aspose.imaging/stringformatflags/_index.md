---
title: "StringFormatFlags"
second_title: "Aspose.Imaging for Java API 参考"
description: "指定文本字符串的显示和布局信息。"
type: docs
weight: 113
url: /zh/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

指定文本字符串的显示和布局信息。
## 字段

| 字段 | 描述 |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | 文本从右向左显示。 |
| [DirectionVertical](#DirectionVertical) | 文本垂直对齐。 |
| [FitBlackBox](#FitBlackBox) | 允许字符的部分超出字符串的布局矩形。 |
| [DisplayFormatControl](#DisplayFormatControl) | 控制字符（例如从左到右标记）在输出中以代表性字形显示。 |
| [NoFontFallback](#NoFontFallback) | 已禁用对请求字体不支持的字符回退到替代字体。 |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | 包括每行末尾的尾随空格。 |
| [NoWrap](#NoWrap) | 在矩形内格式化时，行间的文本换行被禁用。 |
| [LineLimit](#LineLimit) | 仅在格式化矩形中布局完整行。 |
| [NoClip](#NoClip) | 允许字形的超出部分以及未换行的文本超出格式化矩形显示。 |
| [ExactAlignment](#ExactAlignment) | 精确对齐，正确的填充 GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


文本从右向左显示。

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


文本垂直对齐。

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


允许字符的部分超出字符串的布局矩形。默认情况下，字符会重新定位以避免任何超出。

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


控制字符（例如从左到右标记）在输出中以代表性字形显示。

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


已禁用对请求字体不支持的字符回退到替代字体。任何缺失的字符将使用字体的缺失字形显示，通常是一个空方框。

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


包括每行末尾的尾随空格。默认情况下，MeasureString 方法返回的边界矩形不包括每行末尾的空格。设置此标志以在测量中包含该空格。

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


在矩形内格式化时，行间的文本换行被禁用。当传入点而不是矩形，或指定的矩形行长度为零时，此标志会隐含生效。

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


仅在格式化矩形中布局完整行。默认情况下，布局会持续到文本结束，或直到由于裁剪而没有更多行可见，以先到者为准。请注意，默认设置允许最后一行被格式化矩形部分遮挡（如果该矩形的高度不是行高的整数倍）。为确保只显示完整行，请指定此值，并确保提供的格式化矩形高度至少与一行的高度相同。

### NoClip {#NoClip}
```
public static final int NoClip
```


允许字形的超出部分以及未换行的文本超出格式化矩形显示。默认情况下，所有超出格式化矩形的文本和字形部分都会被裁剪。

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


精确对齐，正确的填充 GDI+

