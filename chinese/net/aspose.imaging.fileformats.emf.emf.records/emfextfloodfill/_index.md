---
title: "类 EmfExtFloodFill"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtFloodFill 类。EMR_EXTFLOODFILL 记录使用当前画刷填充显示表面的区域。"
type: docs
weight: 3750
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
## EmfExtFloodFill class

EMR_EXTFLOODFILL 记录使用当前画刷填充显示表面的区域。

```csharp
public sealed class EmfExtFloodFill : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfExtFloodFill](emfextfloodfill/)(EmfRecord) | 初始化 `EmfExtFloodFill` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Argb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/argb32color/) { get; set; } | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象与 FloodFillMode 一起用于确定填充区域。 |
| [FloodFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/floodfillmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何使用 Color 值来确定洪水填充操作的区域。该值必须位于 FloodFill 枚举（第 2.1.13 节）中。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Start](../../aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/start/) { get; set; } | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定填充开始的坐标（逻辑单位）。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


