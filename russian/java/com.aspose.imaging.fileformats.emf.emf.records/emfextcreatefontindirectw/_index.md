---
title: "EmfExtCreateFontIndirectW"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EXTCREATEFONTINDIRECTW определяет логический шрифт для графических операций."
type: docs
weight: 51
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

Запись EMR\_EXTCREATEFONTINDIRECTW определяет логический шрифт для графических операций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfExtCreateFontIndirectW`. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | Инициализирует новый экземпляр класса `EmfExtCreateFontIndirectW`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет индекс объекта логического шрифта в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhFonts(int value)](#setIhFonts-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет индекс объекта логического шрифта в таблице объектов EMF (раздел 3.1.1.1). |
| [getElw()](#getElw--) | Получает или задает объект LogFontExDv (раздел 2.2.15), который определяет логический шрифт. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Получает или задает объект LogFontExDv (раздел 2.2.15), который определяет логический шрифт. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfExtCreateFontIndirectW`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


Инициализирует новый экземпляр класса `EmfExtCreateFontIndirectW`.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


Получает или задает 32‑битное беззнаковое целое число, которое определяет индекс объекта логического шрифта в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект мог быть повторно использован или изменён.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


Получает или задает 32‑битное беззнаковое целое число, которое определяет индекс объекта логического шрифта в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект мог быть повторно использован или изменён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Получает или задает объект LogFontExDv (раздел 2.2.15), который определяет логический шрифт. Вместо него может присутствовать объект LogFont 2.2.13.[90] Процесс определения типа объекта в этом поле описан ниже.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Получает или задает объект LogFontExDv (раздел 2.2.15), который определяет логический шрифт. Вместо него может присутствовать объект LogFont 2.2.13.[90] Процесс определения типа объекта в этом поле описан ниже.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

