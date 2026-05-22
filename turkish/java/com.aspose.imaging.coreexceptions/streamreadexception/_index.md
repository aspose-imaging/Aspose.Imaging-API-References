---
title: "StreamReadException"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Akış okuma istisnası."
type: docs
weight: 25
url: /tr/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

Akış okuma istisnası. Yanlış ofset ve bayt sayısı isteği nedeniyle akış okuması başarısız olduğunda ortaya çıkar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | `StreamReadException` sınıfının yeni bir örneğini başlatır. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | `StreamReadException` sınıfının yeni bir örneğini başlatır. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | `StreamReadException` sınıfının yeni bir örneğini başlatır. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | `StreamReadException` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Beklenen okunan bayt sayısını alır. |
| [getActualReadCount()](#getActualReadCount--) | Gerçek okunan bayt sayısını alır. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


`StreamReadException` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Mesaj. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


`StreamReadException` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Mesaj. |
| innerException | java.lang.Throwable | İç istisna. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


`StreamReadException` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Mesaj. |
| innerException | java.lang.Throwable | İç istisna. |
| expectedReadCount | int | Beklenen okuma sayısı. |
| actualReadCount | int | Gerçek okuma sayısı. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


`StreamReadException` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Mesaj. |
| expectedReadCount | int | Beklenen okuma sayısı. |
| actualReadCount | int | Gerçek okuma sayısı. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Beklenen okunan bayt sayısını alır.

**Returns:**
int - Beklenen okunan bayt sayısı.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Gerçek okunan bayt sayısını alır.

**Returns:**
int - Gerçek okunan bayt sayısı.
