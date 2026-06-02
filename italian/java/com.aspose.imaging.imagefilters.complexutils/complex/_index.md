---
title: "Complesso"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La struttura del numero complesso."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

La struttura del numero complesso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Inizializza una nuova istanza della struttura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Inizializza una nuova istanza della struttura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | La dimensione di `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | La dimensione del complesso. |
| [ZERO](#ZERO) | Complesso zero. |
| [ONE](#ONE) | Un complesso con `Re`(\\#getRe.getRe/\\#setRe(double).setRe(double)) e `Im`(\\#getIm.getIm/\\#setIm(double).setIm(double)) uguali a 1. |
| [I](#I) | Un complesso con `Im`(\\#getIm.getIm/\\#setIm(double).setIm(double)) uguale a 1. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | Esegue una conversione esplicita da `double` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [to_Complex(float value)](#to-Complex-float-) | Esegue una conversione esplicita da `float` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa l'operatore +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa l'operatore -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa l'operatore \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Implementa l'operatore /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Implementa l'operatore /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Aggiunge `a` e `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Aggiunge `a` e `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Aggiunge `a` e `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Aggiunge `a` e `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Sottrae `b` da `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Sottrae `s` da `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Sottrae `s` da `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Sottrae `b` da `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Sottrae `s` da `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Sottrae `a` da `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Moltiplica `a` per `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Moltiplica `a` per `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Moltiplica `a` per `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Moltiplica `a` per `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divide `a` per `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Divide `a` per `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Divide `a` per `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divide `a` per `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divide `a` per `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Divide `s` per `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | Nega `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Verifica l'uguaglianza approssimativa. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Verifica l'uguaglianza approssimativa. |
| [parse(String s)](#parse-java.lang.String-) | Analizza la `s` specificata in un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Tenta di analizzare la `s` specificata in un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | Restituisce la radice quadrata di `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | Restituisce il logaritmo di `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | Eleva e alla potenza `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | Restituisce il seno di `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | Restituisce il coseno di `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | Restituisce la tangente di `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | Moltiplica per `s`. |
| [getRe()](#getRe--) | Restituisce la parte reale. |
| [setRe(double value)](#setRe-double-) | Imposta la parte reale. |
| [getIm()](#getIm--) | Restituisce la parte immaginaria. |
| [setIm(double value)](#setIm-double-) | Imposta la parte immaginaria. |
| [set(double re, double im)](#set-double-double-) | Imposta i valori e restituisce se stesso. |
| [getMagnitude()](#getMagnitude--) | Restituisce la magnitudine. |
| [getPhase()](#getPhase--) | Restituisce la fase. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Restituisce la magnitudine al quadrato. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'`Object` specificato è uguale a questa istanza. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
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


Inizializza una nuova istanza della struttura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reale | double | La parte reale. |
| immaginaria | double | La parte immaginaria. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Inizializza una nuova istanza della struttura [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il numero complesso. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


La dimensione di `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


La dimensione del complesso.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Complesso zero.

### ONE {#ONE}
```
public static final Complex ONE
```


Un complesso con `Re`(\\#getRe.getRe/\\#setRe(double).setRe(double)) e `Im`(\\#getIm.getIm/\\#setIm(double).setIm(double)) uguali a 1.

### I {#I}
```
public static final Complex I
```


Un complesso con `Im`(\\#getIm.getIm/\\#setIm(double).setIm(double)) uguale a 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


Esegue una conversione esplicita da `double` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


Esegue una conversione esplicita da `float` a [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


Implementa l'operatore ==.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
boolean - Il risultato dell'operatore.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


Implementa l'operatore !=.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
boolean - Il risultato dell'operatore.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


Implementa l'operatore -.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


Implementa l'operatore +.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


Implementa l'operatore +.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


Implementa l'operatore +.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


Implementa l'operatore -.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


Implementa l'operatore -.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


Implementa l'operatore -.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


Implementa l'operatore \*.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


Implementa l'operatore \*.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


Implementa l'operatore \*.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


Implementa l'operatore /.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


Implementa l'operatore /.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


Implementa l'operatore /.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


Aggiunge `a` e `b`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


Aggiunge `a` e `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


Aggiunge `a` e `b`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


Aggiunge `a` e `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


Sottrae `b` da `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


Sottrae `s` da `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


Sottrae `s` da `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


Sottrae `b` da `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


Sottrae `s` da `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


Sottrae `a` da `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


Moltiplica `a` per `b`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


Moltiplica `a` per `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


Moltiplica `a` per `b`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


Moltiplica `a` per `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


Divide `a` per `b`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


Divide `a` per `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


Divide `a` per `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


Divide `a` per `b`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


Divide `a` per `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| s | double | Il valore s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


Divide `s` per `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


Nega `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Verifica l'uguaglianza approssimativa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |

**Returns:**
boolean - Il risultato di uguaglianza approssimativa.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Verifica l'uguaglianza approssimativa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso b. |
| tolerance | double | La tolleranza. |

**Returns:**
boolean - Il risultato di uguaglianza approssimativa.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Analizza la `s` specificata in un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Tenta di analizzare la `s` specificata in un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | java.lang.String | Il valore s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il risultato. |

**Returns:**
boolean - True, se il numero complesso è analizzato.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


Restituisce la radice quadrata di `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


Restituisce il logaritmo di `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


Eleva e alla potenza `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


Restituisce il seno di `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


Restituisce il coseno di `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


Restituisce la tangente di `a`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il complesso "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


Moltiplica per `s`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | double | Il valore s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Restituisce la parte reale.

**Returns:**
double - la parte reale.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Imposta la parte reale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | la parte reale. |

### getIm() {#getIm--}
```
public final double getIm()
```


Restituisce la parte immaginaria.

**Returns:**
double - la parte immaginaria.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Imposta la parte immaginaria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | la parte immaginaria. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Imposta i valori e restituisce se stesso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| re | double | Il valore Re. |
| im | double | Il valore Im. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Restituisce la magnitudine.

Valore: La magnitudine.

**Returns:**
double - la magnitudine.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Restituisce la fase.

Valore: La fase.

**Returns:**
double - la fase.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Restituisce la magnitudine al quadrato.

Valore: La magnitudine al quadrato.

**Returns:**
double - la magnitudine al quadrato.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'`Object` specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` da confrontare con questa istanza. |

**Returns:**
boolean - `true` se l'`Object` specificato è uguale a questa istanza; altrimenti, `false`.
### toString() {#toString--}
```
public String toString()
```


Restituisce una String che rappresenta questa istanza.

**Returns:**
java.lang.String - Una stringa che rappresenta questa istanza.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Clona questa istanza.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
