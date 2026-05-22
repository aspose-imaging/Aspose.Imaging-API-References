---
title: "类 EmfCreatePalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreatePalette 类。EMR_CREATEPALETTE 记录定义了用于图形操作的逻辑调色板"
type: docs
weight: 3610
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
## EmfCreatePalette class

EMR_CREATEPALETTE 记录定义用于图形操作的逻辑调色板。

```csharp
public sealed class EmfCreatePalette : EmfObjectCreationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCreatePalette](emfcreatepalette/)(EmfRecord) | 初始化 `EmfCreatePalette` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/ihpal/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象的索引。必须保存此索引，以便该对象可以被重用或修改。 |
| [LogPalette](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/logpalette/) { get; set; } | 获取或设置一个 LogPalette 对象（第 2.2.17 节）。该对象的 Version 字段必须设置为 0x0300。如果该对象的 NumberOfEntries 值为零，则此记录的处理必须失败。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


