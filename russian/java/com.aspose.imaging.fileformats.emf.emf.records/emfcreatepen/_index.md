---
title: "EmfCreatePen"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_CREATEPEN определяет логическое перо для графических операций."
type: docs
weight: 41
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

Запись EMR\_CREATEPEN определяет логическое перо для графических операций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCreatePen`. |
| [EmfCreatePen()](#EmfCreatePen--) | Инициализирует новый экземпляр класса `EmfCreatePen`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhPen()](#getIhPen--) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс объекта логического пера в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс объекта логического пера в таблице объектов EMF (раздел 3.1.1.1). |
| [getLogPen()](#getLogPen--) | Получает или задает объект LogPen (раздел 2.2.19), который определяет стиль, ширину и цвет логического пера. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Получает или задает объект LogPen (раздел 2.2.19), который определяет стиль, ширину и цвет логического пера. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCreatePen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


Инициализирует новый экземпляр класса `EmfCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Получает или задает 32-битное беззнаковое целое, которое определяет индекс объекта логического пера в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект можно было повторно использовать или изменить.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет индекс объекта логического пера в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект можно было повторно использовать или изменить.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Получает или задает объект LogPen (раздел 2.2.19), который определяет стиль, ширину и цвет логического пера.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Получает или задает объект LogPen (раздел 2.2.19), который определяет стиль, ширину и цвет логического пера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

