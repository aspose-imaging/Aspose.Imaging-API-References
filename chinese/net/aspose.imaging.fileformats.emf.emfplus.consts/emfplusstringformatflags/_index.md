---
title: "枚举 EmfPlusStringFormatFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusStringFormatFlags 枚举。StringFormat 标志指定图形文本布局的选项，包括方向、裁剪和字体处理。这些标志可以组合以指定多个选项。"
type: docs
weight: 5200
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
## EmfPlusStringFormatFlags enumeration

StringFormat 标志指定了图形文本布局的选项，包括方向、剪裁和字体处理。这些标志可以组合以指定多个选项。

```csharp
[Flags]
public enum EmfPlusStringFormatFlags : uint
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| StringFormatDirectionRightToLeft | `1` | 如果设置，则字符串的阅读顺序应为从右到左。对于水平文本，这意味着字符从右向左读取。对于垂直文本，这意味着列从右向左读取。如果清除，则水平或垂直文本应从左到右读取。 |
| StringFormatDirectionVertical | `2` | 如果设置，则文本的各行应在显示设备上垂直绘制。如果清除，则各行应水平绘制，每一新行位于前一行下方。 |
| StringFormatNoFitBlackBox | `4` | 如果设置，则字符的部分必须允许超出文本布局矩形。如果清除，则超出文本布局矩形边界的字符必须重新定位以避免超出。例如，斜体的\"f\"就是可能有超出部分的字符示例。 |
| StringFormatDisplayFormatControl | `20` | 如果设置，则控制字符应在输出中显示为相应的 Unicode 字形。 |
| StringFormatNoFontFallback | `400` | 如果设置，则应为不受请求字体支持的字符使用备用字体。如果清除，则缺失于请求字体的字符应显示为\"字体缺失\"字符，可能表现为一个空方框。 |
| StringFormatMeasureTrailingSpaces | `800` | 如果设置，则每行末尾的空格必须计入字符串长度的测量。如果清除，则每行末尾的空格必须从字符串长度的测量中排除。 |
| StringFormatNoWrap | `1000` | 如果设置，则超出文本布局矩形末端的字符串不得换行到下一行。如果清除，则超出文本布局矩形末端的字符串必须在矩形内的最后一个单词边界处断开，剩余部分必须换行到下一行。 |
| StringFormatLineLimit | `2000` | 如果设置，则整行文本应输出且不应被字符串的布局矩形裁剪。如果清除，则文本布局应继续，直到所有行都输出，或直到因裁剪导致额外的行不可见。此标志可用于禁止或允许文本行被非行高倍数的布局矩形部分遮挡。要使所有文本可见，布局矩形的高度至少应等于一行的高度。 |
| StringFormatNoClip | `4000` | 如果设置，则超出字符串布局矩形的文本应允许显示。如果清除，则超出布局矩形的所有文本应被裁剪。 |
| StringFormatBypassGdi | `80000000` | 此标志可用于指定用于渲染文本的实现特定过程。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


