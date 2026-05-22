---
title: "类 EmfComment"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfComment 类。EMR_COMMENT 记录包含任意私有数据。注意，本节未描述的字段在第 2.3.3 节中指定。"
type: docs
weight: 3440
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
## EmfComment class

EMR_COMMENT 记录包含任意私有数据。注意，本节未描述的字段在第 2.3.3 节中指定。

```csharp
public sealed class EmfComment : EmfCommentRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfComment](emfcomment/)(EmfRecord) | 初始化 `EmfComment` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/commentidentifier/) { get; set; } | 获取或设置注释标识符。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| [PrivateData](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/privatedata/) { get; set; } | 获取或设置一个可选的字节数组，指定私有数据。该数据的第一个 DWORD 不得是第 2.3.3 节中指定的预定义注释标识符值之一。私有数据对 EMF 来说是未知的；仅对了解数据格式及其使用方式的应用程序有意义。可以忽略 EMR_COMMENT 私有数据记录。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


