---
title: EmfPolylineTo16
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position.
type: docs
weight: 104
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolylineTo16 extends EmfPolyShape
```

The EMR\_POLYLINETO16 record specifies one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the aPoints field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by aPoints.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolylineTo16(EmfRecord source)](#EmfPolylineTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolylineTo16` class. |
| [EmfPolylineTo16()](#EmfPolylineTo16--) | Initializes a new instance of the `EmfPolylineTo16` class. |
### EmfPolylineTo16(EmfRecord source) {#EmfPolylineTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolylineTo16(EmfRecord source)
```


Initializes a new instance of the `EmfPolylineTo16` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolylineTo16() {#EmfPolylineTo16--}
```
public EmfPolylineTo16()
```


Initializes a new instance of the `EmfPolylineTo16` class.

