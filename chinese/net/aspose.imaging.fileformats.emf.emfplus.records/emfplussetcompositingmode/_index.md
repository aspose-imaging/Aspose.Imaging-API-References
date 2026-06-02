---
title: "类 EmfPlusSetCompositingMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetCompositingMode 类。EmfPlusSetCompositingMode 记录指定源颜色如何与背景颜色组合。"
type: docs
weight: 6440
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
## EmfPlusSetCompositingMode class

此 EmfPlusSetCompositingMode 记录指定源颜色与背景颜色的合成方式。

```csharp
public sealed class EmfPlusSetCompositingMode : EmfPlusPropertyRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetCompositingMode](emfplussetcompositingmode/)(EmfPlusRecord) | 初始化 `EmfPlusSetCompositingMode` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/compositingmode/) { get; set; } | 获取或设置合成模式值，来自 CompositingMode 枚举（章节 2.1.1.5）。合成可以表示为 alpha 混合的状态，可能开启或关闭。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


