---
title: "类 EmfPlusHeader"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusHeader 类。EmfPlusHeader 记录指定元文件中 EMF 数据的起始位置。EmfPlusHeader 记录必须嵌入在 EMF EMR_COMMENT_EMFPLUS 记录中，该记录必须紧跟在元文件的 EMF 头部之后。EMR_COMMENT_EMFPLUS 记录在 MSEMF 第 2.3.3.2 节中有说明。"
type: docs
weight: 6260
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

此 EmfPlusHeader 记录指定元文件中 EMF+ 数据的开始。此 EmfPlusHeader 记录必须嵌入在 EMF EMR_COMMENT_EMFPLUS 记录中，该记录必须是元文件中 EMF 头之后紧随的记录。EMR_COMMENT_EMFPLUS 记录在 [MS-EMF] 第 2.3.3.2 节中指定。

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusHeader](emfplusheader/)(EmfPlusRecord) | 初始化 `EmfPlusHeader` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode/) { get; set; } | 获取或设置一个值，指示是否 [dual mode]。如果设置，则此标志表示该元文件为"dual-mode"，即它包含两套记录，每套记录完整地指定图形内容。如果未设置，则图形内容由 EMF+ 记录指定，且可能还有在 EmfPlusGetDC 记录之前的 EMF 记录。如果此标志被设置，仅 EMF 记录就应足以定义图形内容。请注意，无论"dual-mode"标志是否设置，某些 EMF 记录始终存在，即 EMF 控制记录和包含 EMF+ 记录的 EMF 记录。EMF 控制记录在 [MS-EMF] 第 2.3.4 节中有说明。 |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags/) { get; set; } | 获取或设置 EMF plus 标志。一个 32 位无符号整数，包含有关此元文件记录方式的信息。如果字段的第 31 位被设置，则此标志表示该元文件使用视频显示的参考设备上下文进行记录。如果未设置，则该元文件使用打印机的参考设备上下文进行记录。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid/) { get; } | 获取一个值，指示此实例是否有效。 |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix/) { get; set; } | 获取或设置逻辑水平 DPI。一个 32 位无符号整数，指定元文件记录时的水平分辨率，单位为每英寸像素数。 |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy/) { get; set; } | 获取或设置逻辑垂直 DPI。一个 32 位无符号整数，指定元文件记录时的垂直分辨率，单位为每英寸线数。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version/) { get; set; } | 获取或设置版本。一个 EmfPlusGraphicsVersion 对象（第 2.2.2.19 节），指定用于创建此元文件的操作系统图形版本。 |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay/) { get; set; } | 获取或设置一个值，指示是否视频显示。如果设置，此标志表示该元文件使用视频显示的参考设备上下文进行记录。如果未设置，则该元文件使用打印机的参考设备上下文进行记录。 |

### 另请参见

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


