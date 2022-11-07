---
title: Blend
second_title: Aspose.Imaging for Java API Reference
description: Defines a blend pattern.
type: docs
weight: 12
url: /java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Defines a blend pattern. This class cannot be inherited.

The typical blend class usage is defining a blend pattern for brush. And thus the blend properties should be initialized carefully. Null arrays are not allowed. The brush will throw the appropriate exception if blend factors or positions array are empty or their length is not the same. If there are two or more elements in the positions array then the first element should be 0 and the last should be 1.
## Constructors

| Constructor | Description |
| --- | --- |
| [Blend()](#Blend--) | Initializes a new instance of the `Blend` class. |
| [Blend(int count)](#Blend-int-) | Initializes a new instance of the `Blend` class with the specified number of factors and positions. |
## Methods

| Method | Description |
| --- | --- |
| [getFactors()](#getFactors--) | Gets the array of blend factors for the gradient. |
| [setFactors(float[] value)](#setFactors-float---) | Sets the array of blend factors for the gradient. |
| [getPositions()](#getPositions--) | Gets the array of blend positions for the gradient. |
| [setPositions(float[] value)](#setPositions-float---) | Sets the array of blend positions for the gradient. |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests whether the specified object is a `com.aspose.imaging.Blend` class and is equivalent to this `com.aspose.imaging.Blend` class. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### Blend() {#Blend--}
```
public Blend()
```


Initializes a new instance of the `Blend` class. The number of elements in the factor and blend arrays will be equal to 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initializes a new instance of the `Blend` class with the specified number of factors and positions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int | The number of elements in the factor and position arrays. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Gets the array of blend factors for the gradient.

**Returns:**
float[] - The array of blend factors that specify the percentages of the starting color and the ending color to be used at the corresponding position.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Sets the array of blend factors for the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] | The array of blend factors that specify the percentages of the starting color and the ending color to be used at the corresponding position. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Gets the array of blend positions for the gradient.

**Returns:**
float[] - The array of blend positions that specify the percentages of distance along the gradient line.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Sets the array of blend positions for the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] | The array of blend positions that specify the percentages of distance along the gradient line. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests whether the specified object is a `com.aspose.imaging.Blend` class and is equivalent to this `com.aspose.imaging.Blend` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to test. |

**Returns:**
boolean - True if `obj` is a `com.aspose.imaging.Blend` class equivalent to this `com.aspose.imaging.Blend` class; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
