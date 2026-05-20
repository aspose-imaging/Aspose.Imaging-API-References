---
title: "TiffImageException"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Tiff 图像异常"
type: docs
weight: 21
url: /zh/java/com.aspose.imaging.coreexceptions.imageformats/tiffimageexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.ImageException](../../com.aspose.imaging.coreexceptions/imageexception)
```
public class TiffImageException extends ImageException
```

Tiff 图像异常
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffImageException(String message)](#TiffImageException-java.lang.String-) | 初始化 `TiffImageException` 类的新实例。 |
| [TiffImageException(String message, Throwable innerException)](#TiffImageException-java.lang.String-java.lang.Throwable-) | 初始化 `TiffImageException` 类的新实例。 |
| [TiffImageException(String message, int error)](#TiffImageException-java.lang.String-int-) | 初始化 `TiffImageException` 类的新实例。 |
| [TiffImageException(int error)](#TiffImageException-int-) | 初始化 `TiffImageException` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOptionsError()](#getOptionsError--) | 获取 tiff 选项错误。 |
### TiffImageException(String message) {#TiffImageException-java.lang.String-}
```
public TiffImageException(String message)
```


初始化 `TiffImageException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |

### TiffImageException(String message, Throwable innerException) {#TiffImageException-java.lang.String-java.lang.Throwable-}
```
public TiffImageException(String message, Throwable innerException)
```


初始化 `TiffImageException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 该消息。 |
| innerException | java.lang.Throwable | 内部异常。 |

### TiffImageException(String message, int error) {#TiffImageException-java.lang.String-int-}
```
public TiffImageException(String message, int error)
```


初始化 `TiffImageException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 该消息。 |
| 错误 | int | 错误。 |

### TiffImageException(int error) {#TiffImageException-int-}
```
public TiffImageException(int error)
```


初始化 `TiffImageException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 错误 | int | 错误。 |

### getOptionsError() {#getOptionsError--}
```
public int getOptionsError()
```


获取 tiff 选项错误。

值：tiff 选项错误。

**Returns:**
int
