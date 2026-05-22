---
title: "类 EmfPolyTextOutW"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyTextOutW 类。EMR_POLYTEXTOUTW 记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。"
type: docs
weight: 4190
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
## EmfPolyTextOutW class

该 EMR_POLYTEXTOUTW 记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。

```csharp
public sealed class EmfPolyTextOutW : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPolyTextOutW](emfpolytextoutw/#constructor)() | 初始化 `EmfPolyTextOutW` 类的新实例。 |
| [EmfPolyTextOutW](emfpolytextoutw/#constructor_1)(EmfRecord) | 初始化 `EmfPolyTextOutW` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定设备单位中的边界矩形。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/exscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定在图形模式为 GM_COMPATIBLE 时，从页面单位到 .01mm 单位的 X 缩放比例。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/eyscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定在图形模式为 GM_COMPATIBLE 时，从页面单位到 .01mm 单位的 Y 缩放比例。 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/igraphicsmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定当前图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/wemrtext/) { get; set; } | 获取或设置一个 EmrText 对象数组（第 2.2.5 节），这些对象以 16 位 Unicode UTF16-LE 字符指定输出字符串，并包含文本属性和间距值。EmrText 对象的数量由 cStrings 指定。 |

## 备注

用于输出的字体和文本颜色由播放设备上下文当前状态中的属性指定。EMR_POLYTEXTOUTW 应该通过一系列 EMR_EXTTEXTOUTW 记录（第 2.3.5.7 节）进行仿真，每个字符串对应一条记录。

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


