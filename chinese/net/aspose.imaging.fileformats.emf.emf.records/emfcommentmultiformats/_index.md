---
title: "类 EmfCommentMultiFormats"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentMultiFormats 类。EMR_COMMENT_MULTIFORMATS 记录指定以多种图形格式表示的图像。"
type: docs
weight: 3500
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
## EmfCommentMultiFormats class

EMR_COMMENT_MULTIFORMATS 记录指定多种图形格式的图像。

```csharp
public sealed class EmfCommentMultiFormats : EmfCommentPublicRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCommentMultiFormats](emfcommentmultiformats/)(EmfRecord) | 初始化 `EmfCommentMultiFormats` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AFormats](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/aformats/) { get; set; } | 获取或设置一个长度为 CountFormats 的图形格式数组，由 EmrFormat 对象（第 2.2.4 节）指定，按优先顺序排列。 |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识此注释记录为公共数据。值 0x43494447，即 ASCII 字符串 “CIDG”，标识此记录为 EMR_COMMENT_PUBLIC 记录。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| [FormatData](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/formatdata/) { get; set; } | 获取或设置一个可变长度的字节数组，包含此记录中所有图形格式的图像数据。每个图像的数据大小由相应 EmrFormat 对象的 DataSize 字段提供。因此，此字段的总大小等于所有 EmrFormat 对象中 DataSize 值的总和。每个图像的数据的图形格式由相应 EmrFormat 对象的 Signature 字段指定。 |
| [OutputRect](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/outputrect/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定以逻辑坐标表示的输出矩形。 |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识公共注释记录的类型。除非打印服务器已实现其他公共注释记录类型，否则此值应为前表中列出的值之一，这些值在 EmrComment 枚举（第 2.1.10 节）中指定。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


