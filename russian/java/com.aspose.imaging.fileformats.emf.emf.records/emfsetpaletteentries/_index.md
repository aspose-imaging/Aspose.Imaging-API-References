---
title: "EmfSetPaletteEntries"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETPALETTEENTRIES определяет значения цветов RGB в диапазоне записей для существующего объекта LogPalette раздела 2.2.17."
type: docs
weight: 134
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

Запись EMR\_SETPALETTEENTRIES задает значения цветов RGB в диапазоне записей для существующего объекта LogPalette (раздел 2.2.17).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetPaletteEntries`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhPal()](#getIhPal--) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс таблицы объектов EMF палитры. |
| [setIhPal(int value)](#setIhPal-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс таблицы объектов EMF палитры. |
| [getStart()](#getStart--) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс первой записи для установки. |
| [setStart(int value)](#setStart-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс первой записи для установки. |
| [getNumberofEntries()](#getNumberofEntries--) | Получает или задает 32‑битное беззнаковое целое, которое указывает количество записей. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает количество записей. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Получает или задает массив объектов LogPaletteEntry (section 2.2.18) длиной NumberOfEntries, который определяет данные записей палитры. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Получает или задает массив объектов LogPaletteEntry (section 2.2.18) длиной NumberOfEntries, который определяет данные записей палитры. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetPaletteEntries`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс таблицы объектов EMF палитры.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс таблицы объектов EMF палитры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс первой записи для установки.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс первой записи для установки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает количество записей.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает количество записей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Получает или задает массив объектов LogPaletteEntry (section 2.2.18) длиной NumberOfEntries, который определяет данные записей палитры. Члены Values не содержат никаких значений.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Получает или задает массив объектов LogPaletteEntry (section 2.2.18) длиной NumberOfEntries, который определяет данные записей палитры. Члены Values не содержат никаких значений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

