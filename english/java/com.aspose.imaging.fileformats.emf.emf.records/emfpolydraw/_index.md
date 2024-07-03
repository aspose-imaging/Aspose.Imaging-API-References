---
title: EmfPolyDraw
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYDRAW record specifies a set of line segments and Bezier curves.
type: docs
weight: 89
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

The EMR\_POLYDRAW record specifies a set of line segments and Bezier curves.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyDraw` class. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Initializes a new instance of the [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) class. |
## Methods

| Method | Description |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Gets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Sets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Initializes a new instance of the `EmfPolyDraw` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Initializes a new instance of the [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) class.

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Gets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. This value MUST be in the Point (section 2.1.26) enumeration.

**Returns:**
byte[] - a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Sets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. This value MUST be in the Point (section 2.1.26) enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. |

