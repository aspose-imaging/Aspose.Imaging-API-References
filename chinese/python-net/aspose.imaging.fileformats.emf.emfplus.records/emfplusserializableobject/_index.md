---
title: "EmfPlusSerializableObject 类"
type: docs
weight: 440
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---

**Summary:** The EmfPlusSerializableObject record defines an image effects parameter block that has been<br/>            serialized into a data buffer.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSerializableObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSerializableObject(source)](#EmfPlusSerializableObject_source_1) | 初始化 [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 缓冲区 | System.Byte | r/w | 获取或设置一个由 BufferSize 字节组成的数组，包含序列化的图像效果<br/>            参数块，对应于 ObjectGUID 字段中的 GUID。此数组必须是<br/>            图像效果对象之一（第 2.2.3 节）。 |
| buffer_size | int | r/w | 获取或设置一个 32 位无符号整数，指定 32 位对齐的 Buffer 字段的字节大小。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| flags | int | r/w | 获取或设置一个未使用的 16 位无符号整数。此字段应设置为零<br/>            并且在接收时必须被忽略。 |
| image_effect | [EmfPlusImageEffectsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype/) | r/w | 获取或设置图像效果。 |
| object_guid | [GuidPacketRepresentation](/imaging/python-net/aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/) | r/w | 获取或设置 GUID 包表示值（[MS-DTYP] 第 2.3.4.2 节）<br/>            用于图像效果。此值必须对应于 ImageEffects 标识符之一（第 2.1.3.1 节）。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusSerializableObject(source) {#EmfPlusSerializableObject_source_1}


```
 EmfPlusSerializableObject(source) 
```

初始化 [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

