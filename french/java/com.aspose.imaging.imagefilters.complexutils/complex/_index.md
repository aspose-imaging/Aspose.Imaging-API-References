---
title: "Complex"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La structure du nombre complexe."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

La structure du nombre complexe.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Initialise une nouvelle instance de la structure [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct. |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Initialise une nouvelle instance de la structure [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct. |
## Champs

| Champ | Description |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | La taille de `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | La taille du complexe. |
| [ZERO](#ZERO) | Complexe zéro. |
| [ONE](#ONE) | Un complexe ayant `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) et `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) égaux à 1. |
| [I](#I) | Un complexe ayant `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) égal à 1. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | Effectue une conversion explicite de `double` vers [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [to_Complex(float value)](#to-Complex-float-) | Effectue une conversion explicite de `float` vers [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implémente l'opérateur +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implémente l'opérateur -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implémente l'opérateur \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implémente l'opérateur /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implémente l'opérateur /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Ajoute `a` et `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Ajoute `a` et `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Ajoute `a` et `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Ajoute `a` et `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Soustrait `b` de `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Soustrait `s` de `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Soustrait `s` de `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Soustrait `b` de `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Soustrait `s` de `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Soustrait `a` de `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Multiplie `a` par `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Multiplie `a` par `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplie `a` par `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Multiplie `a` par `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divise `a` par `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Divise `a` par `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divise `a` par `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divise `a` par `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divise `a` par `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divise `s` par `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | Négatif `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Vérifie l'égalité approximative. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Vérifie l'égalité approximative. |
| [parse(String s)](#parse-java.lang.String-) | Analyse la `s` spécifiée en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Essaie d'analyser la `s` spécifiée en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtient la racine carrée de `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtient le logarithme de `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | Élève e à la puissance `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtient le sinus de `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtient le cosinus de `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | Obtient la tangente de `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | Multiplie par `s`. |
| [getRe()](#getRe--) | Obtient la partie réelle. |
| [setRe(double value)](#setRe-double-) | Définit la partie réelle. |
| [getIm()](#getIm--) | Obtient la partie imaginaire. |
| [setIm(double value)](#setIm-double-) | Définit la partie imaginaire. |
| [set(double re, double im)](#set-double-double-) | Définit les valeurs et renvoie lui-même. |
| [getMagnitude()](#getMagnitude--) | Obtient le module. |
| [getPhase()](#getPhase--) | Obtient la phase. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Obtient le module au carré. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'`Object` spécifié est égal à cette instance. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [deepClone()](#deepClone--) | Clone cette instance. |
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


Initialise une nouvelle instance de la structure [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| réel | double | La partie réelle. |
| imaginaire | double | La partie imaginaire. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Initialise une nouvelle instance de la structure [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) struct.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le nombre complexe. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


La taille de `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


La taille du complexe.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Complexe zéro.

### ONE {#ONE}
```
public static final Complex ONE
```


Un complexe ayant `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) et `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) égaux à 1.

### I {#I}
```
public static final Complex I
```


Un complexe ayant `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) égal à 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


Effectue une conversion explicite de `double` vers [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La valeur. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


Effectue une conversion explicite de `float` vers [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


Implémente l'opérateur ==.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
booléen - Le résultat de l'opérateur.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


Implémente l'opérateur !=.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
booléen - Le résultat de l'opérateur.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


Implémente l'opérateur -.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


Implémente l'opérateur +.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


Implémente l'opérateur +.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


Implémente l'opérateur +.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


Implémente l'opérateur -.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


Implémente l'opérateur -.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


Implémente l'opérateur -.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


Implémente l'opérateur \*.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


Implémente l'opérateur \*.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


Implémente l'opérateur \*.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


Implémente l'opérateur /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


Implémente l'opérateur /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


Implémente l'opérateur /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


Ajoute `a` et `b`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


Ajoute `a` et `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


Ajoute `a` et `b`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


Ajoute `a` et `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


Soustrait `b` de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


Soustrait `s` de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


Soustrait `s` de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


Soustrait `b` de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


Soustrait `s` de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


Soustrait `a` de `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


Multiplie `a` par `b`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


Multiplie `a` par `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


Multiplie `a` par `b`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


Multiplie `a` par `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


Divise `a` par `b`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


Divise `a` par `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


Divise `a` par `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


Divise `a` par `b`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


Divise `a` par `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| s | double | La valeur s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


Divise `s` par `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


Négatif `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Vérifie l'égalité approximative.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |

**Returns:**
booléen - Le résultat d'égalité approximative.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Vérifie l'égalité approximative.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe b. |
| tolérance | double | La tolérance. |

**Returns:**
booléen - Le résultat d'égalité approximative.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Analyse la `s` spécifiée en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Essaie d'analyser la `s` spécifiée en un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | java.lang.String | La valeur s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le résultat. |

**Returns:**
booléen - Vrai, si le nombre complexe est analysé.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


Obtient la racine carrée de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


Obtient le logarithme de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


Élève e à la puissance `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


Obtient le sinus de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


Obtient le cosinus de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


Obtient la tangente de `a`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le complexe \"a\". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


Multiplie par `s`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| s | double | La valeur s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Obtient la partie réelle.

**Returns:**
double - la partie réelle.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Définit la partie réelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | la partie réelle. |

### getIm() {#getIm--}
```
public final double getIm()
```


Obtient la partie imaginaire.

**Returns:**
double - la partie imaginaire.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Définit la partie imaginaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | la partie imaginaire. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Définit les valeurs et renvoie lui-même.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| re | double | La valeur Re. |
| im | double | La valeur Im. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Obtient le module.

Valeur : La magnitude.

**Returns:**
double - la magnitude.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Obtient la phase.

Valeur : La phase.

**Returns:**
double - la phase.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Obtient le module au carré.

Valeur : La magnitude au carré.

**Returns:**
double - la magnitude au carré.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'`Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` à comparer avec cette instance. |

**Returns:**
booléen - `true` si l'`Object` spécifié est égal à cette instance ; sinon, `false`.
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente cette instance.

**Returns:**
java.lang.String - Une chaîne qui représente cette instance.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Clone cette instance.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
