---
title: "类 EmfPlusStringFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusStringFormat 类。EmfPlusStringFormat 对象指定文本布局显示的操作以及语言标识。"
type: docs
weight: 5900
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

该 EmfPlusStringFormat 对象指定文本布局、显示操作和语言标识。

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage/) { get; set; } | 获取或设置一个 EmfPlusLanguageIdentifier 对象，指定字符串中数字使用的语言。例如，如果该字符串包含阿拉伯数字，则此字段必须包含指定阿拉伯语言的语言标识符。 |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution/) { get; set; } | 获取或设置一个 32 位无符号整数，指定根据区域设置或语言如何替换字符串中的数字。该值必须在 StringDigitSubstitution 枚举中定义 (section 2.1.1.30)。 |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset/) { get; set; } | 获取或设置一个 32 位浮点值，指定文本行起始位置与第一个制表位之间的空格数。 |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix/) { get; set; } | 获取或设置一个 32 位有符号整数，指定在遇到键盘快捷键前缀（即 & 符号）时对字符串执行的处理类型。基本上，此字段指定是否显示与文本相关的键盘快捷键前缀。该值必须在 HotkeyPrefix 枚举中定义 (section 2.1.1.14)。 |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language/) { get; set; } | 获取或设置一个 EmfPlusLanguageIdentifier 对象 (section 2.2.2.23)，指定字符串使用的语言。 |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin/) { get; set; } | 获取或设置一个 32 位浮点值，指定在字符串起始位置添加的空格长度。默认值为 1/6 英寸；对于排版字体，默认值为 0。 |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign/) { get; set; } | 获取或设置一个 32 位无符号整数，指定字符串在布局矩形中的垂直对齐方式。该值必须在 StringAlignment 枚举中定义。 |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount/) { get; set; } | 获取或设置一个 32 位有符号整数，指定 StringFormatData 字段中定义的 EmfPlusCharacterRange 对象的数量 (section 2.2.2.8)。 |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定在布局矩形中水平对齐字符串的方式。此值必须在 StringAlignment 枚举中定义（section 2.1.1.29）。 |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata/) { get; set; } | 获取或设置一个 EmfPlusStringFormatData 对象（section 2.2.2.44），用于指定可选的文本布局数据。 |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定文本布局选项，包括格式化、剪裁和字体处理。此值必须由 StringFormat 标志组成（section 2.1.2.8）。 |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount/) { get; set; } | 获取或设置一个 32 位有符号整数，用于指定在 StringFormatData 字段中定义的制表位数量。 |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking/) { get; set; } | 获取或设置一个 32 位浮点值，用于指定指定字符串中每个字符分配的水平空间与字符字体定义宽度的比例。该属性的较大值表示字符之间有充足的间距；小于 1 的值可能导致字符重叠。默认值为 1.03；对于排版字体，默认值为 1.00。 |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin/) { get; set; } | 获取或设置一个 32 位浮点值，用于指定字符串后保留的空格长度。默认值为 1/6 英寸；对于排版字体，默认值为 0。 |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming/) { get; set; } | 获取或设置指定如何修剪过大而无法容纳在布局矩形中的字符串的字符。此值必须在 StringTrimming 枚举中定义（section 2.1.1.31）。 |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | 获取或设置版本。 |

### 另请参见

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


