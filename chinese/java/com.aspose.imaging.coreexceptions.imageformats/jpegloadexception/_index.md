---
title: "JpegLoadException"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 JPEG 图像加载异常。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.coreexceptions.imageformats/jpegloadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.ImageException](../../com.aspose.imaging.coreexceptions/imageexception), [com.aspose.imaging.coreexceptions.imageformats.JpegException](../../com.aspose.imaging.coreexceptions.imageformats/jpegexception)
```
public class JpegLoadException extends JpegException
```

表示 JPEG 图像加载异常。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpegLoadException(String message)](#JpegLoadException-java.lang.String-) | 初始化 `JpegLoadException` 类的新实例。 |
| [JpegLoadException(String message, Throwable innerException)](#JpegLoadException-java.lang.String-java.lang.Throwable-) | 初始化 `JpegLoadException` 类的新实例。 |
| [JpegLoadException(String message, int reason)](#JpegLoadException-java.lang.String-int-) | 初始化 `JpegLoadException` 类的新实例。 |
| [JpegLoadException(String message, Throwable innerException, int reason)](#JpegLoadException-java.lang.String-java.lang.Throwable-int-) | 初始化 `JpegLoadException` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getReason()](#getReason--) | 获取或设置错误原因。 |
| [setReason(int value)](#setReason-int-) | 获取或设置错误原因。 |
### JpegLoadException(String message) {#JpegLoadException-java.lang.String-}
```
public JpegLoadException(String message)
```


初始化 `JpegLoadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |

### JpegLoadException(String message, Throwable innerException) {#JpegLoadException-java.lang.String-java.lang.Throwable-}
```
public JpegLoadException(String message, Throwable innerException)
```


初始化 `JpegLoadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 该消息。 |
| innerException | java.lang.Throwable | 内部异常。 |

### JpegLoadException(String message, int reason) {#JpegLoadException-java.lang.String-int-}
```
public JpegLoadException(String message, int reason)
```


初始化 `JpegLoadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |
| reason | int | 错误原因。 |

### JpegLoadException(String message, Throwable innerException, int reason) {#JpegLoadException-java.lang.String-java.lang.Throwable-int-}
```
public JpegLoadException(String message, Throwable innerException, int reason)
```


初始化 `JpegLoadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |
| innerException | java.lang.Throwable | 内部异常。 |
| reason | int | 错误原因。 |

### getReason() {#getReason--}
```
public int getReason()
```


获取或设置错误原因。

值：错误原因。

**Returns:**
int
### setReason(int value) {#setReason-int-}
```
public void setReason(int value)
```


获取或设置错误原因。

值：错误原因。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

