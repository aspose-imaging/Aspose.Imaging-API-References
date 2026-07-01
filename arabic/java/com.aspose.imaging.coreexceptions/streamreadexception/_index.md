---
title: "StreamReadException"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "استثناء قراءة التدفق."
type: docs
weight: 25
url: /ar/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

استثناء قراءة التدفق. يحدث عندما تفشل قراءة التدفق بسبب إزاحة غير صحيحة وطلب عدد بايتات غير صحيح.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | ينشئ مثيلاً جديدًا من الفئة `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | ينشئ مثيلاً جديدًا من الفئة `StreamReadException`. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | ينشئ مثيلاً جديدًا من الفئة `StreamReadException`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | يحصل على عدد البايتات المتوقعة للقراءة. |
| [getActualReadCount()](#getActualReadCount--) | يحصل على عدد البايتات الفعلية للقراءة. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


ينشئ مثيلاً جديدًا من الفئة `StreamReadException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | الرسالة. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


ينشئ مثيلاً جديدًا من الفئة `StreamReadException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | الرسالة. |
| innerException | java.lang.Throwable | الاستثناء الداخلي. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


ينشئ مثيلاً جديدًا من الفئة `StreamReadException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | الرسالة. |
| innerException | java.lang.Throwable | الاستثناء الداخلي. |
| expectedReadCount | int | عدد القراءة المتوقع. |
| actualReadCount | int | عدد القراءة الفعلي. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


ينشئ مثيلاً جديدًا من الفئة `StreamReadException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | الرسالة. |
| expectedReadCount | int | عدد القراءة المتوقع. |
| actualReadCount | int | عدد القراءة الفعلي. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


يحصل على عدد البايتات المتوقعة للقراءة.

**Returns:**
int - عدد البايتات المتوقعة للقراءة.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


يحصل على عدد البايتات الفعلية للقراءة.

**Returns:**
int - عدد البايتات الفعلية للقراءة.
