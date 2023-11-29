---
title: TiffSRational
second_title: Aspose.Imaging for Java API Reference
description: The tiff rational type.
type: docs
weight: 15
url: /java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

The tiff rational type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Initializes a new instance of the `TiffSRational` class. |
| [TiffSRational(int value)](#TiffSRational-int-) | Initializes a new instance of the [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) class. |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Initializes a new instance of the `TiffSRational` class. |
## Fields

| Field | Description |
| --- | --- |
| [EPSILON](#EPSILON) | The epsilon for fraction calculation |
## Methods

| Method | Description |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approximates the provided value to a fraction. |
| [approximateFraction(double value)](#approximateFraction-double-) | Approximates the provided value to a fraction. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approximates the provided value to a fraction. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approximates the provided value to a fraction. |
| [getDenominator()](#getDenominator--) | Gets the denominator. |
| [getNominator()](#getNominator--) | Gets the nominator. |
| [getValue()](#getValue--) | Gets the float value. |
| [getValueD()](#getValueD--) | Gets the double value. |
| [toString()](#toString--) | Returns a `System.String` that represents this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `Object` is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Initializes a new instance of the `TiffSRational` class.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Initializes a new instance of the [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The nominator value. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Initializes a new instance of the `TiffSRational` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nominator | int | The nominator. |
| denominator | int | The denominator. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


The epsilon for fraction calculation

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value. |
| epsilon | double | The error allowed. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The value. |
| epsilon | double | The error allowed. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The value. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Gets the denominator.

Value: The denominator.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Gets the nominator.

Value: The nominator.

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


Gets the float value.

Value: The float value.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Gets the double value.

Value: The double value.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Returns a `System.String` that represents this instance.

**Returns:**
java.lang.String - A `System.String` that represents this instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified `Object` is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `Object` is equal to this instance; otherwise, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
