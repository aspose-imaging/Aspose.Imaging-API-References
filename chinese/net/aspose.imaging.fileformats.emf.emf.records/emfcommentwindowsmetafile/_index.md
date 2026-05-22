---
title: "类 EmfCommentWindowsMetaFile"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentWindowsMetaFile 类。EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入的 WMF 元文件中的图像"
type: docs
weight: 3540
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
## EmfCommentWindowsMetaFile class

EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入 WMF 元文件中的图像。

```csharp
public sealed class EmfCommentWindowsMetaFile : EmfCommentPublicRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCommentWindowsMetaFile](emfcommentwindowsmetafile/)(EmfRecord) | 初始化 `EmfCommentWindowsMetaFile` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/checksum/) { get; set; } | 获取或设置一个 32 位无符号整数，指定此记录的校验和。 |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识此注释记录为公共数据。值 0x43494447，即 ASCII 字符串 “CIDG”，标识此记录为 EMR_COMMENT_PUBLIC 记录。 |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| [Flags](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/flags/) { get; set; } | 获取或设置一个 32 位值，必须为 0x00000000，且必须被忽略。 |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | 获取或设置一个 32 位无符号整数，用于标识公共注释记录的类型。除非打印服务器已实现其他公共注释记录类型，否则此值应为前表中列出的值之一，这些值在 EmrComment 枚举（第 2.1.10 节）中指定。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [Version](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/version/) { get; set; } | 获取或设置一个 16 位无符号整数，指定 WMF 元文件版本（即对设备无关位图 (DIB) 的支持），来源于 WMF MetafileVersion 枚举（[MS-WMF] 第 2.1.1.19 节）。 |
| [WinMetafile](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafile/) { get; set; } | 获取或设置一个包含 WMF 元文件的缓冲区。 |
| [WinMetafileSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafilesize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 WinMetafile 字段中 WMF 元文件的大小（字节）。 |

### 另请参见

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


