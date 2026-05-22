---
title: "类 EmfPlusRestore"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusRestore 类。EmfPlusRestore 记录从已保存图形状态的堆栈中恢复由指定索引标识的图形状态。"
type: docs
weight: 6350
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
## EmfPlusRestore class

此 EmfPlusRestore 记录从已保存的图形状态栈中恢复由指定索引标识的图形状态。

```csharp
public sealed class EmfPlusRestore : EmfPlusStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusRestore](emfplusrestore/)(EmfPlusRecord) | 初始化 `EmfPlusRestore` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/stackindex/) { get; set; } | 获取或设置一个 32 位无符号整数，指定与图形状态关联的层级。该层级值由先前的 EmfPlusSave 记录（第 2.3.7.5 节）分配给图形状态。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


