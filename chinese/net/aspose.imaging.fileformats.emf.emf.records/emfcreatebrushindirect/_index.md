---
title: "类 EmfCreateBrushIndirect"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect 类。EMR_CREATEBRUSHINDIRECT 记录定义了用于图形操作的逻辑画刷。"
type: docs
weight: 3560
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
## EmfCreateBrushIndirect class

EMR_CREATEBRUSHINDIRECT 记录定义用于图形操作的逻辑画刷。

此记录定义的逻辑画刷对象可以通过 EMR_SELECTOBJECT 记录（第 2.3.8.5 节）选入回放设备上下文，该记录指定在后续图形操作中使用的逻辑画刷。

```csharp
public sealed class EmfCreateBrushIndirect : EmfObjectCreationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCreateBrushIndirect](emfcreatebrushindirect/#constructor)() | 初始化 `EmfCreateBrushIndirect` 类的新实例。 |
| [EmfCreateBrushIndirect](emfcreatebrushindirect/#constructor_1)(EmfRecord) | 初始化 `EmfCreateBrushIndirect` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/ihbrush/) { get; set; } | 获取或设置一个 32 位无符号整数，指定逻辑画刷对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便能够重用或修改该对象。 |
| [LogBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/logbrush/) { get; set; } | 获取或设置一个 LogBrushEx 对象（第 2.2.12 节），指定逻辑画刷的样式、颜色和图案。该对象的 BrushStyle 字段必须为 BS_SOLID、BS_HATCHED 或 BS_NULL。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


