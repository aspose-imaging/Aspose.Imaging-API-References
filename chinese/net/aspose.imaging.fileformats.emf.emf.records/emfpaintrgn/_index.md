---
title: "类 EmfPaintRgn"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPaintRgn 类。EMR_PAINTRGN 记录通过使用当前在回放设备上下文中选中的画笔来绘制指定的区域。"
type: docs
weight: 4010
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
## EmfPaintRgn class

EMR_PAINTRGN 记录使用当前在回放设备上下文中选中的画刷绘制指定区域。

```csharp
public sealed class EmfPaintRgn : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPaintRgn](emfpaintrgn/#constructor)() | 初始化 `EmfPaintRgn` 类的新实例。 |
| [EmfPaintRgn](emfpaintrgn/#constructor_1)(EmfRecord) | 初始化 `EmfPaintRgn` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/bounds/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，用于指定边界矩形。 |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/rgndata/) { get; set; } | 获取或设置一个长度为 RgnDataSize 的字节数组，指定以逻辑单位表示的 RegionData（第 2.2.24 节）对象。 |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/rgndatasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定区域数据的大小（字节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


