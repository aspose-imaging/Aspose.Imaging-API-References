---
title: "LimitMemoryException"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "内存限制异常。"
type: docs
weight: 21
url: /zh/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

内存限制异常。发生在应减少内存使用时。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | 初始化 `LimitMemoryException` 类的新实例。 |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | 初始化 `LimitMemoryException` 类的新实例。 |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | 初始化 `LimitMemoryException` 类的新实例。 |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | 初始化 `LimitMemoryException` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | 获取或设置降低内存因子。 |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | 获取或设置降低内存因子。 |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


初始化 `LimitMemoryException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


初始化 `LimitMemoryException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |
| innerException | java.lang.Throwable | 内部异常。 |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


初始化 `LimitMemoryException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |
| reduceMemoryFactor | long | 降低内存因子。 |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


初始化 `LimitMemoryException` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 异常消息。 |
| innerException | java.lang.Throwable | 内部异常。 |
| reduceMemoryFactor | int | 降低内存因子。 |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


获取或设置降低内存因子。

值：降低内存因子。

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


获取或设置降低内存因子。

值：降低内存因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

