---
title: "类 EmfSmallTextOut"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSmallTextOut 类。EMR_SMALLTEXTOUT 记录输出一个字符串。"
type: docs
weight: 4690
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
## EmfSmallTextOut class

EMR_SMALLTEXTOUT 记录输出字符串。

```csharp
public sealed class EmfSmallTextOut : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSmallTextOut](emfsmalltextout/)(EmfRecord) | 初始化 `EmfSmallTextOut` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/bounds/) { get; set; } | 获取或设置一个可选的 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定设备单位中的边界矩形。 |
| [CChars](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/cchars/) { get; set; } | 获取或设置一个 32 位无符号整数，指定字符串中 16 位字符的数量。该字符串未以空字符终止。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/exscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定文本在 x 方向的缩放比例。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/eyscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定文本在 y 方向的缩放比例。 |
| [FuOptions](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/fuoptions/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要使用的文本输出选项。这些选项由 ExtTextOutOptions 枚举（第 2.1.11 节）中的一个或多个值组合而成。 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/igraphicsmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [TextString](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/textstring/) { get; set; } | 获取或设置一个可变长度字符串，包含要绘制的文本字符串，使用 8 位或 16 位字符码，取决于 fuOptions 字段的值。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [X](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/x/) { get; set; } | 获取或设置一个 32 位有符号整数，指定放置字符串的 x 坐标。 |
| [Y](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/y/) { get; set; } | 获取或设置一个 32 位有符号整数，指定放置字符串的 y 坐标。 |

## 备注

如果在 fuOptions 字段中设置了 ETO_SMALL_CHARS，则 TextString 包含字符的 8 位代码，这些代码来源于 16 位 Unicode UTF16-LE 字符代码的低字节，其中高字节假定为 0。如果在 fuOptions 字段中设置了 ETO_NO_RECT，则记录中不包含 Bounds 字段。

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


