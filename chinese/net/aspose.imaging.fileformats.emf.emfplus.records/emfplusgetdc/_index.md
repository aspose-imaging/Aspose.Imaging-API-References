---
title: "类 EmfPlusGetDc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusGetDc 类。EmfPlusGetDC 记录指定应处理元文件中后续遇到的 EMF 记录。"
type: docs
weight: 6250
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
## EmfPlusGetDc class

此 EmfPlusGetDC 记录指定应处理在元文件中遇到的后续 EMF 记录。

```csharp
public sealed class EmfPlusGetDc : EmfPlusControlRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusGetDc](emfplusgetdc/)(EmfPlusRecord) | 初始化 `EmfPlusGetDc` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/flags/) { get; set; } | 获取或设置未使用的 16 位无符号整数。此字段应设置为零，且在接收时必须被忽略。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


