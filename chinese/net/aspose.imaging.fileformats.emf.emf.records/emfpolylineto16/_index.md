---
title: EmfPolylineTo16
second_title: Aspose.Imaging for .NET API 参考
description: EMR_POLYLINETO16 记录根据当前位置指定一条或多条直线 使用 当前笔从当前位置到 aPoints 字段指定的第一个点绘制一条线对于每条附加线从前一条 线的终点到 aPoints 指定的下一个点进行绘制
type: docs
weight: 4130
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---
## EmfPolylineTo16 class

EMR_POLYLINETO16 记录根据当前位置指定一条或多条直线。 使用 当前笔从当前位置到 aPoints 字段指定的第一个点绘制一条线。对于每条附加线，从前一条 线的终点到 aPoints 指定的下一个点进行绘制。

```csharp
public sealed class EmfPolylineTo16 : EmfDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPolylineTo16](emfpolylineto16#constructor)() | 初始化[`EmfPolylineTo16`](../emfpolylineto16)类的新实例。 |
| [EmfPolylineTo16](emfpolylineto16#constructor_1)(EmfRecord) | 初始化[`EmfPolylineTo16`](../emfpolylineto16)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/apoints) { get; set; } | 获取或设置 WMF PointS 对象的 Count 长度数组，在 [MS-WMF] 2.2.2.16 节中指定，它指定了数组的点。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/bounds) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象，在 [MS-WMF] 第 2.2.2.19 节中指定， 指定边界矩形, 以设备为单位。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 也可以看看

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->