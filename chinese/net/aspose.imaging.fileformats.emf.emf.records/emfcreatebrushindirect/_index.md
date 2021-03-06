---
title: EmfCreateBrushIndirect
second_title: Aspose.Imaging for .NET API 参考
description: EMR_CREATEBRUSHINDIRECT 记录定义了图形操作的逻辑画笔
type: docs
weight: 3460
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
## EmfCreateBrushIndirect class

EMR_CREATEBRUSHINDIRECT 记录定义了图形操作的逻辑画笔。

此记录定义的逻辑画笔对象可以通过:::选择到播放设备上下文中47:::EMR_SELECTOBJECT 记录（第 2.3.8.5 节），它指定在 后续图形操作中使用的逻辑画笔。

```csharp
public sealed class EmfCreateBrushIndirect : EmfObjectCreationRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfCreateBrushIndirect](emfcreatebrushindirect#constructor)() | 初始化[`EmfCreateBrushIndirect`](../emfcreatebrushindirect)类的新实例。 |
| [EmfCreateBrushIndirect](emfcreatebrushindirect#constructor_1)(EmfRecord) | 初始化[`EmfCreateBrushIndirect`](../emfcreatebrushindirect)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/ihbrush) { get; set; } | 获取或设置一个 32 位无符号整数，指定 EMF 对象表中逻辑画笔对象 的索引（第 3.1.1.1 节）。必须保存该索引，以便该对象可以被 重用或修改。 |
| [LogBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/logbrush) { get; set; } | 获取或设置一个 LogBrushEx 对象（第 2.2.12 节），它指定逻辑画笔的样式、颜色和 模式。此对象中的 BrushStyle 字段必须是 BS_SOLID、 BS_HATCHED 或 BS_NULL。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 也可以看看

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
