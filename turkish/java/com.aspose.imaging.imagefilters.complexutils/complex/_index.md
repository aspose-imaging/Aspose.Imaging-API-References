---
title: "Karmaşık"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu karmaşık sayı yapısı."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

Bu karmaşık sayı yapısı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Yeni bir örnek başlatır [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) yapısını. |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Yeni bir örnek başlatır [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) yapısını. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | `double`'ın boyutu. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | karmaşık'ın boyutu. |
| [ZERO](#ZERO) | Sıfır karmaşık. |
| [ONE](#ONE) | `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) ve `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 1'e eşit olan bir karmaşık. |
| [I](#I) | `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 1'e eşit olan bir i karmaşık. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | `double`'dan [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)'a açık dönüşüm gerçekleştirir. |
| [to_Complex(float value)](#to-Complex-float-) | `float`'dan [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)'a açık dönüşüm gerçekleştirir. |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | == operatörünü uygular. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | != operatörünü uygular. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | - operatörünü uygular. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | + operatörünü uygular. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | + operatörünü uygular. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | + operatörünü uygular. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | - operatörünü uygular. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | - operatörünü uygular. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | - operatörünü uygular. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | \* operatörünü uygular. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | \* operatörünü uygular. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | \* operatörünü uygular. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | / operatörünü uygular. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | / operatörünü uygular. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | / operatörünü uygular. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a` ve `b`'yi toplar. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | `a` ve `s`'yi toplar. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a` ve `b`'yi toplar. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a` ve `s`'yi toplar. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'dan `b`'yi çıkarır. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | `a`'dan `s`'yi çıkarır. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'dan `s`'yi çıkarır. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a`'dan `b`'yi çıkarır. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a`'dan `s`'yi çıkarır. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | `s`'dan `a`'yi çıkarır. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'yı `b` ile çarpar. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | `a`'yı `s` ile çarpar. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a`'yı `b` ile çarpar. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a`'yı `s` ile çarpar. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'yı `b`'ye böler. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | `a`'yı `s`'ye böler. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'yı `s`'ye böler. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a`'yı `b`'ye böler. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | `a`'yı `s`'ye böler. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | `s`'yi `a`'ya böler. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'yı negatif yapar. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Yaklaşık eşitliği kontrol eder. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Yaklaşık eşitliği kontrol eder. |
| [parse(String s)](#parse-java.lang.String-) | Belirtilen `s` değerini bir [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) nesnesine ayrıştırır. |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Belirtilen `s` değerini bir [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) nesnesine ayrıştırmayı dener. |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'nın karekökünü alır. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'nın logaritmasını alır. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | e'yi `a` kadar yükseltir. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'nın sinüsünü alır. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'nın kosinüsünü alır. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | `a`'nın tanjantını alır. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | `s` ile çarpar. |
| [getRe()](#getRe--) | Gerçek kısmı alır. |
| [setRe(double value)](#setRe-double-) | Gerçek kısmı ayarlar. |
| [getIm()](#getIm--) | Sanal kısmı alır. |
| [setIm(double value)](#setIm-double-) | Sanal kısmı ayarlar. |
| [set(double re, double im)](#set-double-double-) | Değerleri ayarlar ve kendisini döndürür. |
| [getMagnitude()](#getMagnitude--) | Büyüklüğü alır. |
| [getPhase()](#getPhase--) | Fazı alır. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Karesi alınmış büyüklüğü alır. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `Object`'in bu örnek ile eşit olup olmadığını belirler. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [deepClone()](#deepClone--) | Bu örneği kopyalar. |
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


Yeni bir örnek başlatır [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) yapısını.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gerçek | double | Gerçek kısım. |
| sanal | double | Sanal kısım. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Yeni bir örnek başlatır [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) yapısını.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Karmaşık sayı. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


`double`'ın boyutu.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


karmaşık'ın boyutu.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Sıfır karmaşık.

### ONE {#ONE}
```
public static final Complex ONE
```


`Re`(\#getRe.getRe/\#setRe(double).setRe(double)) ve `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 1'e eşit olan bir karmaşık.

### I {#I}
```
public static final Complex I
```


`Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 1'e eşit olan bir i karmaşık.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


`double`'dan [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)'a açık dönüşüm gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Değer. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


`float`'dan [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)'a açık dönüşüm gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Değer. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


== operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
boolean - Operatörün sonucu.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


!= operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
boolean - Operatörün sonucu.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


- operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


+ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


+ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


+ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


- operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


- operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


- operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


\* operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


\* operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


\* operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


/ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


/ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


/ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


`a` ve `b`'yi toplar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


`a` ve `s`'yi toplar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


`a` ve `b`'yi toplar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


`a` ve `s`'yi toplar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


`a`'dan `b`'yi çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


`a`'dan `s`'yi çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


`a`'dan `s`'yi çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


`a`'dan `b`'yi çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


`a`'dan `s`'yi çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


`s`'dan `a`'yi çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


`a`'yı `b` ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


`a`'yı `s` ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


`a`'yı `b` ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


`a`'yı `s` ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


`a`'yı `b`'ye böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


`a`'yı `s`'ye böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


`a`'yı `s`'ye böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


`a`'yı `b`'ye böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


`a`'yı `s`'ye böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| s | double | s değeri. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


`s`'yi `a`'ya böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


`a`'yı negatif yapar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Yaklaşık eşitliği kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |

**Returns:**
boolean - Yaklaşık eşitlik sonucu.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Yaklaşık eşitliği kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | b karmaşık. |
| tolerans | double | Tolerans. |

**Returns:**
boolean - Yaklaşık eşitlik sonucu.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Belirtilen `s` değerini bir [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) nesnesine ayrıştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Belirtilen `s` değerini bir [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) nesnesine ayrıştırmayı dener.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | s değeri. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Sonuç. |

**Returns:**
boolean - True, eğer karmaşık sayı ayrıştırıldıysa.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


`a`'nın karekökünü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


`a`'nın logaritmasını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


e'yi `a` kadar yükseltir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


`a`'nın sinüsünü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


`a`'nın kosinüsünü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


`a`'nın tanjantını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | "a" karmaşık. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


`s` ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | s değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Gerçek kısmı alır.

**Returns:**
double - gerçek kısmı.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Gerçek kısmı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | gerçek kısmı. |

### getIm() {#getIm--}
```
public final double getIm()
```


Sanal kısmı alır.

**Returns:**
double - imajiner kısım.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Sanal kısmı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | imajiner kısmı. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Değerleri ayarlar ve kendisini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| re | double | Re değeri. |
| im | double | Im değeri. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Büyüklüğü alır.

Değer: Büyüklük.

**Returns:**
double - büyüklük.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Fazı alır.

Değer: Faz.

**Returns:**
double - faz.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Karesi alınmış büyüklüğü alır.

Değer: Karesel büyüklük.

**Returns:**
double - karesel büyüklük.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen `Object`'in bu örnek ile eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu `Object` bu örnek ile karşılaştırmak için. |

**Returns:**
boolean - `true` eğer belirtilen `Object` bu örnek ile eşitse; aksi takdirde `false`.
### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir String.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Bu örneği kopyalar.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
