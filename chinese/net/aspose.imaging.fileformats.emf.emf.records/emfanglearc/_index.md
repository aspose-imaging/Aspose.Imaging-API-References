---
title: "类 EmfAngleArc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfAngleArc 类。EMR_ANGLEARC 记录指定弧线的线段。该线段从当前位置信息绘制到弧的起始点。弧沿具有给定半径和中心的圆的周边绘制。弧的长度由给定的起始角度和扫掠角度决定。"
type: docs
weight: 3300
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
## EmfAngleArc class

EMR_ANGLEARC 记录指定弧的线段。该线段从当前位置信息绘制到弧的起点。弧沿具有给定半径和中心的圆周绘制。弧的长度由给定的起始角度和扫掠角度决定。

```csharp
public sealed class EmfAngleArc : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfAngleArc](emfanglearc/#constructor)() | 初始化 `EmfAngleArc` 类的新实例。 |
| [EmfAngleArc](emfanglearc/#constructor_1)(EmfRecord) | 初始化 `EmfAngleArc` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Center](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/center/) { get; set; } | 获取或设置一个 64 位 WMF PointL 对象，该对象在 [MS-WMF] 第 2.2.2.15 节中指定，用于指示圆心的逻辑坐标。 |
| [Radius](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/radius/) { get; set; } | 获取或设置一个 32 位无符号整数，指定圆的半径（逻辑单位）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [StartAngle](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/startangle/) { get; set; } | 获取或设置一个 32 位浮点数，指定弧的起始角度（度）。 |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/sweepangle/) { get; set; } | 获取或设置一个 32 位浮点数，指定弧的扫掠角度（度）。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


