---
title: "类 EmfPolyPolygon"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyPolygon 类。EMR_POLYPOLYGON 记录指定一系列封闭的多边形"
type: docs
weight: 4130
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---
## EmfPolyPolygon class

EMR_POLYPOLYGON 记录指定一系列闭合多边形。

```csharp
public sealed class EmfPolyPolygon : EmfPolyPolyShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPolyPolygon](emfpolypolygon/#constructor)() | 初始化 `EmfPolyPolygon` 类的新实例。 |
| [EmfPolyPolygon](emfpolypolygon/#constructor_1)(EmfRecord) | 初始化 `EmfPolyPolygon` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolyshape/apoints/) { get; set; } | 获取或设置一个 WMF PointS 对象数组，定义于 [MS-WMF] 第 2.2.2.16 节，指定点的数组。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位指定边界矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

每个多边形应使用当前笔进行描边，并使用当前画刷和在回放设备上下文中定义的多边形填充模式进行填充。此记录定义的多边形可以重叠。

### 另请参见

* class [EmfPolyPolyShape](../emfpolypolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


