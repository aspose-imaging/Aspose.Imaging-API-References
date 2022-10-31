---
title: StreamReadException
second_title: Aspose.Imaging for Java API Reference
description: The stream reading exception.
type: docs
weight: 24
url: /java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

The stream reading exception. Caused when stream reading failed due to incorrect offset and bytes count request.
## Constructors

| Constructor | Description |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Initializes a new instance of the `StreamReadException` class. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the `StreamReadException` class. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Initializes a new instance of the `StreamReadException` class. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Initializes a new instance of the `StreamReadException` class. |
## Methods

| Method | Description |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Gets the expected read bytes count. |
| [getActualReadCount()](#getActualReadCount--) | Gets the actual read bytes count. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Initializes a new instance of the `StreamReadException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Initializes a new instance of the `StreamReadException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| innerException | java.lang.Throwable | The inner exception. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Initializes a new instance of the `StreamReadException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| innerException | java.lang.Throwable | The inner exception. |
| expectedReadCount | int | The expected read count. |
| actualReadCount | int | The actual read count. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Initializes a new instance of the `StreamReadException` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| expectedReadCount | int | The expected read count. |
| actualReadCount | int | The actual read count. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Gets the expected read bytes count.

**Returns:**
int - The expected read bytes count.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Gets the actual read bytes count.

**Returns:**
int - The actual read bytes count.
