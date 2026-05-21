---
title: "EmfCreatePalette"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_CREATEPALETTE определяет логическую палитру для графических операций."
type: docs
weight: 40
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

Запись EMR\_CREATEPALETTE определяет логическую палитру для графических операций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCreatePalette`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhPal()](#getIhPal--) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс логического объекта палитры в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет индекс логического объекта палитры в таблице объектов EMF (раздел 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | Получает или задает объект LogPalette (раздел 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Получает или задает объект LogPalette (раздел 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCreatePalette`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Получает или задает 32-битное беззнаковое целое, которое определяет индекс логического объекта палитры в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект мог быть повторно использован или изменён.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет индекс логического объекта палитры в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект мог быть повторно использован или изменён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Получает или задает объект LogPalette (раздел 2.2.17). Поле Version этого объекта ДОЛЖНО быть установлено в 0x0300. Если значение NumberOfEntries в этом объекте равно нулю, обработка этой записи ДОЛЖНА завершиться с ошибкой.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Получает или задает объект LogPalette (раздел 2.2.17). Поле Version этого объекта ДОЛЖНО быть установлено в 0x0300. Если значение NumberOfEntries в этом объекте равно нулю, обработка этой записи ДОЛЖНА завершиться с ошибкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

