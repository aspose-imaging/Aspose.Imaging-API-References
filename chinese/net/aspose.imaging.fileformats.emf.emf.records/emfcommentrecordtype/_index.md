---
title: "类 EmfCommentRecordType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentRecordType 类。注释记录类型定义了在其他元文件格式中指定任意私有数据嵌入记录以及添加新或特殊用途命令的格式"
type: docs
weight: 3520
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
## EmfCommentRecordType class

注释记录类型定义了用于指定任意私有数据、在其他元文件格式中嵌入记录以及添加新或特殊用途命令的格式。

```csharp
public abstract class EmfCommentRecordType : EmfRecord
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/commentidentifier/) { get; set; } | 获取或设置注释标识符。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


