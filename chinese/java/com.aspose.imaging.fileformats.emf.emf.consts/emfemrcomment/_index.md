---
title: "EmfEmrComment"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 EmrComment 枚举定义了公共注释记录可以包含的数据类型，如第 2.3.3.4 节所指定。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

EmrComment 枚举定义了公共注释记录可以包含的数据类型，详见第 2.3.3.4 节。
## 字段

| 字段 | 描述 |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | 此注释记录包含 WMF 中图像的规范。 |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | 此注释记录标识一组绘图记录的开始。 |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | 此注释记录标识一组绘图记录的结束。 |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | 此注释记录允许在元文件中包含图像的多个定义。 |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | 此注释记录已保留，且不得在 EMF 元文件中使用。 |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | 此注释记录已保留，且不得在 EMF 元文件中使用。 |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


此注释记录包含 WMF 中图像的规范。详见 [MS-WMF] 获取更多信息。

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


此注释记录标识一组绘图记录的开始。它标识 EMF 元文件中的一个对象

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


此注释记录标识一组绘图记录的结束。对于每个 EMR\_COMMENT\_BEGINGROUP 记录，必须在元文件中包含相应的 EMR\_COMMENT\_ENDGROUP 记录，并且它们可以嵌套。

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


此注释记录允许在元文件中包含图像的多个定义。例如，使用此注释，应用程序可以包含封装的 PostScript 文本以及图像的 EMF 定义。

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


此注释记录已保留，且不得在 EMF 元文件中使用。

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


此注释记录已保留，且不得在 EMF 元文件中使用。

