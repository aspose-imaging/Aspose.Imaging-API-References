---
title: "类 EmfPolyPolyline"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyPolyline 类。EMR_POLYPOLYLINE 记录指定多个相连线段的系列。"
type: docs
weight: 4150
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/
---
## EmfPolyPolyline class

EMR_POLYPOLYLINE 记录指定多个相连线段的系列。

```csharp
public sealed class EmfPolyPolyline : EmfPolyPolyShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPolyPolyline](emfpolypolyline/#constructor)() | 初始化 `EmfPolyPolyline` 类的新实例。 |
| [EmfPolyPolyline](emfpolypolyline/#constructor_1)(EmfRecord) | 初始化 `EmfPolyPolyline` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolyshape/apoints/) { get; set; } | 获取或设置一个 WMF PointS 对象数组，定义于 [MS-WMF] 第 2.2.2.16 节，指定点的数组。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位指定边界矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

线段应使用当前笔进行绘制。由线段形成的图形不应填充。此记录不应使用或更新当前位置信息。

### 另请参见

* class [EmfPolyPolyShape](../emfpolypolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


