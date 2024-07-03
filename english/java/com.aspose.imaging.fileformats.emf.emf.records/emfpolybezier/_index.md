---
title: EmfPolyBezier
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYBEZIER record specifies one or more Bezier curves.
type: docs
weight: 85
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

The EMR\_POLYBEZIER record specifies one or more Bezier curves.

Cubic Bezier curves are defined using the endpoints and control points specified by the aPoints field. The first curve is drawn from the first point to the fourth point, using the second and third points as control points. Each subsequent curve in the sequence needs exactly three more points: the ending point of the previous curve is used as the starting point, the next two points in the sequence are control points, and the third is the ending point. The cubic Bezier curves SHOULD be drawn using the current pen
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyBezier` class. |
| [EmfPolyBezier()](#EmfPolyBezier--) | Initializes a new instance of the `EmfPolyBezier` class. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


Initializes a new instance of the `EmfPolyBezier` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


Initializes a new instance of the `EmfPolyBezier` class.

