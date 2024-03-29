---
title: EmfCommentWindowsMetaFile
second_title: Aspose.Imaging for .NET API 参考
description: EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入 WMF 元文件中的图像
type: docs
weight: 3440
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
## EmfCommentWindowsMetaFile class

EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入 WMF 元文件中的图像。

```csharp
public sealed class EmfCommentWindowsMetaFile : EmfCommentPublicRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfCommentWindowsMetaFile](emfcommentwindowsmetafile)(EmfRecord) | 初始化[`EmfCommentWindowsMetaFile`](../emfcommentwindowsmetafile)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/checksum) { get; set; } | 获取或设置一个 32 位无符号整数，指定此记录的校验和。 |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier) { get; set; } | 获取或设置一个 32 位无符号整数，将这条评论记录 标识为指定公共数据。值 0x43494447，即 ASCII 字符串“CIDG”，将 标识为 EMR_COMMENT_PUBLIC 记录。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，它指定 后面的 RecordBuffer 字段中的 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。如果 present 它不能包含自身的大小或 AlignmentPadding 字段的大小 |
| [Flags](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/flags) { get; set; } | 获取或设置一个必须为 0x00000000 且必须被忽略的 32 位值。 |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识 公共评论记录的类型。这应该是上表中列出的值之一，其中 在 EmrComment 枚举（第 2.1.10 节）中指定，除非在打印服务器上实现了额外的公共 评论记录类型。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |
| [Version](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/version) { get; set; } | 获取或设置一个 16 位无符号整数，它根据 WMF MetafileVersion 枚举（[MS-WMF] 第 2.1.1.19 节）的 支持与设备无关的位图 (DIB) 来指定 WMF 元文件版本。 |
| [WinMetafile](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafile) { get; set; } | 获取或设置包含 WMF 元文件的缓冲区。 |
| [WinMetafileSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafilesize) { get; set; } | 获取或设置一个 32 位无符号整数，它指定 WinMetafile 字段中 WMF 元文件的大小（以字节为单位）。 |

### 也可以看看

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
