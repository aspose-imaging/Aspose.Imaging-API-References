---
title: "类 EmfPlusSetTextRenderingHint"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTextRenderingHint 类。EmfPlusSetTextRenderingHint 记录指定文本渲染的质量，包括抗锯齿的类型。"
type: docs
weight: 6510
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/
---
## EmfPlusSetTextRenderingHint class

EmfPlusSetTextRenderingHint 记录指定文本渲染的质量，包括抗锯齿的类型。

```csharp
public sealed class EmfPlusSetTextRenderingHint : EmfPlusPropertyRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetTextRenderingHint](emfplussettextrenderinghint/)(EmfPlusRecord) | 初始化 `EmfPlusSetTextRenderingHint` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [TextRenderingHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/textrenderinghint/) { get; set; } | 获取或设置文本渲染提示值，来自 TextRenderingHint 枚举（第 2.1.1.32 节），该值指定后续文本渲染使用的质量。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


