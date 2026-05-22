---
title: "类 EmfCommentEmfSpool"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentEmfSpool 类。EMR_COMMENT_EMFSPOOL 记录包含嵌入的 EMFSPOOL 记录。注意，本节未描述的字段在第 2.3.3 节中指定。"
type: docs
weight: 3470
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
## EmfCommentEmfSpool class

EMR_COMMENT_EMFSPOOL 记录包含嵌入的 EMFSPOOL 记录。注意，本节未描述的字段在第 2.3.3 节中指定。

```csharp
public sealed class EmfCommentEmfSpool : EmfCommentRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCommentEmfSpool](emfcommentemfspool/#constructor)() | 初始化 `EmfCommentEmfSpool` 类的新实例。 |
| [EmfCommentEmfSpool](emfcommentemfspool/#constructor_1)(EmfRecord) | 初始化 `EmfCommentEmfSpool` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/commentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，标识此注释记录包含 EMFSPOOL 记录。值 0x00000000 将其标识为 EMR_COMMENT_EMFSPOOL 记录。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| [EmfSpoolRecordIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecordidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，标识 EMR_COMMENT_EMFSPOOL 记录的类型。 |
| [EmfSpoolRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecords/) { get; set; } | 获取或设置一个可变长度的字节数组，包含一个或多个 EMFSPOOL 字体定义记录（[MS-EMFSPOOL] 第 2.2.3.3 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


