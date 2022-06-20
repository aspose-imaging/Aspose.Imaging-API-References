---
title: EmfSmallTextOut
second_title: Aspose.Imaging for .NET API 参考
description: EMR_SMALLTEXTOUT 记录输出一个字符串
type: docs
weight: 4570
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
## EmfSmallTextOut class

EMR_SMALLTEXTOUT 记录输出一个字符串。

```csharp
public sealed class EmfSmallTextOut : EmfDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfSmallTextOut](emfsmalltextout)(EmfRecord) | 初始化[`EmfSmallTextOut`](../emfsmalltextout)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/bounds) { get; set; } | 获取或设置一个可选的 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象 指定边界矩形以设备为单位。 |
| [CChars](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/cchars) { get; set; } | 获取或设置一个 32 位无符号整数，指定 字符串中 16 位字符的数量。该字符串不是以空值结尾的。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/exscale) { get; set; } | 获取或设置一个 32 位浮点值，该值指定在 x 方向上缩放文本的程度。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/eyscale) { get; set; } | 获取或设置一个 32 位浮点值，该值指定在 y 方向上缩放文本的程度。 |
| [FuOptions](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/fuoptions) { get; set; } | 获取或设置一个 32 位无符号整数，指定要使用的文本输出选项。这些 选项由 ExtTextOutOptions 枚举（第 2.1.11 节）中的一个或一组值指定。 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/igraphicsmode) { get; set; } | 从 GraphicsMode 枚举（第 2.1.16 节）获取或设置指定图形模式的 32 位无符号整数。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [TextString](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/textstring) { get; set; } | 获取或设置包含要绘制的文本字符串的可变长度字符串，格式为 8 位或 16 位字符代码，根据 fuOptions 字段的值。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |
| [X](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/x) { get; set; } | 获取或设置一个 32 位有符号整数，指定放置字符串的 x 坐标。 |
| [Y](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/y) { get; set; } | 获取或设置一个 32 位有符号整数，指定放置字符串的 y 坐标。 |

### 评论

如果在 fuOptions 字段中设置了 ETO_SMALL_CHARS，则 TextString 包含:::47 的 8 位代码:::字符，源自 16 位 Unicode UTF16-LE 字符代码的低字节，其中 高字节假定为 0。 如果设置了 ETO_NO_RECT在 fuOptions 字段中，Bounds 字段不包含在记录中。

### 也可以看看

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->