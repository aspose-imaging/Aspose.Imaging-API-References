---
title: "Complex"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den komplexa talstrukturen."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

Den komplexa talstrukturen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Initierar en ny instans av strukturen [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct. |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Initierar en ny instans av strukturen [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | Storleken på `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | Storleken på komplex. |
| [ZERO](#ZERO) | Noll komplex. |
| [ONE](#ONE) | Ett komplex med `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) och `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) lika med 1. |
| [I](#I) | Ett komplex med `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) lika med 1. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | Utför en explicit konvertering från `double` till [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [to_Complex(float value)](#to-Complex-float-) | Utför en explicit konvertering från `float` till [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementerar operatorn +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementerar operatorn -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementerar operatorn \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementerar operatorn /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementerar operatorn /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Adderar `a` och `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Adderar `a` och `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Adderar `a` och `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Adderar `a` och `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Subtraherar `b` från `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Subtraherar `s` från `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Subtraherar `s` från `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtraherar `b` från `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtraherar `s` från `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtraherar `a` från `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Multiplicerar `a` med `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Multiplicerar `a` med `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplicerar `a` med `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplicerar `a` med `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Dividerar `a` med `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Dividerar `a` med `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Dividerar `a` med `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Dividerar `a` med `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Dividerar `a` med `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Dividerar `s` med `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | Negerar `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Kontrollerar ungefärlig likhet. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Kontrollerar ungefärlig likhet. |
| [parse(String s)](#parse-java.lang.String-) | Analyserar den angivna `s` till en [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Försöker analysera den angivna `s` till en [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | Hämtar kvadratroten av `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | Hämtar logaritmen av `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | Höjer e till `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | Hämtar Sin av `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | Hämtar Cos av `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | Hämtar Tan av `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | Multiplicerar med `s`. |
| [getRe()](#getRe--) | Hämtar den reella delen. |
| [setRe(double value)](#setRe-double-) | Sätter den reella delen. |
| [getIm()](#getIm--) | Hämtar den imaginära delen. |
| [setIm(double value)](#setIm-double-) | Sätter den imaginära delen. |
| [set(double re, double im)](#set-double-double-) | Sätter värdena och returnerar sig själv. |
| [getMagnitude()](#getMagnitude--) | Hämtar magnituden. |
| [getPhase()](#getPhase--) | Hämtar fasen. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Hämtar den kvadrerade magnituden. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det specificerade `Object` är lika med den här instansen. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [deepClone()](#deepClone--) | Klonar den här instansen. |
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


Initierar en ny instans av strukturen [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reell | double | Den reella delen. |
| imaginär | double | Den imaginära delen. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Initierar en ny instans av strukturen [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Det komplexa talet. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


Storleken på `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


Storleken på komplex.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Noll komplex.

### ONE {#ONE}
```
public static final Complex ONE
```


Ett komplex med `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) och `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) lika med 1.

### I {#I}
```
public static final Complex I
```


Ett komplex med `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) lika med 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


Utför en explicit konvertering från `double` till [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


Utför en explicit konvertering från `float` till [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


Implementerar operatorn ==.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
boolean - Resultatet av operatorn.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


Implementerar operatorn !=.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
boolean - Resultatet av operatorn.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


Implementerar operatorn -.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


Implementerar operatorn +.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


Implementerar operatorn +.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


Implementerar operatorn +.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


Implementerar operatorn -.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


Implementerar operatorn -.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


Implementerar operatorn -.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


Implementerar operatorn \*.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


Implementerar operatorn \*.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


Implementerar operatorn \*.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


Implementerar operatorn /.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


Implementerar operatorn /.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


Implementerar operatorn /.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


Adderar `a` och `b`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


Adderar `a` och `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


Adderar `a` och `b`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


Adderar `a` och `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


Subtraherar `b` från `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


Subtraherar `s` från `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


Subtraherar `s` från `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


Subtraherar `b` från `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


Subtraherar `s` från `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


Subtraherar `a` från `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


Multiplicerar `a` med `b`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


Multiplicerar `a` med `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


Multiplicerar `a` med `b`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


Multiplicerar `a` med `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


Dividerar `a` med `b`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


Dividerar `a` med `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


Dividerar `a` med `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


Dividerar `a` med `b`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


Dividerar `a` med `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| s | double | Det s-värdet. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


Dividerar `s` med `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


Negerar `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Kontrollerar ungefärlig likhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |

**Returns:**
boolean - Det approximativa likhetsresultatet.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Kontrollerar ungefärlig likhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den b komplexen. |
| tolerans | double | Toleransen. |

**Returns:**
boolean - Det approximativa likhetsresultatet.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Analyserar den angivna `s` till en [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Försöker analysera den angivna `s` till en [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Det s-värdet. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Resultatet. |

**Returns:**
boolean - Sant, om det komplexa talet har parsats.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


Hämtar kvadratroten av `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


Hämtar logaritmen av `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


Höjer e till `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


Hämtar Sin av `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


Hämtar Cos av `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


Hämtar Tan av `a`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Den "a" komplexen. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


Multiplicerar med `s`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | double | Det s-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Hämtar den reella delen.

**Returns:**
double - den reella delen.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Sätter den reella delen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | den reella delen. |

### getIm() {#getIm--}
```
public final double getIm()
```


Hämtar den imaginära delen.

**Returns:**
double - den imaginära delen.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Sätter den imaginära delen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | den imaginära delen. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Sätter värdena och returnerar sig själv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| re | double | Det Re-värdet. |
| im | double | Det Im-värdet. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Hämtar magnituden.

Värde: magnituden.

**Returns:**
double - magnituden.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Hämtar fasen.

Värde: fasen.

**Returns:**
double - fasen.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Hämtar den kvadrerade magnituden.

Värde: den kvadrerade magnituden.

**Returns:**
double - den kvadrerade magnituden.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det specificerade `Object` är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `Object` att jämföra med den här instansen. |

**Returns:**
boolean - `true` om det angivna `Object` är lika med den här instansen; annars `false`.
### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En sträng som representerar detta objekt.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Klonar den här instansen.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
