---
title: "Complejo"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La estructura de número complejo."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

La estructura de número complejo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Inicializa una nueva instancia de la estructura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Inicializa una nueva instancia de la estructura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
## Campos

| Campo | Descripción |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | El tamaño de `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | El tamaño del complejo. |
| [ZERO](#ZERO) | Complejo cero. |
| [ONE](#ONE) | Un complejo con `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) y `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) iguales a 1. |
| [I](#I) | Un complejo con `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) igual a 1. |
## Métodos

| Método | Descripción |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | Realiza una conversión explícita de `double` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [to_Complex(float value)](#to-Complex-float-) | Realiza una conversión explícita de `float` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa el operador +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa el operador -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa el operador \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa el operador /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa el operador /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Suma `a` y `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Suma `a` y `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Suma `a` y `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Suma `a` y `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Resta `b` de `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Resta `s` de `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Resta `s` de `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Resta `b` de `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Resta `s` de `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Resta `a` de `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Multiplica `a` por `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Multiplica `a` por `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplica `a` por `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplica `a` por `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divide `a` entre `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Divide `a` entre `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divide `a` entre `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divide `a` entre `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divide `a` entre `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divide `s` entre `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | Niega `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Comprueba la igualdad aproximada. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Comprueba la igualdad aproximada. |
| [parse(String s)](#parse-java.lang.String-) | Analiza el `s` especificado en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Intenta analizar el `s` especificado en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtiene la raíz cuadrada de `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtiene el logaritmo de `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | Eleva e a `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtiene el seno de `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtiene el coseno de `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtiene la tangente de `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | Multiplica por `s`. |
| [getRe()](#getRe--) | Obtiene la parte real. |
| [setRe(double value)](#setRe-double-) | Establece la parte real. |
| [getIm()](#getIm--) | Obtiene la parte imaginaria. |
| [setIm(double value)](#setIm-double-) | Establece la parte imaginaria. |
| [set(double re, double im)](#set-double-double-) | Establece los valores y devuelve a sí mismo. |
| [getMagnitude()](#getMagnitude--) | Obtiene la magnitud. |
| [getPhase()](#getPhase--) | Obtiene la fase. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Obtiene la magnitud al cuadrado. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `Object` especificado es igual a esta instancia. |
| [toString()](#toString--) | Devuelve una cadena que representa esta instancia. |
| [deepClone()](#deepClone--) | Clona esta instancia. |
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


Inicializa una nueva instancia de la estructura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| real | double | La parte real. |
| imaginaria | double | La parte imaginaria. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Inicializa una nueva instancia de la estructura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El número complejo. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


El tamaño de `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


El tamaño del complejo.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Complejo cero.

### ONE {#ONE}
```
public static final Complex ONE
```


Un complejo con `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) y `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) iguales a 1.

### I {#I}
```
public static final Complex I
```


Un complejo con `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) igual a 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


Realiza una conversión explícita de `double` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | El valor. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


Realiza una conversión explícita de `float` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


Implementa el operador ==.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
boolean - El resultado del operador.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


Implementa el operador !=.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
boolean - El resultado del operador.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


Implementa el operador -.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


Implementa el operador +.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


Implementa el operador +.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


Implementa el operador +.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


Implementa el operador -.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


Implementa el operador -.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


Implementa el operador -.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


Implementa el operador \*.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


Implementa el operador \*.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


Implementa el operador \*.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


Implementa el operador /.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


Implementa el operador /.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


Implementa el operador /.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


Suma `a` y `b`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


Suma `a` y `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


Suma `a` y `b`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


Suma `a` y `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


Resta `b` de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


Resta `s` de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


Resta `s` de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


Resta `b` de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


Resta `s` de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


Resta `a` de `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


Multiplica `a` por `b`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


Multiplica `a` por `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


Multiplica `a` por `b`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


Multiplica `a` por `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


Divide `a` entre `b`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


Divide `a` entre `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


Divide `a` entre `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


Divide `a` entre `b`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


Divide `a` entre `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| s | double | El valor s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


Divide `s` entre `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


Niega `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Comprueba la igualdad aproximada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |

**Returns:**
boolean - El resultado de igualdad aproximada.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Comprueba la igualdad aproximada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo b. |
| tolerancia | double | La tolerancia. |

**Returns:**
boolean - El resultado de igualdad aproximada.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Analiza el `s` especificado en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Intenta analizar el `s` especificado en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | java.lang.String | El valor s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El resultado. |

**Returns:**
boolean - True, si el número complejo se analiza.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


Obtiene la raíz cuadrada de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


Obtiene el logaritmo de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


Eleva e a `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


Obtiene el seno de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


Obtiene el coseno de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


Obtiene la tangente de `a`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | El complejo "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


Multiplica por `s`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | double | El valor s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Obtiene la parte real.

**Returns:**
double - la parte real.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Establece la parte real.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | la parte real. |

### getIm() {#getIm--}
```
public final double getIm()
```


Obtiene la parte imaginaria.

**Returns:**
double - la parte imaginaria.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Establece la parte imaginaria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | la parte imaginaria. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Establece los valores y devuelve a sí mismo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| re | double | El valor Re. |
| im | double | El valor Im. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Obtiene la magnitud.

Valor: La magnitud.

**Returns:**
double - la magnitud.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Obtiene la fase.

Valor: La fase.

**Returns:**
double - la fase.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Obtiene la magnitud al cuadrado.

Valor: La magnitud al cuadrado.

**Returns:**
double - la magnitud al cuadrado.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `Object` especificado es igual a esta instancia; de lo contrario, `false`.
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa esta instancia.

**Returns:**
java.lang.String - Una cadena que representa esta instancia.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Clona esta instancia.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
