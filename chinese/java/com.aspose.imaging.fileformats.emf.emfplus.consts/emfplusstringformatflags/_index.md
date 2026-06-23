---
title: "EmfPlusStringFormatFlags"
second_title: "Aspose.Imaging for Java API 参考"
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
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | 如果设置，则字符串的阅读顺序 SHOULD 为从右到左。 |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | 如果设置，则文本的各行 SHOULD 被垂直绘制在显示设备上。 |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | 如果设置，则字符的部分 MUST 允许超出文本布局矩形。 |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | 如果设置，则控制字符 SHOULD 以代表性的 Unicode 字形出现在输出中。 |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | 如果设置，则字符 SHOULD 使用备用字体来显示在请求的字体中不受支持的字符。 |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | 如果设置，则每行末尾的空格 MUST 包含在字符串长度的测量中。 |
| [StringFormatNoWrap](#StringFormatNoWrap) | 如果设置，则超出文本布局矩形末端的字符串 MUST NOT 换行到下一行。 |
| [StringFormatLineLimit](#StringFormatLineLimit) | 如果设置，则整行文本 SHOULD 输出，并且 SHOULD NOT 被字符串的布局矩形裁剪。 |
| [StringFormatNoClip](#StringFormatNoClip) | 如果设置，则超出字符串布局矩形的文本 SHOULD 被允许显示。 |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | 此标志 MAY 用于指定用于渲染文本的实现特定过程。 |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


如果设置，则字符串的阅读顺序 SHOULD 为从右到左。对于水平文本，这意味着字符从右向左读取。对于垂直文本，这意味着列从右向左读取。如果清除，则水平或垂直文本 SHOULD 从左向右读取。

--------------------

图形文本布局由 [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat) 对象指定。

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


如果设置，则文本的各行 SHOULD 垂直绘制在显示设备上。如果清除，则各行 SHOULD 水平绘制，每行在前一行下方。

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


如果设置，则字符的部分 MUST 允许超出文本布局矩形。如果清除，则超出文本布局矩形边界的字符 MUST 重新定位以避免超出。斜体的 "f" 是一个可能有超出部分的字符示例。

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


如果设置，则控制字符 SHOULD 以代表性的 Unicode 字形出现在输出中。

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


如果设置，则字符 SHOULD 使用备用字体来显示在请求的字体中不受支持的字符。如果清除，则请求的字体中缺失的字符 SHOULD 显示为 “字体缺失” 字符，可能是一个空方块。

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


如果设置，则每行末尾的空格必须计入字符串长度的测量。如果清除，则每行末尾的空格必须从字符串长度的测量中排除。

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


如果设置，则超出文本布局矩形末端的字符串不得换行到下一行。如果清除，则超出文本布局矩形末端的字符串必须在边界矩形内的最后一个单词边界处断开，剩余部分必须换行到下一行。

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


如果设置，则应输出整行文本，并且不应被字符串的布局矩形裁剪。如果清除，则文本布局应继续，直到所有行都输出，或直到由于裁剪导致额外的行不可见。此标志可用于禁止或允许文本行被非行高倍数的布局矩形部分遮挡。要使所有文本可见，布局矩形的高度至少应等于一行的高度。

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


如果设置，则应允许显示超出字符串布局矩形的文本。如果清除，则应裁剪所有超出布局矩形的文本。

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


此标志 MAY 用于指定用于渲染文本的实现特定过程。

