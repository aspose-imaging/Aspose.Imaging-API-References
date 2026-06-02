---
title: "StreamReadException"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Исключение чтения потока."
type: docs
weight: 25
url: /ru/java/com.aspose.imaging.coreexceptions/streamreadexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.imaging.coreexceptions.FrameworkException](../../com.aspose.imaging.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

Исключение чтения потока. Возникает, когда чтение потока не удалось из‑за неверного смещения и запроса количества байтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Инициализирует новый экземпляр класса `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Инициализирует новый экземпляр класса `StreamReadException`. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Инициализирует новый экземпляр класса `StreamReadException`. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Инициализирует новый экземпляр класса `StreamReadException`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getExpectedReadCount()](#getExpectedReadCount--) | Возвращает ожидаемое количество прочитанных байтов. |
| [getActualReadCount()](#getActualReadCount--) | Возвращает фактическое количество прочитанных байтов. |
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Инициализирует новый экземпляр класса `StreamReadException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Инициализирует новый экземпляр класса `StreamReadException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение. |
| innerException | java.lang.Throwable | Внутреннее исключение. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Инициализирует новый экземпляр класса `StreamReadException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение. |
| innerException | java.lang.Throwable | Внутреннее исключение. |
| expectedReadCount | int | Ожидаемое количество чтения. |
| actualReadCount | int | Фактическое количество чтения. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Инициализирует новый экземпляр класса `StreamReadException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение. |
| expectedReadCount | int | Ожидаемое количество чтения. |
| actualReadCount | int | Фактическое количество чтения. |

### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Возвращает ожидаемое количество прочитанных байтов.

**Returns:**
int — ожидаемое количество прочитанных байтов.
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Возвращает фактическое количество прочитанных байтов.

**Returns:**
int — фактическое количество прочитанных байтов.
