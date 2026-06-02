---
title: "EmfPolylineTo16"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_POLYLINETO16 определяет одну или несколько прямых линий, основанных на текущей позиции."
type: docs
weight: 104
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolylineTo16 extends EmfPolyShape
```

Запись EMR\_POLYLINETO16 определяет одну или несколько прямых линий, основанных на текущей позиции. Линия рисуется от текущей позиции до первой точки, указанной в поле aPoints, с использованием текущей ручки. Для каждой последующей линии рисование выполняется от конечной точки предыдущей линии до следующей точки, указанной в aPoints.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPolylineTo16(EmfRecord source)](#EmfPolylineTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPolylineTo16`. |
| [EmfPolylineTo16()](#EmfPolylineTo16--) | Инициализирует новый экземпляр класса `EmfPolylineTo16`. |
### EmfPolylineTo16(EmfRecord source) {#EmfPolylineTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolylineTo16(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPolylineTo16`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfPolylineTo16() {#EmfPolylineTo16--}
```
public EmfPolylineTo16()
```


Инициализирует новый экземпляр класса `EmfPolylineTo16`.

