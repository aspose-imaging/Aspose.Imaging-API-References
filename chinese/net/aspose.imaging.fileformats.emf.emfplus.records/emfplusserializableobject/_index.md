---
title: "类 EmfPlusSerializableObject"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSerializableObject 类。EmfPlusSerializableObject 记录定义了已序列化到数据缓冲区的图像效果参数块"
type: docs
weight: 6390
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
## EmfPlusSerializableObject class

此 EmfPlusSerializableObject 记录定义已序列化到数据缓冲区的图像效果参数块。

```csharp
public sealed class EmfPlusSerializableObject : EmfPlusObjectRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSerializableObject](emfplusserializableobject/)(EmfPlusRecord) | 初始化 `EmfPlusSerializableObject` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Buffer](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/buffer/) { get; set; } | 获取或设置一个 BufferSize 字节的数组，包含对应于 ObjectGUID 字段中 GUID 的序列化图像效果参数块。该数组必须是 Image Effects 对象之一（第 2.2.3 节）。 |
| [BufferSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/buffersize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 32 位对齐的 Buffer 字段的字节大小。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/flags/) { get; set; } | 获取或设置一个未使用的 16 位无符号整数。此字段应设置为零，且在接收时必须被忽略。 |
| [ImageEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/imageeffect/) { get; set; } | 获取或设置图像效果。 |
| [ObjectGuid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/objectguid/) { get; set; } | 获取或设置图像效果的 GUID 包表示值（[MS-DTYP] 第 2.3.4.2 节）。该值必须对应于 ImageEffects 标识符之一（第 2.1.3.1 节）。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


