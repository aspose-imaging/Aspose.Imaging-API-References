---
title: "TiffSRational"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff rasyonel tipi."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

tiff rasyonel tipi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Yeni bir `TiffSRational` sınıfı örneği başlatır. |
| [TiffSRational(int value)](#TiffSRational-int-) | Yeni bir [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) sınıfı örneği başlatır. |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Yeni bir `TiffSRational` sınıfı örneği başlatır. |
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
| [toString()](#toString--) | Bu örneği temsil eden bir `System.String` döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `Object`'in bu örnekle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Yeni bir `TiffSRational` sınıfı örneği başlatır.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Yeni bir [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Pay değeri. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Yeni bir `TiffSRational` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pay | int | Pay. |
| payda | int | Payda. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Kesir hesaplaması için epsilon

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Değer. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Verilen değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Değer. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Paydayı alır.

Değer: payda.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Payı alır.

Değer: pay.

**Returns:**
int
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


Bu örneği temsil eden bir `System.String` döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir `System.String`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen `Object`'in bu örnekle eşit olup olmadığını belirler.

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
