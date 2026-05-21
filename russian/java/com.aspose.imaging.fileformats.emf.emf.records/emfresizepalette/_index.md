---
title: "EmfResizePalette"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_RESIZEPALETTE увеличивает или уменьшает размер существующего объекта LogPalette раздел 2.2.17."
type: docs
weight: 108
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

Запись EMR\_RESIZEPALETTE увеличивает или уменьшает размер существующего объекта LogPalette (раздел 2.2.17).

Новый размер объекта LogPalette ДОЛЖЕН быть отражён в поле NumberOfEntries этой структуры.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfResizePalette`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhPal()](#getIhPal--) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс объекта палитры в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает индекс объекта палитры в таблице объектов EMF (раздел 3.1.1.1). |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfResizePalette`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс объекта палитры в таблице объектов EMF (раздел 3.1.1.1).

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает индекс объекта палитры в таблице объектов EMF (раздел 3.1.1.1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

