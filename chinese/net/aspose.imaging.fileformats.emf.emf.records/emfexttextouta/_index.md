---
title: "类 EmfExtTextOutA"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtTextOutA 类。EMR_EXTTEXTOUTA 记录使用当前字体和文字颜色绘制 ASCII 文本字符串。"
type: docs
weight: 3770
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
## EmfExtTextOutA class

EMR_EXTTEXTOUTA 记录使用当前字体和文字颜色绘制 ASCII 文本字符串。

```csharp
public sealed class EmfExtTextOutA : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfExtTextOutA](emfexttextouta/#constructor)() | 初始化 `EmfExtTextOutA` 类的新实例。 |
| [EmfExtTextOutA](emfexttextouta/#constructor_1)(EmfRecord) | 初始化 `EmfExtTextOutA` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/aemrtext/) { get; set; } | 获取或设置一个 EmrText 对象（第 2.2.5 节），该对象指定 8 位 ASCII 字符的输出字符串、文本属性和间距值。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节）。该对象未使用，接收时必须忽略。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/exscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定沿 X 轴的比例因子，用于将页面空间单位转换为 0.01mm 单位。仅当 iGraphicsMode 指定的图形模式为 GM_COMPATIBLE 时才应使用此值。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/eyscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定沿 Y 轴的比例因子，用于将页面空间单位转换为 0.01mm 单位。仅当 iGraphicsMode 指定的图形模式为 GM_COMPATIBLE 时才应使用此值。 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/igraphicsmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定来自 GraphicsMode 枚举（第 2.1.16 节）的图形模式。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


