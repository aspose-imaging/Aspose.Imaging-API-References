---
title: IOrderedShape
second_title: Aspose.Imaging for Java API Reference
description: Represents an ordered shape.
type: docs
weight: 140
url: /java/com.aspose.imaging/iorderedshape/
---```
public interface IOrderedShape
```

Represents an ordered shape. An ordered shape is a continuous set of points having a start point and end point. The continuous set of points connected using a specific rule.
## Methods

| Method | Description |
| --- | --- |
| [getStartPoint()](#getStartPoint--) | Gets the starting shape point. |
| [getEndPoint()](#getEndPoint--) | Gets the ending shape point. |
| [isClosed()](#isClosed--) | Gets a value indicating whether ordered shape is closed. |
| [setClosed(boolean value)](#setClosed-boolean-) | Sets a value indicating whether ordered shape is closed. |
| [reverse()](#reverse--) | Reverses the order of points for this shape. |
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Gets the starting shape point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The starting shape point.
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Gets the ending shape point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The ending shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Gets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning.

**Returns:**
boolean - `true` if this ordered shape is closed; otherwise, `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Sets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if this ordered shape is closed; otherwise, `false`. |

### reverse() {#reverse--}
```
public abstract void reverse()
```


Reverses the order of points for this shape.

