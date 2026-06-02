---
title: "LimitMemoryException"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Исключение ограничения памяти."
type: docs
weight: 21
url: /ru/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

Исключение ограничения памяти. Возникает, когда использование памяти должно быть уменьшено.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Инициализирует новый экземпляр класса `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Инициализирует новый экземпляр класса `LimitMemoryException`. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Инициализирует новый экземпляр класса `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Инициализирует новый экземпляр класса `LimitMemoryException`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Получает или задает коэффициент уменьшения памяти. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Получает или задает коэффициент уменьшения памяти. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Инициализирует новый экземпляр класса `LimitMemoryException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение исключения. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Инициализирует новый экземпляр класса `LimitMemoryException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение исключения. |
| innerException | java.lang.Throwable | Внутреннее исключение. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Инициализирует новый экземпляр класса `LimitMemoryException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение исключения. |
| reduceMemoryFactor | long | Коэффициент уменьшения памяти. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Инициализирует новый экземпляр класса `LimitMemoryException`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение исключения. |
| innerException | java.lang.Throwable | Внутреннее исключение. |
| reduceMemoryFactor | int | Коэффициент уменьшения памяти. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Получает или задает коэффициент уменьшения памяти.

Значение: уменьшенный коэффициент памяти.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Получает или задает коэффициент уменьшения памяти.

Значение: уменьшенный коэффициент памяти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

