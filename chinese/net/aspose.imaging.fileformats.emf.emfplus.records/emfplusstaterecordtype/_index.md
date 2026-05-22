---
title: "类 EmfPlusStateRecordType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusStateRecordType 类。状态记录类型指定对回放设备上下文状态的操作。"
type: docs
weight: 6550
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype/
---
## EmfPlusStateRecordType class

State Record Types 指定对回放设备上下文状态的操作。

```csharp
public abstract class EmfPlusStateRecordType : EmfPlusRecord
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

## 备注

每个图形状态容器必须添加到已保存图形容器的数组中。图形状态容器不会写入 EMF+ 元文件，因此其格式由实现决定。

### 另请参见

* class [EmfPlusRecord](../emfplusrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


