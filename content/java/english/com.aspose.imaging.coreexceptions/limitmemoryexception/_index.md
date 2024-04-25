---
title: LimitMemoryException
second_title: Aspose.Imaging for Java API Reference
description: The limit memory exception.
type: docs
weight: 20
url: /com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

The limit memory exception. Occurs when memory usage should be reduced.
## Constructors

| Constructor | Description |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Initializes a new instance of the `LimitMemoryException` class. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the `LimitMemoryException` class. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Initializes a new instance of the `LimitMemoryException` class. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Initializes a new instance of the `LimitMemoryException` class. |
## Methods

| Method | Description |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Gets or sets the reduce memory factor. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Gets or sets the reduce memory factor. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Initializes a new instance of the `LimitMemoryException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The exception message. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Initializes a new instance of the `LimitMemoryException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The exception message. |
| innerException | java.lang.Throwable | The inner exception. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Initializes a new instance of the `LimitMemoryException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The exception message. |
| reduceMemoryFactor | long | The reduce memory factor. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Initializes a new instance of the `LimitMemoryException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The exception message. |
| innerException | java.lang.Throwable | The inner exception. |
| reduceMemoryFactor | int | The reduce memory factor. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Gets or sets the reduce memory factor.

Value: The reduce memory factor.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Gets or sets the reduce memory factor.

Value: The reduce memory factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

