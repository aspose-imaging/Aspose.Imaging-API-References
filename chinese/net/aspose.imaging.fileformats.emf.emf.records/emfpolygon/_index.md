---
title: "类 EmfPolygon"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolygon 类。EMR_POLYGON 记录指定一个由两个或多个通过直线连接的顶点组成的多边形"
type: docs
weight: 4200
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---
## EmfPolygon class

EMR_POLYGON 记录指定由两个或更多顶点通过直线连接组成的多边形。

```csharp
public sealed class EmfPolygon : EmfPolyShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPolygon](emfpolygon/#constructor)() | 初始化 `EmfPolygon` 类的新实例。 |
| [EmfPolygon](emfpolygon/#constructor_1)(EmfRecord) | 初始化 `EmfPolygon` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolyshape/apoints/) { get; set; } | 获取或设置 WMF PointL 对象数组（[MS-WMF] 第 2.2.2.15 节），该数组以逻辑单位指定点数据。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位指定边界矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

多边形应使用当前笔进行描边，并使用当前画刷和多边形填充模式进行填充。多边形应通过从最后一个顶点绘制到第一个顶点的线自动闭合。

### 另请参见

* class [EmfPolyShape](../emfpolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


