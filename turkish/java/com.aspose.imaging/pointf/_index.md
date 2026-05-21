---
title: "PointF"
second_title: "Aspose.Imaging for Java API Referansı"
description: "İki boyutlu bir düzlemde bir noktayı tanımlayan kayan noktalı x ve y koordinatlarından oluşan sıralı bir çift temsil eder."
type: docs
weight: 87
url: /tr/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

İki boyutlu bir düzlemde bir noktayı tanımlayan kayan noktalı x ve y koordinatlarından oluşan sıralı bir çift temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Belirtilen koordinatlarla `com.aspose.imaging.PointF` yapısının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmpty()](#getEmpty--) | `com.aspose.imaging.PointF.X` ve `com.aspose.imaging.PointF.Y` değerleri sıfıra ayarlanmış `com.aspose.imaging.PointF` yapısının yeni bir örneğini alır. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Bir `com.aspose.imaging.PointF` öğesini verilen bir `com.aspose.imaging.Size` ile çevirir. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Bir `com.aspose.imaging.PointF` öğesini verilen bir `com.aspose.imaging.Size`'ın negatifine göre çevirir. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | `com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.SizeF` ile çevirir. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Bir `com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.SizeF`'ın negatifine göre çevirir. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | İki `com.aspose.imaging.PointF` yapısını karşılaştırır. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Belirtilen noktaların koordinatlarının eşit olmadığını belirler. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Verilen bir `com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.Size` ile çevirir. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Bir `com.aspose.imaging.PointF` öğesini belirtilen boyutun negatifine göre çevirir. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Verilen bir `com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.SizeF` ile çevirir. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Bir `com.aspose.imaging.PointF` öğesini belirtilen boyutun negatifine göre çevirir. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | Bu `com.aspose.imaging.PointF` öğesinin boş olup olmadığını gösteren bir değeri alır. |
| [getX()](#getX--) | Bu `com.aspose.imaging.PointF` öğesinin x-koordinatını alır veya ayarlar. |
| [setX(float value)](#setX-float-) | Bu `com.aspose.imaging.PointF` öğesinin x-koordinatını alır veya ayarlar. |
| [getY()](#getY--) | Bu `com.aspose.imaging.PointF` öğesinin y-koordinatını alır veya ayarlar. |
| [setY(float value)](#setY-float-) | Bu `com.aspose.imaging.PointF` öğesinin y-koordinatını alır veya ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu `com.aspose.imaging.PointF` öğesinin belirtilen `System.Object` ile aynı koordinatları içerip içermediğini belirtir. |
| [hashCode()](#hashCode--) | Bu `com.aspose.imaging.PointF` yapısı için bir karma kod (hash code) döndürür. |
| [toString()](#toString--) | Bu `com.aspose.imaging.PointF` öğesini insan tarafından okunabilir bir dizeye dönüştürür. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Belirtilen koordinatlarla `com.aspose.imaging.PointF` yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Noktanın yatay konumu. |
| y | float | Noktanın dikey konumu. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


`com.aspose.imaging.PointF.X` ve `com.aspose.imaging.PointF.Y` değerleri sıfıra ayarlanmış `com.aspose.imaging.PointF` yapısının yeni bir örneğini alır.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Bir `com.aspose.imaging.PointF` öğesini verilen bir `com.aspose.imaging.Size` ile çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek `com.aspose.imaging.PointF`. |
| size | [Size](../../com.aspose.imaging/size) | `point` koordinatlarına eklenecek sayı çiftini belirten bir `com.aspose.imaging.Size`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Bir `com.aspose.imaging.PointF` öğesini verilen bir `com.aspose.imaging.Size`'ın negatifine göre çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek bir `com.aspose.imaging.PointF`. |
| size | [Size](../../com.aspose.imaging/size) | `point`'in x ve y koordinatlarından çıkarılacak sayıları belirten bir `com.aspose.imaging.Size`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


`com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.SizeF` ile çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek `com.aspose.imaging.PointF`. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `point`'in x ve y koordinatlarına eklenecek sayıları belirten `com.aspose.imaging.SizeF`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Bir `com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.SizeF`'ın negatifine göre çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek `com.aspose.imaging.PointF`. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `point` koordinatlarından çıkarılacak sayıları belirten `com.aspose.imaging.SizeF`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


`com.aspose.imaging.PointF` yapılarını karşılaştırır. Sonuç, iki `com.aspose.imaging.PointF` yapısının `com.aspose.imaging.PointF.X` ve `com.aspose.imaging.PointF.Y` özellik değerlerinin eşit olup olmadığını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Karşılaştırılacak ilk `com.aspose.imaging.PointF`. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Karşılaştırılacak ikinci `com.aspose.imaging.PointF`. |

**Returns:**
boolean - İlk ve ikinci `com.aspose.imaging.PointF` yapıların `com.aspose.imaging.PointF.X` ve `com.aspose.imaging.PointF.Y` değerleri eşitse true; aksi takdirde false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Belirtilen noktaların koordinatlarının eşit olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Karşılaştırılacak ilk `com.aspose.imaging.PointF`. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Karşılaştırılacak ikinci `com.aspose.imaging.PointF`. |

**Returns:**
boolean - `point1` ve `point2`'nin `com.aspose.imaging.PointF.X` ve `com.aspose.imaging.PointF.Y` değerlerinin eşit olmadığını göstermek için true; aksi takdirde false.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Verilen bir `com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.Size` ile çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek `com.aspose.imaging.PointF`. |
| size | [Size](../../com.aspose.imaging/size) | `point` koordinatlarına eklenecek sayıları belirten `com.aspose.imaging.Size`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Bir `com.aspose.imaging.PointF` öğesini belirtilen boyutun negatifine göre çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek `com.aspose.imaging.PointF`. |
| size | [Size](../../com.aspose.imaging/size) | `point` koordinatlarından çıkarılacak sayıları belirten `com.aspose.imaging.Size`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Verilen bir `com.aspose.imaging.PointF` öğesini belirtilen `com.aspose.imaging.SizeF` ile çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek `com.aspose.imaging.PointF`. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `point` koordinatlarına eklenecek sayıları belirten `com.aspose.imaging.SizeF`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Bir `com.aspose.imaging.PointF` öğesini belirtilen boyutun negatifine göre çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Çevrilecek `com.aspose.imaging.PointF`. |
| size | [SizeF](../../com.aspose.imaging/sizef) | `point` koordinatlarından çıkarılacak sayıları belirten `com.aspose.imaging.SizeF`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu `com.aspose.imaging.PointF` öğesinin boş olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - `com.aspose.imaging.PointF.X` ve `com.aspose.imaging.PointF.Y` her ikisi de 0 ise true; aksi takdirde false.
### getX() {#getX--}
```
public float getX()
```


Bu `com.aspose.imaging.PointF` öğesinin x-koordinatını alır veya ayarlar.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Bu `com.aspose.imaging.PointF` öğesinin x-koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getY() {#getY--}
```
public float getY()
```


Bu `com.aspose.imaging.PointF` öğesinin y-koordinatını alır veya ayarlar.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Bu `com.aspose.imaging.PointF` öğesinin y-koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu `com.aspose.imaging.PointF` öğesinin belirtilen `System.Object` ile aynı koordinatları içerip içermediğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek `System.Object`. |

**Returns:**
boolean - `obj` bir `com.aspose.imaging.PointF` ise ve bu `com.aspose.imaging.Point` ile aynı koordinatlara sahipse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu `com.aspose.imaging.PointF` yapısı için bir karma kod (hash code) döndürür.

**Returns:**
int - Bu `com.aspose.imaging.PointF` yapısı için bir karma (hash) değeri belirten tam sayı değeri.
### toString() {#toString--}
```
public String toString()
```


Bu `com.aspose.imaging.PointF` öğesini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu `com.aspose.imaging.PointF`'i temsil eden bir dize.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
