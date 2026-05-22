---
title: "类 EmfExtTextOutW"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtTextOutW 类。EMR_EXTTEXTOUTW 记录使用当前字体和文本颜色绘制 ASCII 文本字符串"
type: docs
weight: 3780
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
## EmfExtTextOutW class

EMR_EXTTEXTOUTW 记录使用当前字体和文字颜色绘制 ASCII 文本字符串。

```csharp
public sealed class EmfExtTextOutW : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfExtTextOutW](emfexttextoutw/#constructor)() | 初始化 `EmfExtTextOutW` 类的新实例。 |
| [EmfExtTextOutW](emfexttextoutw/#constructor_1)(EmfRecord) | 初始化 `EmfExtTextOutW` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节）。该对象未使用，接收时必须忽略。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/exscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定沿 X 轴的比例因子，用于将页面空间单位转换为 0.01mm 单位。仅当 iGraphicsMode 指定的图形模式为 GM_COMPATIBLE 时才应使用此值。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/eyscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定沿 Y 轴的比例因子，用于将页面空间单位转换为 0.01mm 单位。仅当 iGraphicsMode 指定的图形模式为 GM_COMPATIBLE 时才应使用此值。 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/igraphicsmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定来自 GraphicsMode 枚举（第 2.1.16 节）的图形模式。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/wemrtext/) { get; set; } | 获取或设置一个 EmrText 对象（第 2.2.5 节），该对象指定以 16 位 Unicode UTF16-LE 字符表示的输出字符串，并包含文本属性和间距值。 |

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


