---
title: EmfPolyTextOutA
second_title: Aspose.Imaging for .NET API 参考
description: EMR_POLYTEXTOUTA 记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串
type: docs
weight: 4060
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
## EmfPolyTextOutA class

EMR_POLYTEXTOUTA 记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串。

```csharp
public sealed class EmfPolyTextOutA : EmfDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPolyTextOutA](emfpolytextouta#constructor)() | 初始化[`EmfPolyTextOutA`](../emfpolytextouta)类. |
| [EmfPolyTextOutA](emfpolytextouta#constructor_1)(EmfRecord) | 初始化[`EmfPolyTextOutA`](../emfpolytextouta)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/aemrtext) { get; set; } | 获取或设置 EmrText 对象数组（第 2.2.5 节），这些对象以 8 位 ASCII 字符、文本属性和间距值指定输出 字符串。 EmrText 对象的数量由 cStrings. 指定 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/bounds) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），它以设备单位指定 边界矩形。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/exscale) { get; set; } | 获取或设置一个 32 位浮点值，如果图形模式为 GM_COMPATIBLE，则指定从页面单位到 .01mm 单位的 X 比例。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/eyscale) { get; set; } | 获取或设置一个 32 位浮点值，如果图形模式为 GM_COMPATIBLE，则指定从页面单位到 .01mm 单位的 Y 比例。 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/igraphicsmode) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定当前图形模式， 来自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 评论

用于输出的字体和文本颜色由 播放设备上下文的当前状态中的属性指定。 EMR_POLYTEXTOUTA 应该使用一系列 EMR_EXTTEXTOUTW 记录（第 2.3.5.7 节）模拟，每个字符串一个。这需要将每个 EmrText 对象中的 ASCII 文本字符串 转换为 Unicode UTF16-LE 编码。

### 也可以看看

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
