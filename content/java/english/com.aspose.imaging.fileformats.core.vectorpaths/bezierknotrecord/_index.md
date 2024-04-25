---
title: BezierKnotRecord
second_title: Aspose.Imaging for Java API Reference
description: Bezier Knot Record Class
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class BezierKnotRecord extends VectorPathRecord
```

Bezier Knot Record Class
## Constructors

| Constructor | Description |
| --- | --- |
| [BezierKnotRecord()](#BezierKnotRecord--) | Initializes a new instance of the [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) class. |
| [BezierKnotRecord(byte[] data)](#BezierKnotRecord-byte---) | Initializes a new instance of the [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Gets the path points. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Sets the path points. |
| [getPoints()](#getPoints--) | Gets the points. |
| [setPoints(Point[] value)](#setPoints-com.aspose.imaging.Point---) | Sets the points. |
| [isClosed()](#isClosed--) | Gets a value indicating whether this instance is closed. |
| [setClosed(boolean value)](#setClosed-boolean-) | Sets a value indicating whether this instance is closed. |
| [isLinked()](#isLinked--) | Gets a value indicating whether this instance is linked. |
| [setLinked(boolean value)](#setLinked-boolean-) | Sets a value indicating whether this instance is linked. |
| [isOpen()](#isOpen--) | Gets a value indicating whether this instance is open. |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets a value indicating whether this instance is open. |
| [getType()](#getType--) | Gets the type. |
### BezierKnotRecord() {#BezierKnotRecord--}
```
public BezierKnotRecord()
```


Initializes a new instance of the [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) class.

### BezierKnotRecord(byte[] data) {#BezierKnotRecord-byte---}
```
public BezierKnotRecord(byte[] data)
```


Initializes a new instance of the [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The record data. |

### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```


Gets the path points.

Value: The path points.

**Returns:**
com.aspose.imaging.PointF[] - the path points.
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public final void setPathPoints(PointF[] value)
```


Sets the path points.

Value: The path points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) | the path points. |

### getPoints() {#getPoints--}
```
public final Point[] getPoints()
```


Gets the points.

**Returns:**
com.aspose.imaging.Point[] - the points.
### setPoints(Point[] value) {#setPoints-com.aspose.imaging.Point---}
```
public final void setPoints(Point[] value)
```


Sets the points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | the points. |

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Gets a value indicating whether this instance is closed.

Value: `true` if this instance is closed; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance is closed.
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Sets a value indicating whether this instance is closed.

Value: `true` if this instance is closed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this instance is closed. |

### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Gets a value indicating whether this instance is linked.

Value: `true` if this instance is linked; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance is linked.
### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Sets a value indicating whether this instance is linked.

Value: `true` if this instance is linked; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this instance is linked. |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Gets a value indicating whether this instance is open.

Value: `true` if this instance is open; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance is open.
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Sets a value indicating whether this instance is open.

Value: `true` if this instance is open; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this instance is open. |

### getType() {#getType--}
```
public short getType()
```


Gets the type.

Value: The type.

**Returns:**
short - the type.
