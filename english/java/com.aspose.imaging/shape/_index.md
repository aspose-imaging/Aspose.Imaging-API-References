---
title: Shape
second_title: Aspose.Imaging for Java API Reference
description: The shape.
type: docs
weight: 103
url: /java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

The shape. A continuous set of points connected using a specific rule.
## Constructors

| Constructor | Description |
| --- | --- |
| [Shape()](#Shape--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Gets the shape's center.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Gets the shape segments.

**Returns:**
com.aspose.imaging.ShapeSegment[] - The shape segments.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Gets a value indicating whether shape has segments.

**Returns:**
boolean - `True` if shape has segments; otherwise, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object obj)
```


Check if objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public abstract int hashCode()
```




**Returns:**
int
