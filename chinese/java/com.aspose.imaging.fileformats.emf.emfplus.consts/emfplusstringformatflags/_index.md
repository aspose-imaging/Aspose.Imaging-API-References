---
title: "EmfPlusStringFormatFlags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "StringFormat 标志指定图形文本布局的选项，包括方向、裁剪和字体处理。"
type: docs
weight: 50
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

StringFormat 标志指定图形文本布局的选项，包括方向、裁剪和字体处理。这些标志可以组合以指定多个选项。
## 字段

| 字段 | 描述 |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | 如果设置，则字符串的阅读顺序应为从右到左。 |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | 如果设置，则各行文本应在显示设备上垂直绘制。 |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | 如果设置，则必须允许字符的部分超出文本布局矩形。 |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | 如果设置，则控制字符应在输出中显示为相应的 Unicode 字形。 |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | 如果设置，则应为请求的字体不支持的字符使用替代字体。 |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | 如果设置，则必须将每行末尾的空格计入字符串长度的测量。 |
| [StringFormatNoWrap](#StringFormatNoWrap) | 如果设置，则超出文本布局矩形末端的字符串不得换行到下一行。 |
| [StringFormatLineLimit](#StringFormatLineLimit) | 如果设置，则应输出完整的文本行，并且不应被字符串的布局矩形裁剪。 |
| [StringFormatNoClip](#StringFormatNoClip) | 如果设置，则应允许显示超出字符串布局矩形的文本。 |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | 此标志可用于指定特定实现的文本渲染过程。 |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


如果设置，则字符串的阅读顺序应为从右到左。对于水平文本，这意味着字符从右向左读取。对于垂直文本，这意味着列从右向左读取。如果未设置，则水平或垂直文本应从左向右读取。

--------------------

图形文本布局由 [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat) 对象指定

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


如果设置，则各行文本应在显示设备上垂直绘制。如果未设置，则各行文本应水平绘制，每行新行位于前一行下方。

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


如果设置，则必须允许字符的部分超出文本布局矩形。如果未设置，则必须重新定位超出文本布局矩形边界的字符以避免超出。斜体的"f"就是可能具有超出部分的字符示例。

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


如果设置，则控制字符应在输出中显示为相应的 Unicode 字形。

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


如果设置，则应为请求的字体不支持的字符使用替代字体。如果未设置，则缺失于请求字体的字符应显示为“缺少字体”字符，该字符可能是一个空方块。

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


如果设置，则必须将每行末尾的空格计入字符串长度的测量。如果未设置，则必须将每行末尾的空格排除在字符串长度的测量之外。

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


如果设置，则超出文本布局矩形末端的字符串不得换行到下一行。如果未设置，则超出文本布局矩形末端的字符串必须在边界矩形内的最后一个单词边界处断开，剩余部分必须换行到下一行。

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


如果设置，则应输出完整的文本行，并且不应被字符串的布局矩形裁剪。如果未设置，则文本布局应持续进行，直至所有行输出完毕，或因裁剪导致后续行不可见。此标志可用于禁止或允许文本行被非行高整数倍的布局矩形部分遮挡。要使所有文本可见，布局矩形的高度至少应等于一行的高度。

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


如果设置，则应允许显示超出字符串布局矩形的文本。如果未设置，则应裁剪所有超出布局矩形的文本。

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


此标志可用于指定特定实现的文本渲染过程。

