---
title: EmfPlusObject
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusObject 记录指定用于图形操作的对象对象定义 可以跨越多条记录由 Flags 字段的值表示
type: docs
weight: 6160
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
## EmfPlusObject class

EmfPlusObject 记录指定用于图形操作的对象。对象定义 可以跨越多条记录，由 Flags 字段的值表示。

```csharp
public sealed class EmfPlusObject : EmfPlusObjectRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusObject](emfplusobject)(EmfPlusRecord) | 初始化[`EmfPlusObject`](../emfplusobject)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在 RecordData 字段中定义 32 位对齐的 数据字节数跟随。这个数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | 获取或设置一个 16 位无符号整数，该整数包含有关如何执行 操作和结构的一些记录的信息记录。 |
| [IsContinuable](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/iscontinuable) { get; set; } | 获取或设置一个值，该值指示此实例是否可继续。 表示对象定义在下一个 EmfPlusObject 记录中继续。此标志永远不会在定义对象的最终记录中设置。 |
| [ObjectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectdata) { get; set; } | 获取或设置一个字节数组，其中包含 Flags 字段中指定的对象类型的数据。每种对象类型的数据内容和格式可能不同。有关更多信息，请参阅第 2.2.1 节中的 单个对象定义。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectid) { get; set; } | 获取或设置对象标识符。 EMF+ 对象表中与该记录创建的对象 关联的索引。该值必须是 0 到 63（含）。 |
| [ObjectType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objecttype) { get; set; } | 获取或设置对象的类型。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整条记录中的 32 位对齐字节数 ，包括 12 -byte 记录头和特定于记录的数据。 |
| [TotalObjectSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/totalobjectsize) { get; set; } | 获取或设置对象的总大小。 如果记录是可继续的，当设置了继续位时，该字段 将出现。连续对象有多个以 EmfPlusContineudObjectRecord 开头的 EMF+ 记录。每个 EmfPlusContinuedObjectRecord 将包含一个 TotalObjectSize。一旦读取了 TotalObjectSize 字节数，下一个 EMF+ 记录将不会被视为连续对象的一部分。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |

### 评论

EmfPlusObject 记录是通用的；它用于所有类型的对象。特定于 特定对象类型的值包含在 ObjectData 字段中。在管理图形对象（第 3.1.2 节）中描述了用于管理 图形对象的概念模型。

### 也可以看看

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->