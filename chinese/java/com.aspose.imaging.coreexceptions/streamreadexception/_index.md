---
title: "StreamReadException"
second_title: "Aspose.Imaging for Java API 参考"
description: "流读取异常。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

流读取异常。当因偏移量或字节计数请求不正确导致流读取失败时产生。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | 初始化 `StreamReadException` 类的新实例。 |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | 初始化 `StreamReadException` 类的新实例。 |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | 初始化 `StreamReadException` 类的新实例。 |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | 初始化 `StreamReadException` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | 获取预期读取的字节数。 |
| [getActualReadCount()](#getActualReadCount--) | 获取实际读取的字节数。 |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


初始化 `StreamReadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 该消息。 |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


初始化 `StreamReadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 该消息。 |
| innerException | java.lang.Throwable | 内部异常。 |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


初始化 `StreamReadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 该消息。 |
| innerException | java.lang.Throwable | 内部异常。 |
| expectedReadCount | int | 预期读取计数。 |
| actualReadCount | int | 实际读取计数。 |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


初始化 `StreamReadException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 该消息。 |
| expectedReadCount | int | 预期读取计数。 |
| actualReadCount | int | 实际读取计数。 |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


获取预期读取的字节数。

**Returns:**
int - 预期读取的字节数。
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


获取实际读取的字节数。

**Returns:**
int - 实际读取的字节数。
