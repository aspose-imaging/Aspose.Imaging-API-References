---
title: "EmfSelectPalette"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SELECTPALETTE определяет логическую палитру для контекста устройства воспроизведения."
type: docs
weight: 117
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

Запись EMR\_SELECTPALETTE определяет логическую палитру для контекста устройства воспроизведения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSelectPalette`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhPal()](#getIhPal--) | Получает или задает 32-битное беззнаковое целое, которое указывает либо индекс объекта LogPalette (раздел 2.2.17) в таблице объектов EMF, либо значение DEFAULT\_PALETTE, которое является индексом палитры стандартного объекта из перечисления StockObject (раздел 2.1.31). |
| [setIhPal(int value)](#setIhPal-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает либо индекс объекта LogPalette (раздел 2.2.17) в таблице объектов EMF, либо значение DEFAULT\_PALETTE, которое является индексом палитры стандартного объекта из перечисления StockObject (раздел 2.1.31). |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSelectPalette`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Получает или задает 32-битное беззнаковое целое, которое указывает либо индекс объекта LogPalette (раздел 2.2.17) в таблице объектов EMF, либо значение DEFAULT\_PALETTE, которое является индексом палитры стандартного объекта из перечисления StockObject (раздел 2.1.31).

Это значение НЕ ДОЛЖНО быть нулём или индексом любого другого стандартного объекта.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает либо индекс объекта LogPalette (раздел 2.2.17) в таблице объектов EMF, либо значение DEFAULT\_PALETTE, которое является индексом палитры стандартного объекта из перечисления StockObject (раздел 2.1.31).

Это значение НЕ ДОЛЖНО быть нулём или индексом любого другого стандартного объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

