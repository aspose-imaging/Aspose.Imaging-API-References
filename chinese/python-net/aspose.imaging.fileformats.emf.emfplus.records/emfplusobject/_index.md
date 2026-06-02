---
title: "EmfPlusObject 类"
type: docs
weight: 330
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | 初始化一个新的 [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| is_continuable | bool | r/w | 获取或设置一个值，指示此实例是否可继续。<br/>            表示对象定义在下一个 EmfPlusObject 记录中继续。此标志在定义对象的最终记录中永不设置。 |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | 获取或设置一个字节数组，其中包含 Flags 字段中指定的对象类型的数据。每种对象类型的数据内容和格式可能不同。有关更多信息，请参阅第 2.2.1 节中的各个对象定义。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            与此记录创建的对象关联的 EMF+ 对象表中的索引。该值必须在 0 到 63（含）之间。 |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | 获取或设置对象的类型。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| total_object_size | int | r/w | 获取或设置对象的总大小。<br/>            如果记录是可继续的，并且继续位被设置，则此字段将出现。可继续的对象有多个以 EmfPlusContineudObjectRecord 开头的 EMF+ 记录。每个 EmfPlusContinuedObjectRecord 将包含一个 TotalObjectSize。读取了 TotalObjectSize 指定的字节数后，下一条 EMF+ 记录将不再视为该继续对象的一部分。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

初始化一个新的 [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

