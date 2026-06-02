---
title: "类 EmfPolylineTo16"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolylineTo16 类。EMR_POLYLINETO16 记录基于当前位置信息指定一条或多条直线。使用当前画笔，从当前位置信息绘制一条线到 aPoints 字段指定的第一个点。对于每条后续直线，绘制从前一条线的结束点到 aPoints 指定的下一个点。"
type: docs
weight: 4250
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---
## EmfPolylineTo16 class

EMR_POLYLINETO16 记录指定基于当前位置信息的一个或多个直线。使用当前画笔从当前位置信息绘制到 aPoints 字段指定的第一个点。对于每条后续直线，从前一条线的结束点绘制到 aPoints 指定的下一个点。

```csharp
public sealed class EmfPolylineTo16 : EmfPolyShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPolylineTo16](emfpolylineto16/#constructor)() | 初始化 `EmfPolylineTo16` 类的新实例。 |
| [EmfPolylineTo16](emfpolylineto16/#constructor_1)(EmfRecord) | 初始化 `EmfPolylineTo16` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolyshape/apoints/) { get; set; } | 获取或设置 WMF PointL 对象数组（[MS-WMF] 第 2.2.2.15 节），该数组以逻辑单位指定点数据。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位指定边界矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfPolyShape](../emfpolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


