---
title: EmfEmrComment
second_title: Aspose.Imaging for .NET API 参考
description: EmrComment 枚举定义公共评论记录 can 包含的数据类型如第 2.3.3.4. 节中所述
type: docs
weight: 2620
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
## EmfEmrComment enumeration

EmrComment 枚举定义公共评论记录 can 包含的数据类型，如第 2.3.3.4. 节中所述

```csharp
public enum EmfEmrComment : uint
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| EMR_COMMENT_WINDOWS_METAFILE | `2147483649` | 此评论记录包含 WMF 中图像的规范。有关详细信息，请参阅 [MS-WMF] |
| EMR_COMMENT_BEGINGROUP | `2` | 此注释记录标识一组绘图记录的开始。它标识 EMF 元文件 中的对象 |
| EMR_COMMENT_ENDGROUP | `3` | 此注释记录标识一组绘图记录的结尾。对于每个 EMR_COMMENT_BEGINGROUP 记录，EMR_COMMENT_ENDGROUP 记录必须包含在元文件中，并且它们可以嵌套。 |
| EMR_COMMENT_MULTIFORMATS | `1073741828` | 此注释记录允许将图像的多个定义包含在元文件中。 例如，使用此注释，应用程序可以包含封装的 PostScript 文本以及图像的 EMF 定义。 |
| EMR_COMMENT_UNICODE_STRING | `64` | 此评论记录是保留的，不得在 EMF 元文件中使用 |
| EMR_COMMENT_UNICODE_END | `128` | 此评论记录是保留的，不得在 EMF 元文件中使用 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
