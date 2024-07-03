---
title: EmfPolyDraw16
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYDRAW16 record specifies a set of line segments and Bezier curves.
type: docs
weight: 90
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

The EMR\_POLYDRAW16 record specifies a set of line segments and Bezier curves.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyDraw16` class. |
## Methods

| Method | Description |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Gets or sets a Count length array of bytes that specifies the point types. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Sets a Count length array of bytes that specifies the point types. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Initializes a new instance of the `EmfPolyDraw16` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Gets or sets a Count length array of bytes that specifies the point types. This value MUST be in the Point (section 2.1.26) enumeration.

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Sets a Count length array of bytes that specifies the point types. This value MUST be in the Point (section 2.1.26) enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | a Count length array of bytes that specifies the point types. |

