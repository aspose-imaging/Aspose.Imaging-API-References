---
title: "Point"
second_title: "Aspose.Imaging for Java API Referansı"
description: "İki boyutlu bir düzlemde bir noktayı tanımlayan tamsayı x ve y koordinatlarından oluşan sıralı bir çift temsil eder."
type: docs
weight: 86
url: /tr/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

İki boyutlu bir düzlemde bir noktayı tanımlayan tamsayı x ve y koordinatlarından oluşan sıralı bir çift temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Belirtilen koordinatlarla yeni bir `Aspose.Imaging.Point` yapısı örneği başlatır. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | `Aspose.Imaging.Size` yapısından yeni bir `Aspose.Imaging.Point` yapısı örneği başlatır. |
| [Point(int dw)](#Point-int-) | Tam sayı değeriyle belirtilen koordinatları kullanarak yeni bir `Aspose.Imaging.Point` yapısı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmpty()](#getEmpty--) | `Aspose.Imaging.Point.X` ve `Aspose.Imaging.Point.Y` değerleri sıfıra ayarlanmış yeni bir `Aspose.Imaging.Point` yapısı örneği alır. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Belirtilen `Aspose.Imaging.Size` öğesini belirtilen `Aspose.Imaging.Point` öğesine ekler. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Belirtilen `Aspose.Imaging.Size` öğesini belirtilen `Aspose.Imaging.Point` öğesinden çıkararak elde edilen sonucu döndürür. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Belirtilen `Aspose.Imaging.PointF` değerini, `Aspose.Imaging.PointF` değerlerini bir üst tam sayıya yuvarlayarak bir `Aspose.Imaging.Point` değerine dönüştürür. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Belirtilen `Aspose.Imaging.PointF` değerini, `Aspose.Imaging.Point` değerlerini en yakın tam sayıya yuvarlayarak bir `Aspose.Imaging.Point` nesnesine dönüştürür. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Belirtilen `Aspose.Imaging.PointF` değerini, `Aspose.Imaging.Point` değerlerini kırparak bir `Aspose.Imaging.Point` değerine dönüştürür. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Bir `Aspose.Imaging.Point` değerini verilen bir `Aspose.Imaging.Size` ile kaydırır. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Bir `Aspose.Imaging.Point` değerini verilen bir `Aspose.Imaging.Size` değerinin negatifine göre kaydırır. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | İki `Aspose.Imaging.Point` nesnesini karşılaştırır. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | İki `Aspose.Imaging.Point` nesnesini karşılaştırır. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Belirtilen `Aspose.Imaging.Point` yapısını bir `Aspose.Imaging.Size` yapısına dönüştürür. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Belirtilen `Point` yapısını `PointF` yapısına dönüştürür. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Bir uzun (long) nesne içinde paketlenmiş bir Point nesnesini, X ve Y tamsayı değerlerine ayırır. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | Bu `Aspose.Imaging.Point` nesnesinin boş olup olmadığını gösteren bir değeri alır. |
| [getX()](#getX--) | Bu `Aspose.Imaging.Point` nesnesinin x-koordinatını alır veya ayarlar. |
| [setX(int value)](#setX-int-) | Bu `Aspose.Imaging.Point` nesnesinin x-koordinatını alır veya ayarlar. |
| [getY()](#getY--) | Bu `Aspose.Imaging.Point` nesnesinin y-koordinatını alır veya ayarlar. |
| [setY(int value)](#setY-int-) | Bu `Aspose.Imaging.Point` nesnesinin y-koordinatını alır veya ayarlar. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Bu `Aspose.Imaging.Point` nesnesini belirtilen `Aspose.Imaging.Point` ile kaydırır. |
| [offset(int dx, int dy)](#offset-int-int-) | Bu `Aspose.Imaging.Point` nesnesini belirtilen miktarda kaydırır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu `Aspose.Imaging.Point` nesnesinin belirtilen `System.Object` ile aynı koordinatları içerip içermediğini belirtir. |
| [hashCode()](#hashCode--) | Bu `Aspose.Imaging.Point` nesnesi için bir karma (hash) kodu döndürür. |
| [toLong()](#toLong--) | Bu Point nesnesini, X ve Y koordinatlarını yüksek ve düşük bitlerde içeren tek bir uzun (long) değere dönüştürür. |
| [toString()](#toString--) | Bu `Aspose.Imaging.Point` nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Belirtilen koordinatlarla yeni bir `Aspose.Imaging.Point` yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Noktanın yatay konumu. |
| y | int | Noktanın dikey konumu. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


`Aspose.Imaging.Size` yapısından yeni bir `Aspose.Imaging.Point` yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Yeni nokta koordinatlarını içerir. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Tam sayı değeriyle belirtilen koordinatları kullanarak yeni bir `Aspose.Imaging.Point` yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dw | int | Yeni nokta için koordinatları belirten 32 bitlik bir tam sayı. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


`Aspose.Imaging.Point.X` ve `Aspose.Imaging.Point.Y` değerleri sıfıra ayarlanmış yeni bir `Aspose.Imaging.Point` yapısı örneği alır.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Belirtilen `Aspose.Imaging.Size` öğesini belirtilen `Aspose.Imaging.Point` öğesine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Eklenecek `Aspose.Imaging.Point`. |
| size | [Size](../../com.aspose.imaging/size) | `point` öğesine eklenecek `Aspose.Imaging.Size`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Belirtilen `Aspose.Imaging.Size` öğesini belirtilen `Aspose.Imaging.Point` öğesinden çıkararak elde edilen sonucu döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Çıkarma yapılacak `Aspose.Imaging.Point`. |
| size | [Size](../../com.aspose.imaging/size) | `point`'den çıkarılacak `Aspose.Imaging.Size`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Belirtilen `Aspose.Imaging.PointF` değerini, `Aspose.Imaging.PointF` değerlerini bir üst tam sayıya yuvarlayarak bir `Aspose.Imaging.Point` değerine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Dönüştürülecek `Aspose.Imaging.PointF`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Belirtilen `Aspose.Imaging.PointF` değerini, `Aspose.Imaging.Point` değerlerini en yakın tam sayıya yuvarlayarak bir `Aspose.Imaging.Point` nesnesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Dönüştürülecek `Aspose.Imaging.PointF`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Belirtilen `Aspose.Imaging.PointF` değerini, `Aspose.Imaging.Point` değerlerini kırparak bir `Aspose.Imaging.Point` değerine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Dönüştürülecek `Aspose.Imaging.PointF`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Bir `Aspose.Imaging.Point` değerini verilen bir `Aspose.Imaging.Size` ile kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Kaydırılacak `Aspose.Imaging.Point`. |
| size | [Size](../../com.aspose.imaging/size) | `point` koordinatlarına eklenecek sayı çiftini belirten bir `Aspose.Imaging.Size`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Bir `Aspose.Imaging.Point` değerini verilen bir `Aspose.Imaging.Size` değerinin negatifine göre kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Kaydırılacak `Aspose.Imaging.Point`. |
| size | [Size](../../com.aspose.imaging/size) | `point` koordinatlarından çıkarılacak sayı çiftini belirten bir `Aspose.Imaging.Size`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


İki `Aspose.Imaging.Point` nesnesini karşılaştırır. Sonuç, iki `Aspose.Imaging.Point` nesnesinin `Aspose.Imaging.Point.X` ve `Aspose.Imaging.Point.Y` özelliklerinin değerlerinin eşit olup olmadığını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Karşılaştırılacak ilk `Aspose.Imaging.Point`. |
| point2 | [Point](../../com.aspose.imaging/point) | Karşılaştırılacak ikinci `Aspose.Imaging.Point`. |

**Returns:**
boolean - `point1` ve `point2`'nin `Aspose.Imaging.Point.X` ve `Aspose.Imaging.Point.Y` değerleri eşitse true; aksi takdirde false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


İki `Aspose.Imaging.Point` nesnesini karşılaştırır. Sonuç, iki `Aspose.Imaging.Point` nesnesinin `Aspose.Imaging.Point.X` veya `Aspose.Imaging.Point.Y` özelliklerinin değerlerinin eşit olmamasını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Karşılaştırılacak ilk `Aspose.Imaging.Point`. |
| point2 | [Point](../../com.aspose.imaging/point) | Karşılaştırılacak ikinci `Aspose.Imaging.Point`. |

**Returns:**
boolean - `point1` ve `point2`'nin `Aspose.Imaging.Point.X` veya `Aspose.Imaging.Point.Y` özelliklerinden birinin değeri farklıysa true; aksi takdirde false.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Belirtilen `Aspose.Imaging.Point` yapısını bir `Aspose.Imaging.Size` yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Dönüştürülecek `Aspose.Imaging.Point`. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Belirtilen `Point` yapısını `PointF` yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Dönüştürülecek `Point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Bir uzun (long) nesne içinde paketlenmiş bir Point nesnesini, X ve Y tamsayı değerlerine ayırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| packedPoint | long | Bir uzun değer içinde paketlenmiş Point nesnesi. |
| x | int[] | Paketlenmiş Point'ten çıkarılan X değeri. |
| y | int[] | Paketlenmiş Point'ten çıkarılan Y değeri. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu `Aspose.Imaging.Point` nesnesinin boş olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - `Aspose.Imaging.Point.X` ve `Aspose.Imaging.Point.Y` her ikisi de 0 ise true; aksi takdirde false.
### getX() {#getX--}
```
public int getX()
```


Bu `Aspose.Imaging.Point` nesnesinin x-koordinatını alır veya ayarlar.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Bu `Aspose.Imaging.Point` nesnesinin x-koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getY() {#getY--}
```
public int getY()
```


Bu `Aspose.Imaging.Point` nesnesinin y-koordinatını alır veya ayarlar.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Bu `Aspose.Imaging.Point` nesnesinin y-koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Bu `Aspose.Imaging.Point` nesnesini belirtilen `Aspose.Imaging.Point` ile kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Bu `Aspose.Imaging.Point`'i ofsetlemek için kullanılan `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Bu `Aspose.Imaging.Point` nesnesini belirtilen miktarda kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | int | x koordinatını ofsetlemek için miktar. |
| dy | int | y koordinatını ofsetlemek için miktar. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu `Aspose.Imaging.Point` nesnesinin belirtilen `System.Object` ile aynı koordinatları içerip içermediğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek `System.Object`. |

**Returns:**
boolean - `obj` bir `Aspose.Imaging.Point` ise ve bu `Aspose.Imaging.Point` ile aynı koordinatlara sahipse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu `Aspose.Imaging.Point` nesnesi için bir karma (hash) kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
### toLong() {#toLong--}
```
public final long toLong()
```


Bu Point nesnesini, X ve Y koordinatlarını yüksek ve düşük bitlerde içeren tek bir uzun (long) değere dönüştürür.

**Returns:**
long - Bir uzun değer içinde paketlenmiş Point nesnesi.
### toString() {#toString--}
```
public String toString()
```


Bu `Aspose.Imaging.Point` nesnesini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir `System.String`.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
