---
title: EmfPolyBezier
second_title: Aspose.Imaging for .NET API 参考
description: EMR_POLYBEZIER 记录指定一条或多条贝塞尔曲线
type: docs
weight: 3960
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
## EmfPolyBezier class

EMR_POLYBEZIER 记录指定一条或多条贝塞尔曲线。

```csharp
public sealed class EmfPolyBezier : EmfDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPolyBezier](emfpolybezier#constructor)() | 初始化[`EmfPolyBezier`](../emfpolybezier)类的新实例。 |
| [EmfPolyBezier](emfpolybezier#constructor_1)(EmfRecord) | 初始化[`EmfPolyBezier`](../emfpolybezier)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezier/apoints) { get; set; } | 获取或设置 WMF PointL 对象的 Count 长度数组（[MS-WMF] 第 2.2.2.15 节） 指定端点和控制贝塞尔曲线的点，以逻辑单位表示。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezier/bounds) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定 设备中的边界矩形单位。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 评论

三次贝塞尔曲线是使用 aPoints:::47 指定的端点和控制点定义的:::场地。第一条曲线是从第一个点到第四个点绘制的，使用第二个和第三个 点作为控制点。序列中的每条后续曲线恰好需要多三个点: 以前一条曲线的终点作为起点， 序列中接下来的两个点是控制点，第三个是终点。 应该使用当前笔绘制三次贝塞尔曲线

### 也可以看看

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
