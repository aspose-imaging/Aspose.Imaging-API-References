---
title: "TiffRational"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff rasyonel tipi."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

tiff rasyonel tipi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffRational()](#TiffRational--) | Yeni bir `TiffRational` sınıfı örneğini başlatır. |
| [TiffRational(long value)](#TiffRational-long-) | Yeni bir `TiffRational` sınıfı örneğini başlatır. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Yeni bir `TiffRational` sınıfı örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EPSILON](#EPSILON) | Kesir hesaplaması için epsilon |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Verilen değeri bir kesire yaklaştırır. |
| [approximateFraction(double value)](#approximateFraction-double-) | Verilen değeri bir kesire yaklaştırır. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Verilen değeri bir kesire yaklaştırır. |
| [approximateFraction(float value)](#approximateFraction-float-) | Verilen değeri bir kesire yaklaştırır. |
| [getDenominator()](#getDenominator--) | Paydayı alır. |
| [getNominator()](#getNominator--) | Payı alır. |
| [getValue()](#getValue--) | float değerini alır. |
| [getValueD()](#getValueD--) | double değerini alır. |
| [toString()](#toString--) | Stringe dönüştürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `Object`'in bu örnek ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Yeni bir `TiffRational` sınıfı örneğini başlatır.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Yeni bir `TiffRational` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | long | Pay değeri. |

Pay, belirtilen değer olarak kullanılacak ve payda 1'e eşit olacaktır. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Yeni bir `TiffRational` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pay | long | Pay. |
| payda | long | Payda. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Kesir hesaplaması için epsilon

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Değer. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Değer. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Paydayı alır.

Değer: payda.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Payı alır.

Değer: pay.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


float değerini alır.

Değer: float değeri.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


double değerini alır.

Değer: Çift değer.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Stringe dönüştürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir String.
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
