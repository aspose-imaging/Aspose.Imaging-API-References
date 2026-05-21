---
title: "EmfColorCorrectPalette"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COLORCORRECTPALETTE указывает, как корректировать элементы логического объекта палитры, используя значения WCS 1.0."
type: docs
weight: 23
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

Запись EMR\_COLORCORRECTPALETTE определяет, как корректировать элементы логического объекта палитры с использованием значений WCS 1.0.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfColorCorrectPalette`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | Получает 32-битное беззнаковое целое, которое указывает индекс логического объекта палитры (раздел 2.2.17) в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhPalette(int value)](#setIhPalette-int-) | Задает 32-битное беззнаковое целое, которое указывает индекс логического объекта палитры (раздел 2.2.17) в таблице объектов EMF (раздел 3.1.1.1). |
| [getNFirstEntry()](#getNFirstEntry--) | Получает 32-битное беззнаковое целое, которое указывает индекс первой записи для корректировки. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | Задает 32-битное беззнаковое целое, которое указывает индекс первой записи для корректировки. |
| [getNPalEntries()](#getNPalEntries--) | Получает 32-битное беззнаковое целое, которое указывает количество записей палитры для корректировки. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Задает 32-битное беззнаковое целое, которое указывает количество записей палитры для корректировки. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfColorCorrectPalette`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


Получает 32-битное беззнаковое целое, которое указывает индекс логического объекта палитры (раздел 2.2.17) в таблице объектов EMF (раздел 3.1.1.1).

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


Задает 32-битное беззнаковое целое, которое указывает индекс логического объекта палитры (раздел 2.2.17) в таблице объектов EMF (раздел 3.1.1.1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


Получает 32-битное беззнаковое целое, которое указывает индекс первой записи для корректировки.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


Задает 32-битное беззнаковое целое, которое указывает индекс первой записи для корректировки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Получает 32-битное беззнаковое целое, которое указывает количество записей палитры для корректировки.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Задает 32-битное беззнаковое целое, которое указывает количество записей палитры для корректировки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

