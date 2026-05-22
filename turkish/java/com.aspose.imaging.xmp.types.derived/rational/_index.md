---
title: "Rational"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP Rational'ı temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.xmp.types.derived/rational/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public class Rational extends XmpTypeBase
```

XMP Rational'ı temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Rational(int numerator, int denominator)](#Rational-int-int-) | Yeni bir `Rational` sınıfı örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNumerator()](#getNumerator--) | Payı alır. |
| [getDenominator()](#getDenominator--) | Payda alır veya ayarlar. |
| [setDenominator(int value)](#setDenominator-int-) | Payda alır veya ayarlar. |
| [getFloatValue()](#getFloatValue--) | float değerini alır. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatındaki string içerik değerini alır. |
### Rational(int numerator, int denominator) {#Rational-int-int-}
```
public Rational(int numerator, int denominator)
```


Yeni bir `Rational` sınıfı örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pay | int | Pay. |
| payda | int | Payda. |

### getNumerator() {#getNumerator--}
```
public int getNumerator()
```


Payı alır.

Değer: Pay.

**Returns:**
int
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Payda alır veya ayarlar.

**Returns:**
int - Payda.
### setDenominator(int value) {#setDenominator-int-}
```
public void setDenominator(int value)
```


Payda alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Payda. |

### getFloatValue() {#getFloatValue--}
```
public float getFloatValue()
```


float değerini alır.

**Returns:**
float - Float değeri.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatındaki string içerik değerini alır.

**Returns:**
java.lang.String - XMP biçiminde içerilen dize değerini döndürür.
