---
title: "类 EmfText"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfText 类。EmrText 对象包含文本输出的值。"
type: docs
weight: 3250
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---
## EmfText class

EmrText 对象包含文本输出的值。

```csharp
public sealed class EmfText : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfText](emftext/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Chars](../../aspose.imaging.fileformats.emf.emf.objects/emftext/chars/) { get; set; } | 获取或设置一个 32 位无符号整数，指定字符串中的字符数 |
| [DxBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/dxbuffer/) { get; set; } | 获取或设置可选的字符间距缓冲区 UndefinedSpace2（变量）：可选的未使用字节数。OutputDx 字段不需要紧跟在此结构的前一部分之后。OutputDx（变量）：一个 32 位无符号整数数组，指定相邻字符单元原点之间的输出间距（逻辑单位）。该字段的位置由 offDx 的字节值（相对于记录起始）指定。如果已定义间距，则该字段包含与输出字符串中字符数量相同的值。如果 EmrText 对象的 Options 字段包含 ETO_PDY 标志，则此缓冲区包含的值数量是输出字符串字符数的两倍，每个字符对应一个水平偏移和一个垂直偏移，按此顺序。如果指定了 ETO_RTLREADING，字符将从右向左排列，而不是从左向右。没有其他选项会影响此字段的解释。 |
| [GlyphIndexBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/glyphindexbuffer/) { get; set; } | 获取或设置可选的字形索引缓冲区。如果 options 含有 ETO_GLYPH_INDEX 标志，则输出文本字符串中的字符代码实际上是 TrueType 字体中字符字形的索引（参见 2.1.11 ExtTextOutOptions 枚举）。字形索引是特定于字体的，因此在回放时显示正确字符，所使用的字体必须与生成索引时使用的字体完全相同。 |
| [Options](../../aspose.imaging.fileformats.emf.emf.objects/emftext/options/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何使用 Rectangle 字段中指定的矩形。此字段可以是多个 ExtTextOutOptions 枚举（第 2.1.11 节）值的组合。 |
| [Rectangle](../../aspose.imaging.fileformats.emf.emf.objects/emftext/rectangle/) { get; set; } | 获取或设置一个可选的 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位定义裁剪和/或不透明矩形。此矩形会应用于包含记录执行的文本输出。 |
| [Reference](../../aspose.imaging.fileformats.emf.emf.objects/emftext/reference/) { get; set; } | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定用于定位字符串的参考点坐标。参考点由最近的 EMR_SETTEXTALIGN 记录（第 2.3.11.25 节）定义。如果未设置此记录，默认对齐方式为 TA_LEFT、TA_TOP。 |
| [StringBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/stringbuffer/) { get; set; } | 获取或设置字符字符串缓冲区 UndefinedSpace1（变量）：可选的未使用字节数。OutputString 字段不需要紧跟在此结构的前一部分之后。OutputString（变量）：一个字符数组，指定要输出的字符串。该字段的位置由 offString 的字节值（相对于记录起始）指定。字符数量由 Chars 的值指定。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


