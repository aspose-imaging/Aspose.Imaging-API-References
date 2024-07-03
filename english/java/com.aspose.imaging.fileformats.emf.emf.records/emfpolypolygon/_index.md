---
title: EmfPolyPolygon
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYPOLYGON record specifies a series of closed polygons.
type: docs
weight: 92
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolypolyshape)
```
public final class EmfPolyPolygon extends EmfPolyPolyShape
```

The EMR\_POLYPOLYGON record specifies a series of closed polygons.

Each polygon SHOULD be outlined using the current pen, and filled using the current brush and polygon fill mode that are defined in the playback device context. The polygons defined by this record can overlap.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyPolygon(EmfRecord source)](#EmfPolyPolygon-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyPolygon` class. |
| [EmfPolyPolygon()](#EmfPolyPolygon--) | Initializes a new instance of the `EmfPolyPolygon` class. |
### EmfPolyPolygon(EmfRecord source) {#EmfPolyPolygon-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyPolygon(EmfRecord source)
```


Initializes a new instance of the `EmfPolyPolygon` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyPolygon() {#EmfPolyPolygon--}
```
public EmfPolyPolygon()
```


Initializes a new instance of the `EmfPolyPolygon` class.

