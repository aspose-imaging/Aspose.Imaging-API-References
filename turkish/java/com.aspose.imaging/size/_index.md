---
title: "Size"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Boyutu temsil eder."
type: docs
weight: 104
url: /tr/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Boyutu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Belirtilen `Aspose.Imaging.Point` öğesinden yeni bir `Aspose.Imaging.Size` yapısı örneği başlatır. |
| [Size(int width, int height)](#Size-int-int-) | Belirtilen boyutlardan yeni bir `Aspose.Imaging.Size` yapısı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmpty()](#getEmpty--) | `Aspose.Imaging.Size.Width` ve `Aspose.Imaging.Size.Height` değerleri sıfıra ayarlanmış bir `Aspose.Imaging.Size` yapısı örneği alır. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Belirtilen `Aspose.Imaging.Size` öğesini bir `Aspose.Imaging.SizeF` öğesine dönüştürür. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğine ekler. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğinden çıkarır. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | İki `Aspose.Imaging.Size` yapısının eşit olup olmadığını test eder. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | İki `Aspose.Imaging.Size` yapısının farklı olup olmadığını test eder. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Belirtilen `Aspose.Imaging.Size` öğesini bir `Aspose.Imaging.Point` öğesine dönüştürür. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğine ekler. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Belirtilen `Aspose.Imaging.SizeF` yapısını, `Aspose.Imaging.Size` yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak bir `Aspose.Imaging.Size` yapısına dönüştürür. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğinden çıkarır. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Belirtilen `Aspose.Imaging.SizeF` yapısını, `Aspose.Imaging.SizeF` yapısının değerlerini bir sonraki alt tam sayıya kırparak bir `Aspose.Imaging.Size` yapısına dönüştürür. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Belirtilen `Aspose.Imaging.SizeF` yapısını, `Aspose.Imaging.SizeF` yapısının değerlerini en yakın tam sayıya yuvarlayarak bir `Aspose.Imaging.Size` yapısına dönüştürür. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | Bu `Aspose.Imaging.Size` nesnesinin genişlik ve yüksekliğinin 0 olup olmadığını gösteren bir değer alır. |
| [getWidth()](#getWidth--) | Bu `Aspose.Imaging.Size` nesnesinin yatay bileşenini alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | Bu `Aspose.Imaging.Size` nesnesinin yatay bileşenini alır veya ayarlar. |
| [getHeight()](#getHeight--) | Bu `Aspose.Imaging.Size` nesnesinin dikey bileşenini alır veya ayarlar. |
| [setHeight(int value)](#setHeight-int-) | Bu `Aspose.Imaging.Size` nesnesinin dikey bileşenini alır veya ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin bu `Aspose.Imaging.Size` ile aynı boyutlara sahip bir `Aspose.Imaging.Size` olup olmadığını test eder. |
| [hashCode()](#hashCode--) | Bu `Aspose.Imaging.Size` yapısı için bir karma kodu döndürür. |
| [toString()](#toString--) | Bu `Aspose.Imaging.Size` öğesini temsil eden insan tarafından okunabilir bir dize oluşturur. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Belirtilen `Aspose.Imaging.Point` öğesinden yeni bir `Aspose.Imaging.Size` yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Bu `Aspose.Imaging.Size` öğesini başlatmak için kullanılacak `Aspose.Imaging.Point`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Belirtilen boyutlardan yeni bir `Aspose.Imaging.Size` yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Yeni `Aspose.Imaging.Size` öğesinin genişlik bileşeni. |
| yükseklik | int | Yeni `Aspose.Imaging.Size` öğesinin yükseklik bileşeni. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


`Aspose.Imaging.Size.Width` ve `Aspose.Imaging.Size.Height` değerleri sıfıra ayarlanmış bir `Aspose.Imaging.Size` yapısı örneği alır.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Belirtilen `Aspose.Imaging.Size` öğesini bir `Aspose.Imaging.SizeF` öğesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Dönüştürülecek `Aspose.Imaging.Size`. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Eklenecek ilk `Aspose.Imaging.Size`. |
| size2 | [Size](../../com.aspose.imaging/size) | Eklenecek ikinci `Aspose.Imaging.Size`. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Çıkarma operatörünün sol tarafındaki `Aspose.Imaging.Size` yapısı. |
| size2 | [Size](../../com.aspose.imaging/size) | Çıkarma operatörünün sağ tarafındaki `Aspose.Imaging.Size` yapısı. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


İki `Aspose.Imaging.Size` yapısının eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Eşitlik operatörünün sol tarafındaki `Aspose.Imaging.Size` yapısı. |
| size2 | [Size](../../com.aspose.imaging/size) | Eşitlik operatörünün sağ tarafındaki `Aspose.Imaging.Size` yapısı. |

**Returns:**
boolean - `size1` ve `size2` eşit genişlik ve yüksekliğe sahipse true; aksi takdirde false.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


İki `Aspose.Imaging.Size` yapısının farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Eşitsizlik operatörünün sol tarafındaki `Aspose.Imaging.Size` yapısı. |
| size2 | [Size](../../com.aspose.imaging/size) | Eşitsizlik operatörünün sağ tarafındaki `Aspose.Imaging.Size` yapısı. |

**Returns:**
boolean - `size1` ve `size2` genişlik ya da yükseklikte farklıysa true; `size1` ve `size2` eşitse false.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Belirtilen `Aspose.Imaging.Size` öğesini bir `Aspose.Imaging.Point` öğesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Dönüştürülecek `Aspose.Imaging.Size`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Eklenecek ilk `Aspose.Imaging.Size`. |
| size2 | [Size](../../com.aspose.imaging/size) | Eklenecek ikinci `Aspose.Imaging.Size`. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Belirtilen `Aspose.Imaging.SizeF` yapısını, `Aspose.Imaging.Size` yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak bir `Aspose.Imaging.Size` yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Dönüştürülecek `Aspose.Imaging.SizeF` yapısı. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğini başka bir `Aspose.Imaging.Size` yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Çıkarma operatörünün sol tarafındaki `Aspose.Imaging.Size` yapısı. |
| size2 | [Size](../../com.aspose.imaging/size) | Çıkarma operatörünün sağ tarafındaki `Aspose.Imaging.Size` yapısı. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Belirtilen `Aspose.Imaging.SizeF` yapısını, `Aspose.Imaging.SizeF` yapısının değerlerini bir sonraki alt tam sayıya kırparak bir `Aspose.Imaging.Size` yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Dönüştürülecek `Aspose.Imaging.SizeF` yapısı. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Belirtilen `Aspose.Imaging.SizeF` yapısını, `Aspose.Imaging.SizeF` yapısının değerlerini en yakın tam sayıya yuvarlayarak bir `Aspose.Imaging.Size` yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Dönüştürülecek `Aspose.Imaging.SizeF` yapısı. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu `Aspose.Imaging.Size` nesnesinin genişlik ve yüksekliğinin 0 olup olmadığını gösteren bir değer alır.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu `Aspose.Imaging.Size` nesnesinin yatay bileşenini alır veya ayarlar.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Bu `Aspose.Imaging.Size` nesnesinin yatay bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu `Aspose.Imaging.Size` nesnesinin dikey bileşenini alır veya ayarlar.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Bu `Aspose.Imaging.Size` nesnesinin dikey bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin bu `Aspose.Imaging.Size` ile aynı boyutlara sahip bir `Aspose.Imaging.Size` olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek `System.Object`. |

**Returns:**
boolean - `obj` bir `Aspose.Imaging.Size` ise ve bu `Aspose.Imaging.Size` ile aynı genişlik ve yüksekliğe sahipse true; aksi takdirde false.
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


Bu `Aspose.Imaging.Size` öğesini temsil eden insan tarafından okunabilir bir dize oluşturur.

**Returns:**
java.lang.String - Bu `Aspose.Imaging.Size` öğesini temsil eden bir dize.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
