---
title: "类 EmfPlusSetAntiAliasMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetAntiAliasMode 类。EmfPlusSetAntiAliasMode 记录指定文本输出的抗锯齿模式"
type: docs
weight: 6400
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
## EmfPlusSetAntiAliasMode class

此 EmfPlusSetAntiAliasMode 记录指定文本输出的抗锯齿模式。

```csharp
public sealed class EmfPlusSetAntiAliasMode : EmfPlusPropertyRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetAntiAliasMode](emfplussetantialiasmode/)(EmfPlusRecord) | 初始化 `EmfPlusSetAntiAliasMode` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AntiAliasing](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/antialiasing/) { get; set; } | 获取或设置一个值，指示是否 [anti aliasing]。如果设置，则应执行抗锯齿；如果未设置，则不应执行抗锯齿。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [SmoothingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/smoothingmode/) { get; set; } | 获取或设置平滑模式。（7 位）：平滑模式值，取自 SmoothingMode 枚举（第 2.1.1.28 节） |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


