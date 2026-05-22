---
title: "LimitMemoryException"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bellek sınırı istisnası."
type: docs
weight: 21
url: /tr/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

Bellek sınırı istisnası. Bellek kullanımı azaltılmalı olduğunda oluşur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Yeni bir `LimitMemoryException` sınıfı örneği başlatır. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Yeni bir `LimitMemoryException` sınıfı örneği başlatır. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Yeni bir `LimitMemoryException` sınıfı örneği başlatır. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Yeni bir `LimitMemoryException` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Azaltma bellek faktörünü alır veya ayarlar. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Azaltma bellek faktörünü alır veya ayarlar. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Yeni bir `LimitMemoryException` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İstisna mesajı. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Yeni bir `LimitMemoryException` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İstisna mesajı. |
| innerException | java.lang.Throwable | İç istisna. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Yeni bir `LimitMemoryException` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İstisna mesajı. |
| reduceMemoryFactor | long | Azaltma bellek faktörü. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Yeni bir `LimitMemoryException` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İstisna mesajı. |
| innerException | java.lang.Throwable | İç istisna. |
| reduceMemoryFactor | int | Azaltma bellek faktörü. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Azaltma bellek faktörünü alır veya ayarlar.

Değer: Bellek azaltma faktörü.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Azaltma bellek faktörünü alır veya ayarlar.

Değer: Bellek azaltma faktörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

