---
title: SizeF
second_title: Aspose.Imaging for Java API Reference
description: Stores an ordered pair of floating-point numbers typically the width and height of a rectangle.
type: docs
weight: 106
url: /com.aspose.imaging/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.imaging.SizeF-) | Initializes a new instance of the `Aspose.Imaging.SizeF` structure from the specified `Aspose.Imaging.SizeF`. |
| [SizeF(PointF point)](#SizeF-com.aspose.imaging.PointF-) | Initializes a new instance of the `Aspose.Imaging.SizeF` structure from the specified `Aspose.Imaging.PointF`. |
| [SizeF(float width, float height)](#SizeF-float-float-) | Initializes a new instance of the `Aspose.Imaging.SizeF` structure from the specified dimensions. |
## Methods

| Method | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gets a new instance of the `Aspose.Imaging.SizeF` structure that has `Aspose.Imaging.SizeF.Width` and `Aspose.Imaging.SizeF.Height` values set to zero. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this `Aspose.Imaging.SizeF` has zero width and height. |
| [getWidth()](#getWidth--) | Gets or sets the horizontal component of this `Aspose.Imaging.SizeF`. |
| [setWidth(float value)](#setWidth-float-) | Gets or sets the horizontal component of this `Aspose.Imaging.SizeF`. |
| [getHeight()](#getHeight--) | Gets or sets the vertical component of this `Aspose.Imaging.SizeF`. |
| [setHeight(float value)](#setHeight-float-) | Gets or sets the vertical component of this `Aspose.Imaging.SizeF`. |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Adds the width and height of one `Aspose.Imaging.SizeF` structure to the width and height of another `Aspose.Imaging.SizeF` structure. |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Subtracts the width and height of one `Aspose.Imaging.SizeF` structure from the width and height of another `Aspose.Imaging.SizeF` structure. |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Tests whether two `Aspose.Imaging.SizeF` structures are equal. |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Tests whether two `Aspose.Imaging.SizeF` structures are different. |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.imaging.SizeF-) | Converts the specified `Aspose.Imaging.SizeF` to a `Aspose.Imaging.PointF`. |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Adds the width and height of one `Aspose.Imaging.SizeF` structure to the width and height of another `Aspose.Imaging.SizeF` structure. |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Subtracts the width and height of one `Aspose.Imaging.SizeF` structure from the width and height of another `Aspose.Imaging.SizeF` structure. |
| [toPointF()](#toPointF--) | Converts a `Aspose.Imaging.SizeF` to a `Aspose.Imaging.PointF`. |
| [toSize()](#toSize--) | Converts a `Aspose.Imaging.SizeF` to a `Aspose.Imaging.Size` structure with truncated size values. |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests to see whether the specified object is a `Aspose.Imaging.SizeF` with the same dimensions as this `Aspose.Imaging.SizeF`. |
| [hashCode()](#hashCode--) | Returns a hash code for this `Aspose.Imaging.Size` structure. |
| [toString()](#toString--) | Creates a human-readable string that represents this `Aspose.Imaging.SizeF`. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.imaging.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.imaging.SizeF-}
```
public SizeF(SizeF size)
```


Initializes a new instance of the `Aspose.Imaging.SizeF` structure from the specified `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` from which to create the new `Aspose.Imaging.SizeF`. |

### SizeF(PointF point) {#SizeF-com.aspose.imaging.PointF-}
```
public SizeF(PointF point)
```


Initializes a new instance of the `Aspose.Imaging.SizeF` structure from the specified `Aspose.Imaging.PointF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `Aspose.Imaging.PointF` from which to initialize this `Aspose.Imaging.SizeF`. |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Initializes a new instance of the `Aspose.Imaging.SizeF` structure from the specified dimensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The width component of the new `Aspose.Imaging.SizeF`. |
| height | float | The height component of the new `Aspose.Imaging.SizeF`. |

### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


Gets a new instance of the `Aspose.Imaging.SizeF` structure that has `Aspose.Imaging.SizeF.Width` and `Aspose.Imaging.SizeF.Height` values set to zero.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this `Aspose.Imaging.SizeF` has zero width and height.

**Returns:**
boolean - This property returns true when this `Aspose.Imaging.SizeF` has both a width and height of zero; otherwise, false.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Gets or sets the horizontal component of this `Aspose.Imaging.SizeF`.

**Returns:**
float - The horizontal component of this `Aspose.Imaging.SizeF`, typically measured in pixels.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Gets or sets the horizontal component of this `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Gets or sets the vertical component of this `Aspose.Imaging.SizeF`.

**Returns:**
float - The vertical component of this `Aspose.Imaging.SizeF`, typically measured in pixels.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Gets or sets the vertical component of this `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


Adds the width and height of one `Aspose.Imaging.SizeF` structure to the width and height of another `Aspose.Imaging.SizeF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | The first `Aspose.Imaging.SizeF` to add. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | The second `Aspose.Imaging.SizeF` to add. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


Subtracts the width and height of one `Aspose.Imaging.SizeF` structure from the width and height of another `Aspose.Imaging.SizeF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` on the left side of the subtraction operator. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` on the right side of the subtraction operator. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` that is the result of the subtraction operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


Tests whether two `Aspose.Imaging.SizeF` structures are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure on the left side of the equality operator. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure on the right of the equality operator. |

**Returns:**
boolean - This operator returns true if `size1` and `size2` have equal width and height; otherwise, false.
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


Tests whether two `Aspose.Imaging.SizeF` structures are different.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure on the left of the inequality operator. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure on the right of the inequality operator. |

**Returns:**
boolean - This operator returns true if `size1` and `size2` differ either in width or height; false if `size1` and `size2` are equal.
### to_PointF(SizeF size) {#to-PointF-com.aspose.imaging.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


Converts the specified `Aspose.Imaging.SizeF` to a `Aspose.Imaging.PointF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure to be converted |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `Aspose.Imaging.PointF` structure to which this operator converts.
### add(SizeF size1, SizeF size2) {#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


Adds the width and height of one `Aspose.Imaging.SizeF` structure to the width and height of another `Aspose.Imaging.SizeF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | The first `Aspose.Imaging.SizeF` to add. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | The second `Aspose.Imaging.SizeF` to add. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


Subtracts the width and height of one `Aspose.Imaging.SizeF` structure from the width and height of another `Aspose.Imaging.SizeF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure on the left side of the subtraction operator. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure on the right side of the subtraction operator. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` that is a result of the subtraction operation.
### toPointF() {#toPointF--}
```
public PointF toPointF()
```


Converts a `Aspose.Imaging.SizeF` to a `Aspose.Imaging.PointF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns a `Aspose.Imaging.PointF` structure.
### toSize() {#toSize--}
```
public Size toSize()
```


Converts a `Aspose.Imaging.SizeF` to a `Aspose.Imaging.Size` structure with truncated size values.

**Returns:**
[Size](../../com.aspose.imaging/size) - Returns a `Aspose.Imaging.Size` structure.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests to see whether the specified object is a `Aspose.Imaging.SizeF` with the same dimensions as this `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to test. |

**Returns:**
boolean - This method returns true if `obj` is a `Aspose.Imaging.SizeF` and has the same width and height as this `Aspose.Imaging.SizeF`; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this `Aspose.Imaging.Size` structure.

**Returns:**
int - An integer value that specifies a hash value for this `Aspose.Imaging.Size` structure.
### toString() {#toString--}
```
public String toString()
```


Creates a human-readable string that represents this `Aspose.Imaging.SizeF`.

**Returns:**
java.lang.String - A string that represents this `Aspose.Imaging.SizeF`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.imaging.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.imaging/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.imaging/sizef) |  |
| obj2 | [SizeF](../../com.aspose.imaging/sizef) |  |

**Returns:**
boolean
