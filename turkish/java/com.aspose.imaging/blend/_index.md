---
title: "Blend"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir karışım desenini tanımlar."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Blend desenini tanımlar. Bu sınıf kalıtılamaz.

Tipik blend sınıfı kullanımı, fırça için bir blend deseni tanımlamaktır. Bu nedenle blend özellikleri dikkatlice başlatılmalıdır. Null dizilerine izin verilmez. Fırça, blend faktörleri veya konum dizileri boşsa ya da uzunlukları aynı değilse uygun istisnayı fırlatacaktır. Konum dizisinde iki veya daha fazla öğe varsa, ilk öğe 0 ve son öğe 1 olmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Blend()](#Blend--) | `Blend` sınıfının yeni bir örneğini başlatır. |
| [Blend(int count)](#Blend-int-) | `Blend` sınıfının, belirtilen faktör ve konum sayısıyla yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFactors()](#getFactors--) | Gradient için blend faktörleri dizisini alır. |
| [setFactors(float[] value)](#setFactors-float---) | Gradient için blend faktörleri dizisini ayarlar. |
| [getPositions()](#getPositions--) | Gradient için blend konumları dizisini alır. |
| [setPositions(float[] value)](#setPositions-float---) | Gradient için blend konumları dizisini ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin bir `com.aspose.imaging.Blend` sınıfı olup olmadığını ve bu `com.aspose.imaging.Blend` sınıfına eşit olup olmadığını test eder. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### Blend() {#Blend--}
```
public Blend()
```


`Blend` sınıfının yeni bir örneğini başlatır. Faktor ve blend dizilerindeki öğe sayısı 1 olacaktır.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


`Blend` sınıfının, belirtilen faktör ve konum sayısıyla yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| count | int | Faktor ve konum dizilerindeki öğe sayısı. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Gradient için blend faktörleri dizisini alır.

**Returns:**
float[] - İlgili konumda kullanılacak başlangıç rengi ve bitiş rengi yüzdelerini belirten blend faktörleri dizisi.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Gradient için blend faktörleri dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | İlgili konumda kullanılacak başlangıç rengi ve bitiş rengi yüzdelerini belirten blend faktörleri dizisi. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Gradient için blend konumları dizisini alır.

**Returns:**
float[] - Gradyan çizgisi boyunca mesafenin yüzdelerini belirten blend konumları dizisi.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Gradient için blend konumları dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | Gradyan çizgisi boyunca mesafenin yüzdelerini belirten blend konumları dizisi. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin bir `com.aspose.imaging.Blend` sınıfı olup olmadığını ve bu `com.aspose.imaging.Blend` sınıfına eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek nesne. |

**Returns:**
boolean - `obj` bu `com.aspose.imaging.Blend` sınıfına eşit bir `com.aspose.imaging.Blend` sınıfı ise doğru; aksi takdirde yanlış.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
