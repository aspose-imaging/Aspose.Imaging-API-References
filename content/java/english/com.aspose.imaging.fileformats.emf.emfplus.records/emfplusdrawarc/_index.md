---
title: EmfPlusDrawArc
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawArc record specifies drawing the arc of an ellipse.
type: docs
weight: 16
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

The EmfPlusDrawArc record specifies drawing the arc of an ellipse.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawArc` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDataSize()](#getDataSize--) | Gets the size of the data. |
| [setDataSize(int value)](#setDataSize-int-) | Sets the size of the data. |
| [getRectFloat()](#getRectFloat--) | Gets a value indicating whether the data contains EmfPlusRectF or EmfPlusRect records This bit indicates whether the data in the RectData field is compressed. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Sets a value indicating whether the data contains EmfPlusRectF or EmfPlusRect records This bit indicates whether the data in the RectData field is compressed. |
| [getObjectId()](#getObjectId--) | Gets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Sets the object identifier. |
| [getSize()](#getSize--) | Gets the size. |
| [setSize(int value)](#setSize-int-) | Sets the size. |
| [getStartAngle()](#getStartAngle--) | Gets the start angle A 32-bit non-negative floating-point value that specifies the angle between the x-axis and the starting point of the arc. |
| [setStartAngle(float value)](#setStartAngle-float-) | Sets the start angle A 32-bit non-negative floating-point value that specifies the angle between the x-axis and the starting point of the arc. |
| [getSweepAngle()](#getSweepAngle--) | Gets the sweep angle A 32-bit floating-point value that specifies the extent of the arc to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. |
| [getRectangleData()](#getRectangleData--) | Gets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that is collinear with the arc. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that is collinear with the arc. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawArc` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Gets the size of the data. A 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes of record-specific data that follows. For this record type, the value MUST be one of the following: 0x00000010 If the C bit is set in the Flags field. 0x00000018 If the C bit is clear in the Flags field.

**Returns:**
int - The size of the data.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Sets the size of the data. A 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes of record-specific data that follows. For this record type, the value MUST be one of the following: 0x00000010 If the C bit is set in the Flags field. 0x00000018 If the C bit is clear in the Flags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The size of the data. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Gets a value indicating whether the data contains EmfPlusRectF or EmfPlusRect records This bit indicates whether the data in the RectData field is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

**Returns:**
boolean - `true` if float; otherwise, `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Sets a value indicating whether the data contains EmfPlusRectF or EmfPlusRect records This bit indicates whether the data in the RectData field is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if float; otherwise, `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the arc. The value MUST be zero to 63, inclusive.

**Returns:**
byte - The object identifier.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the arc. The value MUST be zero to 63, inclusive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The object identifier. |

### getSize() {#getSize--}
```
public int getSize()
```


Gets the size. A 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. For this record type, the value MUST be one of the following: 0x0000001C If the C bit is set in the Flags field. 0x00000024 If the C bit is clear in the Flags field

**Returns:**
int - The size.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Sets the size. A 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. For this record type, the value MUST be one of the following: 0x0000001C If the C bit is set in the Flags field. 0x00000024 If the C bit is clear in the Flags field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The size. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Gets the start angle A 32-bit non-negative floating-point value that specifies the angle between the x-axis and the starting point of the arc. Any value is acceptable, but it MUST be interpreted modulo 360, with the result that is used being in the range 0.0 inclusive to 360.0 exclusive.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Sets the start angle A 32-bit non-negative floating-point value that specifies the angle between the x-axis and the starting point of the arc. Any value is acceptable, but it MUST be interpreted modulo 360, with the result that is used being in the range 0.0 inclusive to 360.0 exclusive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Gets the sweep angle A 32-bit floating-point value that specifies the extent of the arc to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined in a clockwise direction, and a negative value indicates that the sweep is defined in a counter-clockwise direction.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined in a clockwise direction, and a negative value indicates that the sweep is defined in a counter-clockwise direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Gets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that is collinear with the arc. This rectangle defines the position, size, and shape of the arc. The type of object in this field is specified by the value of the Flags field.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that is collinear with the arc. This rectangle defines the position, size, and shape of the arc. The type of object in this field is specified by the value of the Flags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

