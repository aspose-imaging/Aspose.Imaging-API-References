---
title: "Complex"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die komplexe Zahlenstruktur."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

Die komplexe Zahlenstruktur.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Initialisiert eine neue Instanz der [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) Struktur. |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Initialisiert eine neue Instanz der [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) Struktur. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | Die Größe von `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | Die Größe von complex. |
| [ZERO](#ZERO) | Null komplex. |
| [ONE](#ONE) | Ein komplexer Wert mit `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) und `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) gleich 1. |
| [I](#I) | Ein komplexer Wert mit `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) gleich 1. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | Führt eine explizite Konvertierung von `double` zu [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) durch. |
| [to_Complex(float value)](#to-Complex-float-) | Führt eine explizite Konvertierung von `float` zu [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) durch. |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementiert den Operator +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementiert den Operator -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementiert den Operator \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementiert den Operator /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementiert den Operator /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Addiert `a` und `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Addiert `a` und `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Addiert `a` und `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Addiert `a` und `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Subtrahiert `b` von `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Subtrahiert `s` von `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Subtrahiert `s` von `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtrahiert `b` von `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtrahiert `s` von `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Subtrahiert `a` von `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Multipliziert `a` mit `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Multipliziert `a` mit `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multipliziert `a` mit `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multipliziert `a` mit `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Dividiert `a` durch `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Dividiert `a` durch `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Dividiert `a` durch `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Dividiert `a` durch `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Dividiert `a` durch `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Dividiert `s` durch `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | Negiert `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Prüft die ungefähre Gleichheit. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Prüft die ungefähre Gleichheit. |
| [parse(String s)](#parse-java.lang.String-) | Parst das angegebene `s` in ein [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Versucht, das angegebene `s` in ein [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) zu parsen. |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | Liefert die Quadratwurzel von `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | Liefert den Logarithmus von `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | Erhöht e um `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | Liefert den Sinus von `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | Liefert den Kosinus von `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | Liefert den Tangens von `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | Multipliziert mit `s`. |
| [getRe()](#getRe--) | Liefert den Realteil. |
| [setRe(double value)](#setRe-double-) | Setzt den Realteil. |
| [getIm()](#getIm--) | Liefert den Imaginärteil. |
| [setIm(double value)](#setIm-double-) | Setzt den Imaginärteil. |
| [set(double re, double im)](#set-double-double-) | Setzt die Werte und gibt sich selbst zurück. |
| [getMagnitude()](#getMagnitude--) | Liefert den Betrag. |
| [getPhase()](#getPhase--) | Liefert die Phase. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Liefert den quadrierten Betrag. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [deepClone()](#deepClone--) | Klonen Sie diese Instanz. |
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


Initialisiert eine neue Instanz der [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| real | double | Der Realteil. |
| imaginär | double | Der Imaginärteil. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Initialisiert eine neue Instanz der [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Die komplexe Zahl. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


Die Größe von `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


Die Größe von complex.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Null komplex.

### ONE {#ONE}
```
public static final Complex ONE
```


Ein komplexer Wert mit `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) und `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) gleich 1.

### I {#I}
```
public static final Complex I
```


Ein komplexer Wert mit `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) gleich 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


Führt eine explizite Konvertierung von `double` zu [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) durch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


Führt eine explizite Konvertierung von `float` zu [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) durch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


Implementiert den Operator ==.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
boolesch - Das Ergebnis des Operators.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


Implementiert den Operator !=.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
boolesch - Das Ergebnis des Operators.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


Implementiert den Operator -.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


Implementiert den Operator +.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


Implementiert den Operator +.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


Implementiert den Operator +.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


Implementiert den Operator -.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


Implementiert den Operator -.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


Implementiert den Operator -.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


Implementiert den Operator \*.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


Implementiert den Operator \*.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


Implementiert den Operator \*.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


Implementiert den Operator /.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


Implementiert den Operator /.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


Implementiert den Operator /.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


Addiert `a` und `b`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


Addiert `a` und `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


Addiert `a` und `b`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


Addiert `a` und `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


Subtrahiert `b` von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


Subtrahiert `s` von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


Subtrahiert `s` von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


Subtrahiert `b` von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


Subtrahiert `s` von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


Subtrahiert `a` von `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


Multipliziert `a` mit `b`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


Multipliziert `a` mit `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


Multipliziert `a` mit `b`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


Multipliziert `a` mit `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


Dividiert `a` durch `b`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


Dividiert `a` durch `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


Dividiert `a` durch `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


Dividiert `a` durch `b`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


Dividiert `a` durch `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| s | double | Der s-Wert. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


Dividiert `s` durch `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


Negiert `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Prüft die ungefähre Gleichheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |

**Returns:**
boolean - Das Ergebnis der ungefähren Gleichheit.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Prüft die ungefähre Gleichheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der b-Komplex. |
| Toleranz | double | Die Toleranz. |

**Returns:**
boolean - Das Ergebnis der ungefähren Gleichheit.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Parst das angegebene `s` in ein [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Versucht, das angegebene `s` in ein [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) zu parsen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Der s-Wert. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Das Ergebnis. |

**Returns:**
boolean - True, wenn die komplexe Zahl geparst wird.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


Liefert die Quadratwurzel von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


Liefert den Logarithmus von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


Erhöht e um `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


Liefert den Sinus von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


Liefert den Kosinus von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


Liefert den Tangens von `a`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der "a"-Komplex. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


Multipliziert mit `s`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | double | Der s-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Liefert den Realteil.

**Returns:**
double - der Realteil.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Setzt den Realteil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Realteil. |

### getIm() {#getIm--}
```
public final double getIm()
```


Liefert den Imaginärteil.

**Returns:**
double - der Imaginärteil.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Setzt den Imaginärteil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Imaginärteil. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Setzt die Werte und gibt sich selbst zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| re | double | Der Re-Wert. |
| im | double | Der Im-Wert. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Liefert den Betrag.

Wert: Der Betrag.

**Returns:**
double - der Betrag.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Liefert die Phase.

Wert: Die Phase.

**Returns:**
double - die Phase.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Liefert den quadrierten Betrag.

Wert: Der quadrierte Betrag.

**Returns:**
double - der quadrierte Betrag.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true` wenn das angegebene `Object` dieser Instanz gleich ist; andernfalls `false`.
### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Klonen Sie diese Instanz.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
