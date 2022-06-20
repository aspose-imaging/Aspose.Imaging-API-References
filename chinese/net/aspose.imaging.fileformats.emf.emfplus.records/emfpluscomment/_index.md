---
title: EmfPlusComment
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusComment 记录指定任意私有数据
type: docs
weight: 5880
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
## EmfPlusComment class

EmfPlusComment 记录指定任意私有数据。

```csharp
public sealed class EmfPlusComment : EmfPlusRecord
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusComment](emfpluscomment)(EmfPlusRecord) | 初始化[`EmfPlusComment`](../emfpluscomment)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在 RecordData 字段中定义 32 位对齐的 数据字节数跟随。这个数字不包括 12 字节的记录头。 |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/flags) { get; set; } | 获取或设置未使用的 16 位无符号整数。该字段应该设置为零 并且必须在收到时被忽略 |
| [PrivateData](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/privatedata) { get; set; } | 获取或设置私有数据的 DataSize 长度字节数组。 后面的特定于记录的数据字节。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整条记录中的 32 位对齐字节数 ，包括 12 -byte 记录头和特定于记录的数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |

### 也可以看看

* class [EmfPlusRecord](../emfplusrecord)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->