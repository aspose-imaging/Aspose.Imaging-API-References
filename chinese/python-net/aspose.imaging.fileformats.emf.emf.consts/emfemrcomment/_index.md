---
title: "EmfEmrComment 枚举"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---

EmrComment 枚举定义了公共注释记录可以包含的数据类型，<br/>            如第 2.3.3.4 节所述。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfEmrComment

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| EMR_COMMENT_BEGINGROUP | 此注释记录标识一组绘图记录的开始。它标识 EMF 元文件中的一个对象。 |
| EMR_COMMENT_ENDGROUP | 此注释记录标识一组绘图记录的结束。对于每个 EMR_COMMENT_BEGINGROUP<br/>            记录，必须在元文件中包含一个 EMR_COMMENT_ENDGROUP 记录，并且它们可以嵌套。 |
| EMR_COMMENT_MULTIFORMATS | 此注释记录允许在元文件中包含图像的多个定义。<br/>            例如，使用此注释，应用程序可以同时包含封装的 PostScript 文本以及图像的 EMF 定义。 |
| EMR_COMMENT_UNICODE_END | 此注释记录已保留，且不得在 EMF 元文件中使用。 |
| EMR_COMMENT_UNICODE_STRING | 此注释记录已保留，且不得在 EMF 元文件中使用。 |
| EMR_COMMENT_WINDOWS_METAFILE | 此注释记录包含 WMF 中图像的规范。有关更多信息，请参阅 [MS-WMF]。 |
