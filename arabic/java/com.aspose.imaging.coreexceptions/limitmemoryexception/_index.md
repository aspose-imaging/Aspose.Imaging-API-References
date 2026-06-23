---
title: "LimitMemoryException"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "استثناء الذاكرة المحدودة."
type: docs
weight: 21
url: /ar/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

استثناء الذاكرة المحدودة. يحدث عندما يجب تقليل استخدام الذاكرة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | يحصل أو يعيّن عامل تقليل الذاكرة. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | يحصل أو يعيّن عامل تقليل الذاكرة. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الاستثناء. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الاستثناء. |
| innerException | java.lang.Throwable | الاستثناء الداخلي. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الاستثناء. |
| reduceMemoryFactor | long | عامل تقليل الذاكرة. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


يقوم بإنشاء نسخة جديدة من الفئة `LimitMemoryException`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الاستثناء. |
| innerException | java.lang.Throwable | الاستثناء الداخلي. |
| reduceMemoryFactor | int | عامل تقليل الذاكرة. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


يحصل أو يعيّن عامل تقليل الذاكرة.

القيمة: عامل تقليل الذاكرة.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


يحصل أو يعيّن عامل تقليل الذاكرة.

القيمة: عامل تقليل الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

