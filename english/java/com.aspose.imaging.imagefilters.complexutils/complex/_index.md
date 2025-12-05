---
title: Complex
second_title: Aspose.Imaging for Java API Reference
description: The complex number structure.
type: docs
weight: 10
url: /java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

The complex number structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Initializes a new instance of the [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct. |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Initializes a new instance of the [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct. |
## Fields

| Field | Description |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | The size of `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | The size of complex. |
| [ZERO](#ZERO) | Zero complex. |
| [ONE](#ONE) | One complex having `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) and `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) equal to 1. |
| [I](#I) | I complex having `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) equal to 1. |
## Methods

| Method | Description |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | Performs an explicit conversion from `double` to [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [to_Complex(float value)](#to-Complex-float-) | Performs an explicit conversion from `float` to [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implements the operator +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implements the operator -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implements the operator \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implements the operator /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implements the operator /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Adds `a` and `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Adds `a` and `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Adds `a` and `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Adds `a` and `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Subtracts `b` from `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Subtracts `s` from `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Subtracts `s` from `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtracts `b` from `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtracts `s` from `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtracts `a` from `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Multiplies `a` by `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Multiplies `a` by `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplies `a` by `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplies `a` by `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divides `a` by `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Divides `a` by `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divides `a` by `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divides `a` by `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divides `a` by `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divides `s` by `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | Negates `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Checks approximate equality. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Checks approximate equality. |
| [parse(String s)](#parse-java.lang.String-) | Parses the specified `s` into a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Tries to parse the specified `s` into a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | Gets square root of `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | Gets log of `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | Raises e by `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | Gets Sin of `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | Gets Cos of `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | Gets Tan of `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | Multiplies by `s`. |
| [getRe()](#getRe--) | Gets the real part. |
| [setRe(double value)](#setRe-double-) | Sets the real part. |
| [getIm()](#getIm--) | Gets the imaginary part. |
| [setIm(double value)](#setIm-double-) | Sets the imaginary part. |
| [set(double re, double im)](#set-double-double-) | Sets the values and returns itself. |
| [getMagnitude()](#getMagnitude--) | Gets the magnitude. |
| [getPhase()](#getPhase--) | Gets the phase. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Gets the squared magnitude. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `Object`, is equal to this instance. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [deepClone()](#deepClone--) | Clones this instance. |
| [CloneTo(Complex that)](#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [Clone()](#Clone--) |  |
### Complex() {#Complex--}
```
public Complex()
```


### Complex(double real, double imaginary) {#Complex-double-double-}
```
public Complex(double real, double imaginary)
```


Initializes a new instance of the [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| real | double | The real part. |
| imaginary | double | The imaginary part. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Initializes a new instance of the [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The complex number. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


The size of `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


The size of complex.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Zero complex.

### ONE {#ONE}
```
public static final Complex ONE
```


One complex having `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) and `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) equal to 1.

### I {#I}
```
public static final Complex I
```


I complex having `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) equal to 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


Performs an explicit conversion from `double` to [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


Performs an explicit conversion from `float` to [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


Implements the operator ==.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
boolean - The result of the operator.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


Implements the operator !=.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
boolean - The result of the operator.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


Implements the operator -.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


Implements the operator +.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


Implements the operator +.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


Implements the operator +.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


Implements the operator -.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


Implements the operator -.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


Implements the operator -.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


Implements the operator \*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


Implements the operator \*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


Implements the operator \*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


Implements the operator /.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


Implements the operator /.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


Implements the operator /.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


Adds `a` and `b`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


Adds `a` and `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


Adds `a` and `b`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


Adds `a` and `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


Subtracts `b` from `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


Subtracts `s` from `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


Subtracts `s` from `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


Subtracts `b` from `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


Subtracts `s` from `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


Subtracts `a` from `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


Multiplies `a` by `b`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


Multiplies `a` by `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


Multiplies `a` by `b`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


Multiplies `a` by `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


Divides `a` by `b`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


Divides `a` by `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


Divides `a` by `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


Divides `a` by `b`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


Divides `a` by `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| s | double | The s value. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


Divides `s` by `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


Negates `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Checks approximate equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |

**Returns:**
boolean - The approximate equality result.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Checks approximate equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The b complex. |
| tolerance | double | The tolerance. |

**Returns:**
boolean - The approximate equality result.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Parses the specified `s` into a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Tries to parse the specified `s` into a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | The s value. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | The result. |

**Returns:**
boolean - True, if the complex number is parsed.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


Gets square root of `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


Gets log of `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


Raises e by `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


Gets Sin of `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


Gets Cos of `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


Gets Tan of `a`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | The "a" complex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


Multiplies by `s`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | double | The s value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Gets the real part.

**Returns:**
double - the real part.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Sets the real part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the real part. |

### getIm() {#getIm--}
```
public final double getIm()
```


Gets the imaginary part.

**Returns:**
double - the imaginary part.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Sets the imaginary part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the imaginary part. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Sets the values and returns itself.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| re | double | The Re value. |
| im | double | The Im value. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Gets the magnitude.

Value: The magnitude.

**Returns:**
double - the magnitude.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Gets the phase.

Value: The phase.

**Returns:**
double - the phase.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Gets the squared magnitude.

Value: The squared magnitude.

**Returns:**
double - the squared magnitude.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified `Object`, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `Object` is equal to this instance; otherwise, `false`.
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Clones this instance.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
