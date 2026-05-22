---
title: "类 EmfCommentEmfPlus"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentEmfPlus 类。EMR_COMMENT_EMFPLUS 记录包含嵌入的 EMF 记录。注意，本节未描述的字段在第 2.3.3 节中指定。"
type: docs
weight: 3460
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
## EmfCommentEmfPlus class

EMR_COMMENT_EMFPLUS 记录包含嵌入的 EMF+ 记录。注意，本节未描述的字段在第 2.3.3 节中指定。

```csharp
public sealed class EmfCommentEmfPlus : EmfCommentRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCommentEmfPlus](emfcommentemfplus/)(EmfRecord) | 初始化 `EmfCommentEmfPlus` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/commentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMF+ 记录。值 0x2B464D45（ASCII 字符串 "+FME"）将其标识为 EMR_COMMENT_EMFPLUS 记录。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| [EmfPlusRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/emfplusrecords/) { get; set; } | 获取或设置一个字节数组，包含一个或多个 EMF+ 记录（[MS-EMFPLUS] 第 2.3.1 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


