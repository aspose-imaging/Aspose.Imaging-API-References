---
title: "类 EmfPlusEndOfFile"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusEndOfFile 类。EmfPlusEndOfFile 记录指定元文件中 EMF 数据的结束。"
type: docs
weight: 6170
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---
## EmfPlusEndOfFile class

EmfPlusEndOfFile 记录指定元文件中 EMF+ 数据的结束。

```csharp
public sealed class EmfPlusEndOfFile : EmfPlusControlRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusEndOfFile](emfplusendoffile/)(EmfPlusRecord) | 初始化 `EmfPlusEndOfFile` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/flags/) { get; set; } | 获取或设置未使用的 16 位无符号整数。此字段应设置为零，且在接收时必须被忽略。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


