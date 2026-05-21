---
title: "EmfPlusSetClipRect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetClipRect объединяет текущую область отсечения с прямоугольником."
type: docs
weight: 56
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

Запись EmfPlusSetClipRect объединяет текущую область отсечения с прямоугольником.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetClipRect`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCm()](#getCm--) | Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. |
| [setCm(byte value)](#setCm-byte-) | Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. |
| [getClipRect()](#getClipRect--) | Получает или задает объект EmfPlusRectF (section 2.2.2.39), который определяет прямоугольник, используемый в операции CombineMode. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | Получает или задает объект EmfPlusRectF (section 2.2.2.39), который определяет прямоугольник, используемый в операции CombineMode. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetClipRect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getCm() {#getCm--}
```
public byte getCm()
```


Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. См. перечисление CombineMode (раздел 2.1.1.4) для значений.

Значение: cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. См. перечисление CombineMode (раздел 2.1.1.4) для значений.

Значение: cm.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


Получает или задает объект EmfPlusRectF (section 2.2.2.39), который определяет прямоугольник, используемый в операции CombineMode.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


Получает или задает объект EmfPlusRectF (section 2.2.2.39), который определяет прямоугольник, используемый в операции CombineMode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

