---
title: "枚举 EmfEmrComment"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfEmrComment 枚举。EmrComment 枚举定义了公共注释记录可以包含的数据类型，详见第 2.3.3.4 节。"
type: docs
weight: 2710
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
## EmfEmrComment enumeration

该 EmrComment 枚举定义了公共注释记录可以包含的数据类型，详见第 2.3.3.4 节。

```csharp
public enum EmfEmrComment : uint
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| EMR_COMMENT_WINDOWS_METAFILE | `2147483649` | 此注释记录包含 WMF 中图像的规范。有关更多信息，请参阅 [MS-WMF]。 |
| EMR_COMMENT_BEGINGROUP | `2` | 此注释记录标识一组绘图记录的开始。它标识 EMF 元文件中的一个对象。 |
| EMR_COMMENT_ENDGROUP | `3` | 此注释记录标识一组绘图记录的结束。对于每个 EMR_COMMENT_BEGINGROUP 记录，元文件中必须包含相应的 EMR_COMMENT_ENDGROUP 记录，且它们可以嵌套。 |
| EMR_COMMENT_MULTIFORMATS | `1073741828` | 此注释记录允许在元文件中包含图像的多个定义。例如，使用此注释，应用程序可以同时包含封装的 PostScript 文本以及图像的 EMF 定义。 |
| EMR_COMMENT_UNICODE_STRING | `64` | 此注释记录已保留，禁止在 EMF 元文件中使用。 |
| EMR_COMMENT_UNICODE_END | `128` | 此注释记录已保留，禁止在 EMF 元文件中使用。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


