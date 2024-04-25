---
title: EmfPlusDrawPie
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.
type: docs
weight: 26
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawPie` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether the PointData is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether the PointData is compressed. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getStartAngle()](#getStartAngle--) | Gets or sets the start angle A 32-bit, non-negative floating-point value that specifies the angle between the x-axis and the starting point of the pie wedge. |
| [setStartAngle(float value)](#setStartAngle-float-) | Gets or sets the start angle A 32-bit, non-negative floating-point value that specifies the angle between the x-axis and the starting point of the pie wedge. |
| [getSweepAngle()](#getSweepAngle--) | Gets or sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc that defines the pie wedge to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Gets or sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc that defines the pie wedge to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. |
| [getRectData()](#getRectData--) | Gets or sets the rectangle datas Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that contains the pie wedge. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Gets or sets the rectangle datas Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that contains the pie wedge. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawPie` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

Value: `true` if compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the pie. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the pie. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Gets or sets the start angle A 32-bit, non-negative floating-point value that specifies the angle between the x-axis and the starting point of the pie wedge. Any value is acceptable, but it MUST be interpreted modulo 360, with the result that is used being in the range 0.0 inclusive to 360.0 exclusive.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Gets or sets the start angle A 32-bit, non-negative floating-point value that specifies the angle between the x-axis and the starting point of the pie wedge. Any value is acceptable, but it MUST be interpreted modulo 360, with the result that is used being in the range 0.0 inclusive to 360.0 exclusive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Gets or sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc that defines the pie wedge to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined in a clockwise direction, and a negative value indicates that the sweep is defined in a counter-clockwise direction.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Gets or sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc that defines the pie wedge to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined in a clockwise direction, and a negative value indicates that the sweep is defined in a counter-clockwise direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Gets or sets the rectangle datas Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that contains the pie wedge. This rectangle defines the position, size, and shape of the pie. The type of object in this field is specified by the value of the Flags field.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Gets or sets the rectangle datas Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that contains the pie wedge. This rectangle defines the position, size, and shape of the pie. The type of object in this field is specified by the value of the Flags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

