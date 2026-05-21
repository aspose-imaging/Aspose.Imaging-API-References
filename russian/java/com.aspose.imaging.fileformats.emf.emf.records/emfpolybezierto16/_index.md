---
title: "EmfPolyBezierTo16"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_POLYBEZIERTO16 определяет одну или несколько кривых Безье, основанных на текущей позиции."
type: docs
weight: 88
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo16 extends EmfPolyShape
```

Запись EMR_POLYBEZIERTO16 задаёт одну или несколько кривых Безье, основанных на текущей позиции.

Кубические кривые Безье определяются с использованием конечных точек и контрольных точек, указанных в поле aPoints. Первая кривая рисуется от первой точки до четвертой, используя вторую и третью точки в качестве контрольных. Каждая последующая кривая в последовательности требует ровно три дополнительные точки: конечная точка предыдущей кривой используется как начальная точка, следующие две точки последовательности являются контрольными точками, а третья — конечной точкой. Кубические кривые Безье ДОЛЖНЫ рисоваться с использованием текущей ручки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPolyBezierTo16(EmfRecord record)](#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPolyBezierTo16`. |
| [EmfPolyBezierTo16()](#EmfPolyBezierTo16--) | Инициализирует новый экземпляр класса `EmfPolyBezierTo16`. |
### EmfPolyBezierTo16(EmfRecord record) {#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo16(EmfRecord record)
```


Инициализирует новый экземпляр класса `EmfPolyBezierTo16`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Запись. |

### EmfPolyBezierTo16() {#EmfPolyBezierTo16--}
```
public EmfPolyBezierTo16()
```


Инициализирует новый экземпляр класса `EmfPolyBezierTo16`.

