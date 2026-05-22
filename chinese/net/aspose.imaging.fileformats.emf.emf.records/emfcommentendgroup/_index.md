---
title: "类 EmfCommentEndGroup"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentEndGroup 类。EMR_COMMENT_ENDGROUP 记录指定一组绘图记录的结束。"
type: docs
weight: 3490
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/
---
## EmfCommentEndGroup class

EMR_COMMENT_ENDGROUP 记录指定一组绘图记录的结束。

```csharp
public sealed class EmfCommentEndGroup : EmfCommentPublicRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCommentEndGroup](emfcommentendgroup/)(EmfRecord) | 初始化 `EmfCommentEndGroup` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识此注释记录为公共数据。值 0x43494447，即 ASCII 字符串 “CIDG”，标识此记录为 EMR_COMMENT_PUBLIC 记录。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识公共注释记录的类型。除非打印服务器已实现其他公共注释记录类型，否则此值应为前表中列出的值之一，这些值在 EmrComment 枚举（第 2.1.10 节）中指定。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


