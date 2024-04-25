---
title: EmfPlusDrawLines
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawlLines record specifies drawing a series of connected lines
type: docs
weight: 24
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

The EmfPlusDrawlLines record specifies drawing a series of connected lines
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawLines` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. |
| [getRelative()](#getRelative--) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. |
| [setRelative(boolean value)](#setRelative-boolean-) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. |
| [getClosedShape()](#getClosedShape--) | Gets or sets a value indicating whether [closed shape]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | Gets or sets a value indicating whether [closed shape]. |
| [getPointData()](#getPointData--) | Gets or sets the point data An array of Count points that specify the starting and ending points of the lines to be drawn. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Gets or sets the point data An array of Count points that specify the starting and ending points of the lines to be drawn. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawLines` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the lines. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the lines. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored

Value: `true` if compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored

Value: `true` if relative; otherwise, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored

Value: `true` if relative; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


Gets or sets a value indicating whether [closed shape].

Value: `true` if [closed shape]; otherwise, `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


Gets or sets a value indicating whether [closed shape].

Value: `true` if [closed shape]; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Gets or sets the point data An array of Count points that specify the starting and ending points of the lines to be drawn.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Gets or sets the point data An array of Count points that specify the starting and ending points of the lines to be drawn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

