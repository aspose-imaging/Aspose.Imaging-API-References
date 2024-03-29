---
title: EmfPolygon
second_title: Aspose.Imaging for .NET API 参考
description: EMR_POLYGON 记录指定了一个多边形该多边形由两个或多个由 直线连接的顶点组成
type: docs
weight: 4080
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---
## EmfPolygon class

EMR_POLYGON 记录指定了一个多边形，该多边形由两个或多个由 直线连接的顶点组成。

```csharp
public sealed class EmfPolygon : EmfDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPolygon](emfpolygon#constructor)() | 初始化[`EmfPolygon`](../emfpolygon)类. |
| [EmfPolygon](emfpolygon#constructor_1)(EmfRecord) | 初始化[`EmfPolygon`](../emfpolygon)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon/apoints) { get; set; } | 获取或设置 WMF PointL 对象的 Count 长度数组（[MS-WMF] 第 2.2.2.15 节） 以逻辑单位指定多边形的顶点。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon/bounds) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），它指定 以设备为单位的边界矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 评论

多边形应该使用当前笔勾勒出轮廓并使用当前画笔和 多边形填充模式进行填充。应该通过从最后一个 顶点到第一个 顶点绘制一条线来自动关闭多边形

### 也可以看看

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
