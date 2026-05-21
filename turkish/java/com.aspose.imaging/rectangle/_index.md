---
title: "Dikdörtgen"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tamsayı setini depolar."
type: docs
weight: 93
url: /tr/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tamsayı setini depolar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Belirtilen konum ve boyutla yeni bir `com.aspose.imaging.Rectangle` yapısı örneği başlatır. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Belirtilen konum ve boyutla yeni bir `com.aspose.imaging.Rectangle` yapısı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmpty()](#getEmpty--) | `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` ve `com.aspose.imaging.Rectangle.Height` değerleri sıfıra ayarlanmış yeni bir `com.aspose.imaging.Rectangle` yapı örneği alır. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Belirtilen iki noktadan yeni bir `Rectangle` oluşturur. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Belirtilen `com.aspose.imaging.RectangleF` yapısını, `com.aspose.imaging.RectangleF` değerlerini bir üst tam sayıya yuvarlayarak bir `com.aspose.imaging.Rectangle` yapısına dönüştürür. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Belirtilen `com.aspose.imaging.RectangleF` değerlerini kırparak bir `com.aspose.imaging.Rectangle`'a dönüştürür. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Belirtilen `com.aspose.imaging.RectangleF` nesnesini, `com.aspose.imaging.RectangleF` değerlerini en yakın tam sayıya yuvarlayarak bir `com.aspose.imaging.Rectangle` nesnesine dönüştürür. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Belirtilen `com.aspose.imaging.Rectangle` yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | İki diğer `com.aspose.imaging.Rectangle` yapısının kesişimini temsil eden üçüncü bir `com.aspose.imaging.Rectangle` yapısını döndürür. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | İki `com.aspose.imaging.Rectangle` yapısının birleşimini içeren bir `com.aspose.imaging.Rectangle` yapısını alır. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | İki `com.aspose.imaging.Rectangle` yapısının konum ve boyutunun eşit olup olmadığını test eder. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | İki `com.aspose.imaging.Rectangle` yapısının konum veya boyut açısından farklı olup olmadığını test eder. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Belirtilen kenar konumlarıyla bir `com.aspose.imaging.Rectangle` yapısı oluşturur. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| [getSize()](#getSize--) | Bu `com.aspose.imaging.Rectangle` nesnesinin boyutunu alır veya ayarlar. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Bu `com.aspose.imaging.Rectangle` nesnesinin boyutunu alır veya ayarlar. |
| [getX()](#getX--) | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| [setX(int value)](#setX-int-) | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| [getY()](#getY--) | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
| [setY(int value)](#setY-int-) | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
| [getWidth()](#getWidth--) | Bu `com.aspose.imaging.Rectangle` yapısının genişliğini alır. |
| [setWidth(int value)](#setWidth-int-) | Bu `com.aspose.imaging.Rectangle` yapısının genişliğini ayarlar. |
| [getHeight()](#getHeight--) | Bu `com.aspose.imaging.Rectangle` yapısının yüksekliğini alır veya ayarlar. |
| [setHeight(int value)](#setHeight-int-) | Bu `com.aspose.imaging.Rectangle` yapısının yüksekliğini alır veya ayarlar. |
| [getLeft()](#getLeft--) | Bu `com.aspose.imaging.Rectangle` yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [setLeft(int value)](#setLeft-int-) | Bu `com.aspose.imaging.Rectangle` yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [getTop()](#getTop--) | Bu `com.aspose.imaging.Rectangle` yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [setTop(int value)](#setTop-int-) | Bu `com.aspose.imaging.Rectangle` yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [getRight()](#getRight--) | Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X` ve `com.aspose.imaging.Rectangle.Width` özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar. |
| [setRight(int value)](#setRight-int-) | Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X` ve `com.aspose.imaging.Rectangle.Width` özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar. |
| [getBottom()](#getBottom--) | Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.Y` ve `com.aspose.imaging.Rectangle.Height` özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar. |
| [setBottom(int value)](#setBottom-int-) | Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.Y` ve `com.aspose.imaging.Rectangle.Height` özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar. |
| [isEmpty()](#isEmpty--) | Bu `com.aspose.imaging.Rectangle` nesnesinin tüm sayısal özelliklerinin sıfır değerine sahip olup olmadığını gösteren bir değeri alır. |
| [contains(int x, int y)](#contains-int-int-) | Belirtilen noktanın bu `com.aspose.imaging.Rectangle` yapısı içinde bulunup bulunmadığını belirler. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Belirtilen noktanın bu `com.aspose.imaging.Rectangle` yapısı içinde bulunup bulunmadığını belirler. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | `rect` tarafından temsil edilen dikdörtgen bölgenin bu `com.aspose.imaging.Rectangle` yapısı içinde tamamen bulunup bulunmadığını belirler. |
| [inflate(int width, int height)](#inflate-int-int-) | Bu `com.aspose.imaging.Rectangle` nesnesini belirtilen miktarda şişirir. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Bu `com.aspose.imaging.Rectangle` nesnesini belirtilen miktarda şişirir. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Bu `com.aspose.imaging.Rectangle` nesnesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` nesnesinin kesişimiyle değiştirir. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Bu dikdörtgenin `rect` ile kesişip kesişmediğini belirler. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(int x, int y)](#offset-int-int-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [normalize()](#normalize--) | Dikdörtgeni genişlik ve yüksekliğini pozitif yaparak, solun sağdan, üstün alttan küçük olmasını sağlayarak normalleştirir. |
| [equals(Object obj)](#equals-java.lang.Object-) | `obj` nesnesinin bu `com.aspose.imaging.Rectangle` yapısıyla aynı konum ve boyuta sahip bir `com.aspose.imaging.Rectangle` yapısı olup olmadığını test eder. |
| [hashCode()](#hashCode--) | Bu `com.aspose.imaging.Rectangle` yapısı için karma kodunu döndürür. |
| [toString()](#toString--) | Bu `com.aspose.imaging.Rectangle` öğesinin özelliklerini insan tarafından okunabilir bir dizeye dönüştürür. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Belirtilen konum ve boyutla yeni bir `com.aspose.imaging.Rectangle` yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | int | Dikdörtgenin genişliği. |
| yükseklik | int | Dikdörtgenin yüksekliği. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Belirtilen konum ve boyutla yeni bir `com.aspose.imaging.Rectangle` yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | Dikdörtgen bölgenin sol üst köşesini temsil eden bir `com.aspose.imaging.Point`. |
| size | [Size](../../com.aspose.imaging/size) | Dikdörtgen bölgenin genişliğini ve yüksekliğini temsil eden bir `com.aspose.imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


`com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` ve `com.aspose.imaging.Rectangle.Height` değerleri sıfıra ayarlanmış yeni bir `com.aspose.imaging.Rectangle` yapı örneği alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Belirtilen iki noktadan yeni bir `Rectangle` oluşturur. Oluşturulan `Rectangle`'ın iki kenarı, verilen `point1` ve `point2` değerlerine eşit olacaktır. Bunlar genellikle karşıt köşeler olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Yeni dikdörtgen için ilk `Point`. |
| point2 | [Point](../../com.aspose.imaging/point) | Yeni dikdörtgen için ikinci `Point`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Belirtilen `com.aspose.imaging.RectangleF` yapısını, `com.aspose.imaging.RectangleF` değerlerini bir üst tam sayıya yuvarlayarak bir `com.aspose.imaging.Rectangle` yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Dönüştürülecek `com.aspose.imaging.RectangleF` yapısı. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Belirtilen `com.aspose.imaging.RectangleF` değerlerini kırparak bir `com.aspose.imaging.Rectangle`'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Dönüştürülecek `com.aspose.imaging.RectangleF`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Belirtilen `com.aspose.imaging.RectangleF` nesnesini, `com.aspose.imaging.RectangleF` değerlerini en yakın tam sayıya yuvarlayarak bir `com.aspose.imaging.Rectangle` nesnesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Dönüştürülecek `com.aspose.imaging.RectangleF`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Belirtilen `com.aspose.imaging.Rectangle` yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal `com.aspose.imaging.Rectangle` yapısı değiştirilmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Başlamak için kullanılacak `com.aspose.imaging.Rectangle`. Bu dikdörtgen değiştirilmez. |
| x | int | Bu `com.aspose.imaging.Rectangle`'ı yatay olarak şişirmek için miktar. |
| y | int | Bu `com.aspose.imaging.Rectangle`'ı dikey olarak şişirmek için miktar. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


İki diğer `com.aspose.imaging.Rectangle` yapısının kesişimini temsil eden üçüncü bir `com.aspose.imaging.Rectangle` yapısını döndürür. Kesişme yoksa, boş bir `com.aspose.imaging.Rectangle` döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Kesişmek için birinci dikdörtgen. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Kesişmek için ikinci dikdörtgen. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


İki `com.aspose.imaging.Rectangle` yapısının birleşimini içeren bir `com.aspose.imaging.Rectangle` yapısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Birleştirmek için birinci dikdörtgen. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Birleştirmek için ikinci dikdörtgen. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


İki `com.aspose.imaging.Rectangle` yapısının konum ve boyutunun eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | Eşitlik operatörünün solundaki `com.aspose.imaging.Rectangle` yapısı. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | Eşitlik operatörünün sağındaki `com.aspose.imaging.Rectangle` yapısı. |

**Returns:**
boolean - Bu operatör, iki `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` ve `com.aspose.imaging.Rectangle.Height` özellikleri eşit ise true döndürür.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


İki `com.aspose.imaging.Rectangle` yapısının konum veya boyut açısından farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | Eşitsizlik operatörünün solundaki `com.aspose.imaging.Rectangle` yapısı. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | Eşitsizlik operatörünün sağındaki `com.aspose.imaging.Rectangle` yapısı. |

**Returns:**
boolean - Bu operatör, iki `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` veya `com.aspose.imaging.Rectangle.Height` özelliklerinden herhangi biri eşit değilse true; aksi takdirde false döndürür.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Belirtilen kenar konumlarıyla bir `com.aspose.imaging.Rectangle` yapısı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | int | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin x koordinatı. |
| üst | int | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin y koordinatı. |
| sağ | int | Bu `com.aspose.imaging.Rectangle` yapısının sağ alt köşesinin x koordinatı. |
| alt | int | Bu `com.aspose.imaging.Rectangle` yapısının sağ alt köşesinin y koordinatı. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin koordinatlarını alır veya ayarlar.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin koordinatlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesini temsil eden bir `Point`. |

### getSize() {#getSize--}
```
public Size getSize()
```


Bu `com.aspose.imaging.Rectangle` nesnesinin boyutunu alır veya ayarlar.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Bu `com.aspose.imaging.Rectangle` nesnesinin boyutunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | Bu `com.aspose.imaging.Rectangle` yapısının genişliğini ve yüksekliğini temsil eden bir `com.aspose.imaging.Size`. |

### getX() {#getX--}
```
public int getX()
```


Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin x koordinatını alır veya ayarlar.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin x koordinatı.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin x koordinatı. |

### getY() {#getY--}
```
public int getY()
```


Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin y koordinatını alır veya ayarlar.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin y koordinatı.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının sol üst köşesinin y koordinatı. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu `com.aspose.imaging.Rectangle` yapısının genişliğini alır.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının genişliği.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının genişliği. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu `com.aspose.imaging.Rectangle` yapısının yüksekliğini alır veya ayarlar.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının yüksekliği.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının yüksekliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının yüksekliği. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Bu `com.aspose.imaging.Rectangle` yapısının sol kenarının x koordinatını alır veya ayarlar.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının sol kenarının x koordinatı.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının sol kenarının x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının sol kenarının x koordinatı. |

### getTop() {#getTop--}
```
public int getTop()
```


Bu `com.aspose.imaging.Rectangle` yapısının üst kenarının y koordinatını alır veya ayarlar.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının üst kenarının y koordinatı.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının üst kenarının y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının üst kenarının y koordinatı. |

### getRight() {#getRight--}
```
public int getRight()
```


Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X` ve `com.aspose.imaging.Rectangle.Width` özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X` ve `com.aspose.imaging.Rectangle.Width` toplamı olan x koordinatı.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X` ve `com.aspose.imaging.Rectangle.Width` özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.X` ve `com.aspose.imaging.Rectangle.Width` toplamı olan x koordinatı. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.Y` ve `com.aspose.imaging.Rectangle.Height` özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar.

**Returns:**
int - Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.Y` ve `com.aspose.imaging.Rectangle.Height` toplamı olan y koordinatı.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.Y` ve `com.aspose.imaging.Rectangle.Height` özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.Y` ve `com.aspose.imaging.Rectangle.Height` toplamı olan y koordinatı. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu `com.aspose.imaging.Rectangle` nesnesinin tüm sayısal özelliklerinin sıfır değerine sahip olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Bu özellik, bu `com.aspose.imaging.Rectangle` yapısının `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X` ve `com.aspose.imaging.Rectangle.Y` özelliklerinin tümünün sıfır değerine sahip olması durumunda true, aksi takdirde false döndürür.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Belirtilen noktanın bu `com.aspose.imaging.Rectangle` yapısı içinde bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem, `x` ve `y` ile tanımlanan noktanın bu `com.aspose.imaging.Rectangle` yapısı içinde bulunması durumunda true, aksi takdirde false döndürür.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Belirtilen noktanın bu `com.aspose.imaging.Rectangle` yapısı içinde bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Test edilecek `com.aspose.imaging.Point`. |

**Returns:**
boolean - Bu yöntem, `point` tarafından temsil edilen noktanın bu `com.aspose.imaging.Rectangle` yapısı içinde bulunması durumunda true, aksi takdirde false döndürür.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


`rect` tarafından temsil edilen dikdörtgen bölgenin bu `com.aspose.imaging.Rectangle` yapısı içinde tamamen bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Test edilecek `com.aspose.imaging.Rectangle`. |

**Returns:**
boolean - Bu yöntem, `rect` tarafından temsil edilen dikdörtgen bölgenin bu `com.aspose.imaging.Rectangle` yapısı içinde tamamen bulunması durumunda true, aksi takdirde false döndürür.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Bu `com.aspose.imaging.Rectangle` nesnesini belirtilen miktarda şişirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Bu `com.aspose.imaging.Rectangle`'ı yatay olarak şişirmek için miktar. |
| yükseklik | int | Bu `com.aspose.imaging.Rectangle`'ı dikey olarak şişirmek için miktar. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Bu `com.aspose.imaging.Rectangle` nesnesini belirtilen miktarda şişirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Bu dikdörtgeni şişirme miktarı. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Bu `com.aspose.imaging.Rectangle` nesnesini, kendisi ile belirtilen `com.aspose.imaging.Rectangle` nesnesinin kesişimiyle değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Kesişmek için kullanılacak `com.aspose.imaging.Rectangle`. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Bu dikdörtgenin `rect` ile kesişip kesişmediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Test edilecek dikdörtgen. |

**Returns:**
boolean - Bu yöntem, herhangi bir kesişim olması durumunda true, aksi takdirde false döndürür.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Konumu ofsetlemek için miktar. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Yatay ofset. |
| y | int | Dikey ofset. |

### normalize() {#normalize--}
```
public void normalize()
```


Dikdörtgeni genişlik ve yüksekliğini pozitif yaparak, solun sağdan, üstün alttan küçük olmasını sağlayarak normalleştirir.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


`obj` nesnesinin bu `com.aspose.imaging.Rectangle` yapısıyla aynı konum ve boyuta sahip bir `com.aspose.imaging.Rectangle` yapısı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek `System.Object`. |

**Returns:**
boolean - Bu yöntem, `obj` bir `com.aspose.imaging.Rectangle` yapısı ise ve onun `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` ve `com.aspose.imaging.Rectangle.Height` özellikleri bu `com.aspose.imaging.Rectangle` yapısının ilgili özelliklerine eşit olduğunda true, aksi takdirde false döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu `com.aspose.imaging.Rectangle` yapısı için karma kodunu döndürür.

**Returns:**
int - Bu dikdörtgen için karma kodunu temsil eden bir tamsayı.
### toString() {#toString--}
```
public String toString()
```


Bu `com.aspose.imaging.Rectangle` öğesinin özelliklerini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu `com.aspose.imaging.Rectangle` yapısının konumunu, genişliğini ve yüksekliğini içeren bir dize.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
