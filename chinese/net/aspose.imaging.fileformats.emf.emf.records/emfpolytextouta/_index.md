---
title: "类 EmfPolyTextOutA"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyTextOutA 类。EMR_POLYTEXTOUTA 记录使用当前字体和文字颜色绘制一个或多个 ASCII 文本字符串。"
type: docs
weight: 4180
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
## EmfPolyTextOutA class

该 EMR_POLYTEXTOUTA 记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串。

```csharp
public sealed class EmfPolyTextOutA : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPolyTextOutA](emfpolytextouta/#constructor)() | 初始化 `EmfPolyTextOutA` 类的新实例。 |
| [EmfPolyTextOutA](emfpolytextouta/#constructor_1)(EmfRecord) | 初始化 `EmfPolyTextOutA` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/aemrtext/) { get; set; } | 获取或设置一个 EmrText 对象数组（第 2.2.5 节），该数组指定以 8 位 ASCII 字符表示的输出字符串、文本属性和间距值。EmrText 对象的数量由 cStrings 指定。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定设备单位中的边界矩形。 |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/exscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定在图形模式为 GM_COMPATIBLE 时，从页面单位到 .01mm 单位的 X 缩放比例。 |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/eyscale/) { get; set; } | 获取或设置一个 32 位浮点值，指定在图形模式为 GM_COMPATIBLE 时，从页面单位到 .01mm 单位的 Y 缩放比例。 |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/igraphicsmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定当前图形模式，取自 GraphicsMode 枚举（第 2.1.16 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

用于输出的字体和文字颜色由播放设备上下文当前状态中的属性指定。EMR_POLYTEXTOUTA 应使用一系列 EMR_EXTTEXTOUTW 记录（第 2.3.5.7 节）进行仿真，每个字符串对应一条记录。这要求将每个 EmrText 对象中的 ASCII 文本字符串转换为 Unicode UTF16-LE 编码。

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


