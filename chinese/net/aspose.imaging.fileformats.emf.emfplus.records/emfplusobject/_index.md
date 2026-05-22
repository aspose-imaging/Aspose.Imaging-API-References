---
title: "类 EmfPlusObject"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusObject 类。EmfPlusObject 记录指定用于图形操作的对象。对象定义可以跨多个记录，这由 Flags 字段的值指示。"
type: docs
weight: 6280
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
## EmfPlusObject class

此 EmfPlusObject 记录指定用于图形操作的对象。对象定义可以跨多个记录，由 Flags 字段的值指示。

```csharp
public sealed class EmfPlusObject : EmfPlusObjectRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusObject](emfplusobject/)(EmfPlusRecord) | 初始化 `EmfPlusObject` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [IsContinuable](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/iscontinuable/) { get; set; } | 获取或设置一个值，指示此实例是否可继续。表示对象定义在下一个 EmfPlusObject 记录中继续。此标志在定义对象的最终记录中永不设置。 |
| [ObjectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectdata/) { get; set; } | 获取或设置一个字节数组，包含 Flags 字段中指定的对象类型的数据。数据的内容和格式可能因对象类型而异。有关更多信息，请参阅第 2.2.1 节中的各个对象定义。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectid/) { get; set; } | 获取或设置对象标识符。该索引位于 EMF+ 对象表中，用于关联此记录创建的对象。该值必须在 0 到 63（含）之间。 |
| [ObjectType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objecttype/) { get; set; } | 获取或设置对象的类型。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [TotalObjectSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/totalobjectsize/) { get; set; } | 获取或设置对象的总大小。如果记录是可续的，当继续位被设置时，此字段将出现。可续对象具有多个 EMF+ 记录，起始于 EmfPlusContineudObjectRecord。每个 EmfPlusContinuedObjectRecord 将包含一个 TotalObjectSize。读取了 TotalObjectSize 指定的字节数后，下一条 EMF+ 记录将不再视为该可续对象的一部分。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

## 备注

EmfPlusObject 记录是通用的；它用于所有类型的对象。特定对象类型的值包含在 ObjectData 字段中。管理图形对象的概念模型在《Managing Graphics Objects》（第 3.1.2 节）中有所描述。

### 另请参见

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


