---
title: EmfExtTextOutA
second_title: Aspose.Imaging for .NET API 参考
description: EMR_EXTTEXTOUTA 记录使用当前字体和文本颜色绘制一个 ASCII 文本字符串
type: docs
weight: 3670
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
## EmfExtTextOutA class

EMR_EXTTEXTOUTA 记录使用当前字体和文本颜色绘制一个 ASCII 文本字符串。

```csharp
public sealed class EmfExtTextOutA : EmfDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfExtTextOutA](emfexttextouta#constructor)() | 初始化[`EmfExtTextOutA`](../emfexttextouta)类. |
| [EmfExtTextOutA](emfexttextouta#constructor_1)(EmfRecord) | 初始化[`EmfExtTextOutA`](../emfexttextouta)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/aemrtext) { get; set; } | 获取或设置一个 EmrText 对象（第 2.2.5 节），该对象指定 8 位 ASCII 字符、文本属性和间距值的输出字符串。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/bounds) { get; set; } | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节）。它没有被使用并且 在收据时必须被忽略。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/exscale) { get; set; } | 获取或设置一个 32 位浮点值，该值指定沿 X 轴应用的比例因子，以将页面空间单位转换为 0.01mm 单位。仅当 iGraphicsMode 指定的 图形模式为 GM_COMPATIBLE 时才应使用此选项。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/eyscale) { get; set; } | 获取或设置一个 32 位浮点值，该值指定沿 Y 轴应用的比例因子，以将页面空间单位转换为 0.01mm 单位。仅当 iGraphicsMode 指定的 图形模式为 GM_COMPATIBLE. 时才应使用此选项 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/igraphicsmode) { get; set; } | 获取或设置一个 32 位无符号整数，它从 GraphicsMode 枚举（第 2.1.16 节）中指定图形模式。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 也可以看看

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
