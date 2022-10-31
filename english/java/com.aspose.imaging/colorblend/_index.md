---
title: ColorBlend
second_title: Aspose.Imaging for Java API Reference
description: Defines arrays of colors and positions used for interpolating color blending in a multicolor gradient.
type: docs
weight: 22
url: /java/com.aspose.imaging/colorblend/
---
**Inheritance:**
java.lang.Object
```
public final class ColorBlend
```

Defines arrays of colors and positions used for interpolating color blending in a multicolor gradient. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorBlend()](#ColorBlend--) | Initializes a new instance of the `com.aspose.imaging.ColorBlend` class. |
| [ColorBlend(int count)](#ColorBlend-int-) | Initializes a new instance of the `com.aspose.imaging.ColorBlend` class with the specified number of colors and positions. |
## Methods

| Method | Description |
| --- | --- |
| [getColors()](#getColors--) | Gets or sets an array of colors that represents the colors to use at corresponding positions along a gradient. |
| [setColors(Color[] value)](#setColors-com.aspose.imaging.Color---) |  |
| [getPositions()](#getPositions--) | Gets or sets the positions along a gradient line. |
| [setPositions(float[] value)](#setPositions-float---) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests whether the specified object is a `com.aspose.imaging.ColorBlend` class and is equivalent to this `com.aspose.imaging.ColorBlend` class. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### ColorBlend() {#ColorBlend--}
```
public ColorBlend()
```


Initializes a new instance of the `com.aspose.imaging.ColorBlend` class.

### ColorBlend(int count) {#ColorBlend-int-}
```
public ColorBlend(int count)
```


Initializes a new instance of the `com.aspose.imaging.ColorBlend` class with the specified number of colors and positions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int | The number of colors and positions in this `com.aspose.imaging.ColorBlend`. |

### getColors() {#getColors--}
```
public Color[] getColors()
```


Gets or sets an array of colors that represents the colors to use at corresponding positions along a gradient.

**Returns:**
com.aspose.imaging.Color[] - An array of `com.aspose.imaging.Color` structures that represents the colors to use at corresponding positions along a gradient.
### setColors(Color[] value) {#setColors-com.aspose.imaging.Color---}
```
public void setColors(Color[] value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) |  |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Gets or sets the positions along a gradient line.

**Returns:**
float[] - An array of values that specify percentages of distance along the gradient line.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests whether the specified object is a `com.aspose.imaging.ColorBlend` class and is equivalent to this `com.aspose.imaging.ColorBlend` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to test. |

**Returns:**
boolean - True if `obj` is a `com.aspose.imaging.ColorBlend` class equivalent to this `com.aspose.imaging.ColorBlend` class; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
