---
title: "LengthRecord"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс записи длины подпути"
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Класс записи длины подпути
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
| [LengthRecord()](#LengthRecord--) | Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
## Методы

| Метод | Описание |
| --- | --- |
| [isClosed()](#isClosed--) | Получает значение, указывающее, закрыт ли этот экземпляр. |
| [setClosed(boolean value)](#setClosed-boolean-) | Устанавливает значение, указывающее, закрыт ли этот экземпляр. |
| [isOpen()](#isOpen--) | Получает значение, указывающее, открыт ли этот экземпляр. |
| [setOpen(boolean value)](#setOpen-boolean-) | Устанавливает значение, указывающее, открыт ли этот экземпляр. |
| [getRecordCount()](#getRecordCount--) | Получает количество записей. |
| [setRecordCount(int value)](#setRecordCount-int-) | Устанавливает количество записей. |
| [getType()](#getType--) | Получает тип. |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Получает количество записей узлов Безье. |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Устанавливает количество записей узлов Безье. |
| [getPathOperations()](#getPathOperations--) | Получает операции пути. |
| [setPathOperations(int value)](#setPathOperations-int-) | Устанавливает операции пути. |
| [getShapeIndex()](#getShapeIndex--) | Получает индекс текущей формы пути в слое. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Устанавливает индекс текущей формы пути в слое. |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные записи. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Получает значение, указывающее, закрыт ли этот экземпляр.

Значение: `true`, если этот экземпляр закрыт; в противном случае `false`.

**Returns:**
boolean — значение, указывающее, закрыт ли этот экземпляр.
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Устанавливает значение, указывающее, закрыт ли этот экземпляр.

Значение: `true`, если этот экземпляр закрыт; в противном случае `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, закрыт ли этот экземпляр. |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Получает значение, указывающее, открыт ли этот экземпляр.

Значение: `true`, если этот экземпляр открыт; в противном случае `false`.

**Returns:**
boolean — значение, указывающее, открыт ли этот экземпляр.
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Устанавливает значение, указывающее, открыт ли этот экземпляр.

Значение: `true`, если этот экземпляр открыт; в противном случае `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, открыт ли этот экземпляр. |

### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Получает количество записей.

Значение: количество записей.

**Returns:**
int — количество записей.
### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Устанавливает количество записей.

Значение: количество записей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | количество записей. |

### getType() {#getType--}
```
public short getType()
```


Получает тип.

Значение: тип.

**Returns:**
short — тип.
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Получает количество записей узлов Безье.

**Returns:**
int — количество записей узлов Безье.
### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Устанавливает количество записей узлов Безье.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | количество записей узлов Безье. |

### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Получает операции пути.

**Returns:**
int — операции пути.
### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Устанавливает операции пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | операции пути. |

### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Получает индекс текущей формы пути в слое.

**Returns:**
int — индекс текущей формы пути в слое.
### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Устанавливает индекс текущей формы пути в слое.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | индекс текущей формы пути в слое. |

