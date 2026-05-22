---
title: "类 EmfPlusSetInterpolationMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetInterpolationMode 类。EmfPlusSetInterpolationMode 记录指定图像缩放（包括拉伸和收缩）的执行方式。"
type: docs
weight: 6460
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---
## EmfPlusSetInterpolationMode class

此 EmfPlusSetInterpolationMode 记录指定图像缩放（包括拉伸和收缩）的执行方式。

```csharp
public sealed class EmfPlusSetInterpolationMode : EmfPlusPropertyRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetInterpolationMode](emfplussetinterpolationmode/)(EmfPlusRecord) | 初始化 `EmfPlusSetInterpolationMode` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [InterpolationMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/interpolationmode/) { get; set; } | 获取或设置插值模式值，来自 InterpolationMode 枚举（第 2.1.1.16 节）。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


