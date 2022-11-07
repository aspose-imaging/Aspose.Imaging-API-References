---
title: Brush
second_title: Aspose.Imaging for Java API Reference
description: The base brush class.
type: docs
weight: 13
url: /java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

The base brush class.
## Constructors

| Constructor | Description |
| --- | --- |
| [Brush()](#Brush--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getOpacity()](#getOpacity--) | Gets the brush opacity. |
| [setOpacity(float value)](#setOpacity-float-) | Sets the brush opacity. |
| [deepClone()](#deepClone--) | Creates a new deep clone of the current `Brush`. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Returns:**
float - The brush opacity value.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The brush opacity value. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Creates a new deep clone of the current `Brush`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
