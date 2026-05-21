---
title: "EmfPolyBezier"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_POLYBEZIER определяет одну или несколько кривых Безье."
type: docs
weight: 85
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

Запись EMR_POLYBEZIER задаёт одну или несколько кривых Безье.

Кубические кривые Безье определяются с использованием конечных точек и контрольных точек, указанных в поле aPoints. Первая кривая рисуется от первой точки до четвертой, используя вторую и третью точки в качестве контрольных. Каждая последующая кривая в последовательности требует ровно три дополнительные точки: конечная точка предыдущей кривой используется как начальная точка, следующие две точки последовательности являются контрольными точками, а третья — конечной точкой. Кубические кривые Безье ДОЛЖНЫ рисоваться с использованием текущей ручки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPolyBezier`. |
| [EmfPolyBezier()](#EmfPolyBezier--) | Инициализирует новый экземпляр класса `EmfPolyBezier`. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPolyBezier`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


Инициализирует новый экземпляр класса `EmfPolyBezier`.

