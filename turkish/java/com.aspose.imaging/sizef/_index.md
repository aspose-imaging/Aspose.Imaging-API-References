---
title: "SizeF"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Genellikle bir dikdörtgenin genişliği ve yüksekliği olan, sıralı bir kayan nokta sayı çifti depolar."
type: docs
weight: 105
url: /tr/java/com.aspose.imaging/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

Bir dikdörtgenin genellikle genişlik ve yüksekliği olan, kayan noktalı sayıların sıralı bir çiftini depolar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.imaging.SizeF-) | Belirtilen `Aspose.Imaging.SizeF` yapısından yeni bir `Aspose.Imaging.SizeF` örneği başlatır. |
| [SizeF(PointF point)](#SizeF-com.aspose.imaging.PointF-) | Belirtilen `Aspose.Imaging.PointF` yapısından yeni bir `Aspose.Imaging.SizeF` örneği başlatır. |
| [SizeF(float width, float height)](#SizeF-float-float-) | Belirtilen boyutlardan yeni bir `Aspose.Imaging.SizeF` örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmpty()](#getEmpty--) | `Aspose.Imaging.SizeF.Width` ve `Aspose.Imaging.SizeF.Height` değerleri sıfıra ayarlanmış yeni bir `Aspose.Imaging.SizeF` örneği alır. |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğine ekler. |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğinden çıkarır. |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | İki `Aspose.Imaging.SizeF` yapısının eşit olup olmadığını test eder. |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | İki `Aspose.Imaging.SizeF` yapısının farklı olup olmadığını test eder. |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.imaging.SizeF-) | Belirtilen `Aspose.Imaging.SizeF` değerini bir `Aspose.Imaging.PointF` değerine dönüştürür. |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğine ekler. |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğinden çıkarır. |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) |  |
| [isEmpty()](#isEmpty--) | Bu `Aspose.Imaging.SizeF` nesnesinin sıfır genişlik ve yüksekliğe sahip olup olmadığını gösteren bir değer alır. |
| [getWidth()](#getWidth--) | Bu `Aspose.Imaging.SizeF` nesnesinin yatay bileşenini alır veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Bu `Aspose.Imaging.SizeF` nesnesinin yatay bileşenini alır veya ayarlar. |
| [getHeight()](#getHeight--) | Bu `Aspose.Imaging.SizeF` nesnesinin dikey bileşenini alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Bu `Aspose.Imaging.SizeF` nesnesinin dikey bileşenini alır veya ayarlar. |
| [toPointF()](#toPointF--) | Bir `Aspose.Imaging.SizeF` değerini bir `Aspose.Imaging.PointF` değerine dönüştürür. |
| [toSize()](#toSize--) | Bir `Aspose.Imaging.SizeF` değerini kesirli kısmı atılmış boyut değerlerine sahip bir `Aspose.Imaging.Size` yapısına dönüştürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin bu `Aspose.Imaging.SizeF` ile aynı boyutlara sahip bir `Aspose.Imaging.SizeF` olup olmadığını test eder. |
| [hashCode()](#hashCode--) | Bu `Aspose.Imaging.Size` yapısı için bir karma kodu döndürür. |
| [toString()](#toString--) | Bu `Aspose.Imaging.SizeF` nesnesini temsil eden insan tarafından okunabilir bir dize oluşturur. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.imaging.SizeF-) |  |
| [Clone()](#Clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.imaging.SizeF-}
```
public SizeF(SizeF size)
```


Belirtilen `Aspose.Imaging.SizeF` yapısından yeni bir `Aspose.Imaging.SizeF` örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Yeni `Aspose.Imaging.SizeF` oluşturulacak `Aspose.Imaging.SizeF`. |

### SizeF(PointF point) {#SizeF-com.aspose.imaging.PointF-}
```
public SizeF(PointF point)
```


Belirtilen `Aspose.Imaging.PointF` yapısından yeni bir `Aspose.Imaging.SizeF` örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Bu `Aspose.Imaging.SizeF` başlatılacak `Aspose.Imaging.PointF`. |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Belirtilen boyutlardan yeni bir `Aspose.Imaging.SizeF` örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | float | Yeni `Aspose.Imaging.SizeF` nesnesinin genişlik bileşeni. |
| yükseklik | float | Yeni `Aspose.Imaging.SizeF` nesnesinin yükseklik bileşeni. |

### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


`Aspose.Imaging.SizeF.Width` ve `Aspose.Imaging.SizeF.Height` değerleri sıfıra ayarlanmış yeni bir `Aspose.Imaging.SizeF` örneği alır.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Eklenecek ilk `Aspose.Imaging.SizeF`. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Eklemek için ikinci `Aspose.Imaging.SizeF`. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Çıkarma operatörünün sol tarafındaki `Aspose.Imaging.SizeF`. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Çıkarma operatörünün sağ tarafındaki `Aspose.Imaging.SizeF`. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` that is the result of the subtraction operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


İki `Aspose.Imaging.SizeF` yapısının eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Eşitlik operatörünün sol tarafındaki `Aspose.Imaging.SizeF` yapısı. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Eşitlik operatörünün sağ tarafındaki `Aspose.Imaging.SizeF` yapısı. |

**Returns:**
boolean - Bu operatör, `size1` ve `size2` aynı genişlik ve yüksekliğe sahipse true döndürür; aksi takdirde false.
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


İki `Aspose.Imaging.SizeF` yapısının farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Eşitsizlik operatörünün sol tarafındaki `Aspose.Imaging.SizeF` yapısı. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Eşitsizlik operatörünün sağ tarafındaki `Aspose.Imaging.SizeF` yapısı. |

**Returns:**
boolean - Bu operatör, `size1` ve `size2` genişlik ya da yükseklikte farklıysa true döndürür; `size1` ve `size2` eşitse false.
### to_PointF(SizeF size) {#to-PointF-com.aspose.imaging.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


Belirtilen `Aspose.Imaging.SizeF` değerini bir `Aspose.Imaging.PointF` değerine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Dönüştürülecek `Aspose.Imaging.SizeF` yapısı |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `Aspose.Imaging.PointF` structure to which this operator converts.
### add(SizeF size1, SizeF size2) {#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Eklenecek ilk `Aspose.Imaging.SizeF`. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Eklemek için ikinci `Aspose.Imaging.SizeF`. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


Bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.SizeF` yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Çıkarma operatörünün sol tarafındaki `Aspose.Imaging.SizeF` yapısı. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Çıkarma operatörünün sağ tarafındaki `Aspose.Imaging.SizeF` yapısı. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` that is a result of the subtraction operation.
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.imaging/sizef) |  |
| obj2 | [SizeF](../../com.aspose.imaging/sizef) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu `Aspose.Imaging.SizeF` nesnesinin sıfır genişlik ve yüksekliğe sahip olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu özellik, bu `Aspose.Imaging.SizeF` genişlik ve yüksekliği sıfır olduğunda true döndürür; aksi takdirde false.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Bu `Aspose.Imaging.SizeF` nesnesinin yatay bileşenini alır veya ayarlar.

**Returns:**
float - Bu `Aspose.Imaging.SizeF`'in yatay bileşeni, genellikle piksel cinsinden ölçülür.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Bu `Aspose.Imaging.SizeF` nesnesinin yatay bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Bu `Aspose.Imaging.SizeF` nesnesinin dikey bileşenini alır veya ayarlar.

**Returns:**
float - Bu `Aspose.Imaging.SizeF`'in dikey bileşeni, genellikle piksel cinsinden ölçülür.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Bu `Aspose.Imaging.SizeF` nesnesinin dikey bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### toPointF() {#toPointF--}
```
public PointF toPointF()
```


Bir `Aspose.Imaging.SizeF` değerini bir `Aspose.Imaging.PointF` değerine dönüştürür.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns a `Aspose.Imaging.PointF` structure.
### toSize() {#toSize--}
```
public Size toSize()
```


Bir `Aspose.Imaging.SizeF` değerini kesirli kısmı atılmış boyut değerlerine sahip bir `Aspose.Imaging.Size` yapısına dönüştürür.

**Returns:**
[Size](../../com.aspose.imaging/size) - Returns a `Aspose.Imaging.Size` structure.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin bu `Aspose.Imaging.SizeF` ile aynı boyutlara sahip bir `Aspose.Imaging.SizeF` olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek `System.Object`. |

**Returns:**
boolean - Bu metod, `obj` bir `Aspose.Imaging.SizeF` ise ve bu `Aspose.Imaging.SizeF` ile aynı genişlik ve yüksekliğe sahipse true döndürür; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu `Aspose.Imaging.Size` yapısı için bir karma kodu döndürür.

**Returns:**
int - Bu `Aspose.Imaging.Size` yapısı için bir karma değeri belirten tam sayı değeri.
### toString() {#toString--}
```
public String toString()
```


Bu `Aspose.Imaging.SizeF` nesnesini temsil eden insan tarafından okunabilir bir dize oluşturur.

**Returns:**
java.lang.String - Bu `Aspose.Imaging.SizeF`'i temsil eden bir dize.
### CloneTo(SizeF that) {#CloneTo-com.aspose.imaging.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.imaging/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
