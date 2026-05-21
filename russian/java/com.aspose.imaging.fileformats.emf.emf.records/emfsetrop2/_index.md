---
title: "EmfSetRop2"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETROP2 определяет режим бинарной растровой операции."
type: docs
weight: 137
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

Запись EMR\_SETROP2 задает режим бинарной растровой операции.

Режимы смешивания бинарных растровых операций определяют, как комбинировать цвета источника и назначения при рисовании текущей ручкой. Режимы смешивания представляют собой коды бинарных растровых операций, охватывающие все возможные булевы функции двух переменных, используя бинарные операции И (AND), ИЛИ (OR) и исключающее ИЛИ (XOR), а также унарную операцию НЕ (NOT). Этот режим предназначен только для растровых устройств; он недоступен для векторных устройств.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetRop2`. |
| [EmfSetRop2()](#EmfSetRop2--) | Инициализирует новый экземпляр класса `EmfSetRop2`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Получает или задает 32‑битное беззнаковое целое, которое определяет режим растровой операции и ДОЛЖНО находиться в перечислении WMF Binary Raster Op ([MS-WMF] раздел 2.1.1.2). |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет режим растровой операции и ДОЛЖНО находиться в перечислении WMF Binary Raster Op ([MS-WMF] раздел 2.1.1.2). |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetRop2`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


Инициализирует новый экземпляр класса `EmfSetRop2`.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет режим растровой операции и ДОЛЖНО находиться в перечислении WMF Binary Raster Op ([MS-WMF] раздел 2.1.1.2).

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет режим растровой операции и ДОЛЖНО находиться в перечислении WMF Binary Raster Op ([MS-WMF] раздел 2.1.1.2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

