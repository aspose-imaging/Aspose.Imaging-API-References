---
title: "EmfSetColorAdjustment"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETCOLORADJUSTMENT задает свойства коррекции цвета в контексте устройства воспроизведения."
type: docs
weight: 122
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

Запись EMR\_SETCOLORADJUSTMENT определяет свойства коррекции цвета в контексте устройства воспроизведения.

Значения коррекции цвета используются для корректировки входного цвета исходного битмапа при графических операциях, выполняемых записями EMR\_STRETCHBLT и EMR\_STRETCHDIBITS, когда режим STRETCH\_HALFTONE установлен из перечисления StretchMode (раздел 2.1.32). Объект ColorAdjustment, указанный этой записью, ДОЛЖЕН использоваться в графических операциях, требующих объект ColorAdjustment, пока другой объект ColorAdjustment не будет указан другой записью EMR\_SETCOLORADJUSTMENT или пока объект не будет удалён записью EMR\_DELETEOBJECT.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetColorAdjustment`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Получает или задает объект ColorAdjustment (раздел 2.2.2), который определяет значения коррекции цвета. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Получает или задает объект ColorAdjustment (раздел 2.2.2), который определяет значения коррекции цвета. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetColorAdjustment`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Получает или задает объект ColorAdjustment (раздел 2.2.2), который определяет значения коррекции цвета.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Получает или задает объект ColorAdjustment (раздел 2.2.2), который определяет значения коррекции цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

