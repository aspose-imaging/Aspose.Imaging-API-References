---
title: EmfPlusPathPointTypeRle
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.
type: docs
weight: 62
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 bit): If set, the path points are on a Bezier curve. If clear, the path points are on a graphics line. RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field. PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Gets or sets the data. |
| [setData(int value)](#setData-int-) | Gets or sets the data. |
| [getBezier()](#getBezier--) | Gets or sets a value indicating whether this `EmfPlusPathPointTypeRle` is bezier. |
| [setBezier(boolean value)](#setBezier-boolean-) | Gets or sets a value indicating whether this `EmfPlusPathPointTypeRle` is bezier. |
| [getRunCount()](#getRunCount--) | Gets or sets the run count. |
| [setRunCount(byte value)](#setRunCount-byte-) | Gets or sets the run count. |
| [getPointType()](#getPointType--) | Gets or sets the type of the point. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Gets or sets the type of the point. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Gets or sets the data.

Value: The data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


Gets or sets a value indicating whether this `EmfPlusPathPointTypeRle` is bezier. If set, the path points are on a Bezier curve. If clear, the path points are on a graphics line.

Value: `true` if bezier; otherwise, `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusPathPointTypeRle` is bezier. If set, the path points are on a Bezier curve. If clear, the path points are on a graphics line.

Value: `true` if bezier; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Gets or sets the run count. RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field

Value: The run count.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Gets or sets the run count. RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field

Value: The run count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Gets or sets the type of the point. PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

Value: The type of the point.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Gets or sets the type of the point. PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

Value: The type of the point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

