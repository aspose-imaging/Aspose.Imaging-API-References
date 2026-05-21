---
title: "RectangleF"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan noktalı sayı setini depolar."
type: docs
weight: 94
url: /tr/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan noktalı sayı setini depolar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Belirtilen konum ve boyutla `com.aspose.imaging.RectangleF` yapısının yeni bir örneğini başlatır. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Belirtilen konum ve boyutla `com.aspose.imaging.RectangleF` yapısının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmpty()](#getEmpty--) | `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` ve `com.aspose.imaging.RectangleF.Height` değerleri sıfıra ayarlanmış `com.aspose.imaging.RectangleF` yapısının yeni bir örneğini alır. |
| [getLocation()](#getLocation--) | Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşe koordinatlarını alır veya ayarlar. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşe koordinatlarını alır veya ayarlar. |
| [getSize()](#getSize--) | Bu `com.aspose.imaging.RectangleF` nesnesinin boyutunu alır veya ayarlar. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Bu `com.aspose.imaging.RectangleF` nesnesinin boyutunu alır veya ayarlar. |
| [getX()](#getX--) | Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| [setX(float value)](#setX-float-) | Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| [getY()](#getY--) | Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
| [setY(float value)](#setY-float-) | Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
| [getWidth()](#getWidth--) | Bu `com.aspose.imaging.RectangleF` yapısının genişliğini alır veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Bu `com.aspose.imaging.RectangleF` yapısının genişliğini alır veya ayarlar. |
| [getHeight()](#getHeight--) | Bu `com.aspose.imaging.RectangleF` yapısının yüksekliğini alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Bu `com.aspose.imaging.RectangleF` yapısının yüksekliğini alır veya ayarlar. |
| [getLeft()](#getLeft--) | Bu `com.aspose.imaging.RectangleF` yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [setLeft(float value)](#setLeft-float-) | Bu `com.aspose.imaging.RectangleF` yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [getTop()](#getTop--) | Bu `com.aspose.imaging.RectangleF` yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [setTop(float value)](#setTop-float-) | Bu `com.aspose.imaging.RectangleF` yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [getRight()](#getRight--) | Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.X` ve `com.aspose.imaging.RectangleF.Width` toplamı olan x koordinatını alır veya ayarlar. |
| [setRight(float value)](#setRight-float-) | Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.X` ve `com.aspose.imaging.RectangleF.Width` toplamı olan x koordinatını alır veya ayarlar. |
| [getBottom()](#getBottom--) | Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.Y` ve `com.aspose.imaging.RectangleF.Height` toplamı olan y koordinatını alır veya ayarlar. |
| [setBottom(float value)](#setBottom-float-) | Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.Y` ve `com.aspose.imaging.RectangleF.Height` toplamı olan y koordinatını alır veya ayarlar. |
| [isEmpty()](#isEmpty--) | Bu `com.aspose.imaging.RectangleF` nesnesinin `com.aspose.imaging.RectangleF.Width` veya `com.aspose.imaging.RectangleF.Height` özelliğinin sıfır olup olmadığını gösteren bir değeri alır. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Belirtilen iki noktadan yeni bir `Rectangle` oluşturur. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Belirtilen `com.aspose.imaging.RectangleF` yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | İki dikdörtgenin kesişimini temsil eden bir `com.aspose.imaging.RectangleF` yapısını döndürür. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Birleşim oluşturan iki dikdörtgeni içerebilecek en küçük üçüncü dikdörtgeni oluşturur. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | İki `com.aspose.imaging.RectangleF` yapısının konum ve boyutunun eşit olup olmadığını test eder. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | İki `com.aspose.imaging.RectangleF` yapısının konum veya boyutta farklı olup olmadığını test eder. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | \* operatörünü uygular. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | / operatörünü uygular. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Belirtilen `com.aspose.imaging.Rectangle` yapısını bir `com.aspose.imaging.RectangleF` yapısına dönüştürür. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Sol üst köşe ve sağ alt köşe belirtilen konumlarda olan bir `com.aspose.imaging.RectangleF` yapısı oluşturur. |
| [normalize()](#normalize--) | Genişlik ve yüksekliği pozitif, solun sağdan, üstün alttan küçük olmasını sağlayarak dikdörtgeni normalleştirir. |
| [contains(float x, float y)](#contains-float-float-) | Belirtilen noktanın bu `com.aspose.imaging.RectangleF` yapısı içinde olup olmadığını belirler. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Belirtilen noktanın bu `com.aspose.imaging.RectangleF` yapısı içinde olup olmadığını belirler. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Bu `com.aspose.imaging.RectangleF` yapısı içinde, `rect` tarafından temsil edilen dikdörtgen bölgenin tamamen içerilip içerilmediğini belirler. |
| [inflate(float x, float y)](#inflate-float-float-) | Bu `com.aspose.imaging.RectangleF` yapısını belirtilen miktarda genişletir. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Bu `com.aspose.imaging.RectangleF`'i belirtilen miktarda genişletir. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Bu `com.aspose.imaging.RectangleF` yapısını, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının kesişimiyle değiştirir. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Bu dikdörtgenin `rect` ile kesişip kesişmediğini belirler. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(float x, float y)](#offset-float-float-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | `obj`'nin bu `com.aspose.imaging.RectangleF` ile aynı konuma ve boyuta sahip bir `com.aspose.imaging.RectangleF` olup olmadığını test eder. |
| [hashCode()](#hashCode--) | Bu `com.aspose.imaging.RectangleF` yapısı için karma kodunu alır. |
| [toString()](#toString--) | Bu `com.aspose.imaging.RectangleF`'in özelliklerini insan tarafından okunabilir bir dizeye dönüştürür. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Belirtilen konum ve boyutla `com.aspose.imaging.RectangleF` yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Dikdörtgenin sol üst köşesinin y koordinatı. |
| genişlik | float | Dikdörtgenin genişliği. |
| yükseklik | float | Dikdörtgenin yüksekliği. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Belirtilen konum ve boyutla `com.aspose.imaging.RectangleF` yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | Dikdörtgen bölgenin sol üst köşesini temsil eden bir `com.aspose.imaging.PointF`. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Dikdörtgen bölgenin genişliğini ve yüksekliğini temsil eden bir `com.aspose.imaging.SizeF`. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


`com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` ve `com.aspose.imaging.RectangleF.Height` değerleri sıfıra ayarlanmış `com.aspose.imaging.RectangleF` yapısının yeni bir örneğini alır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşe koordinatlarını alır veya ayarlar.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşe koordinatlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Bu `com.aspose.imaging.RectangleF` nesnesinin boyutunu alır veya ayarlar.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Bu `com.aspose.imaging.RectangleF` nesnesinin boyutunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin x koordinatını alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin x koordinatı.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getY() {#getY--}
```
public float getY()
```


Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin y koordinatını alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin y koordinatı.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının sol üst köşesinin y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Bu `com.aspose.imaging.RectangleF` yapısının genişliğini alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının genişliği.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının genişliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Bu `com.aspose.imaging.RectangleF` yapısının yüksekliğini alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının yüksekliği.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının yüksekliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Bu `com.aspose.imaging.RectangleF` yapısının sol kenarının x koordinatını alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının sol kenarının x koordinatı.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının sol kenarının x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Bu `com.aspose.imaging.RectangleF` yapısının üst kenarının y koordinatını alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının üst kenarının y koordinatı.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının üst kenarının y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.X` ve `com.aspose.imaging.RectangleF.Width` toplamı olan x koordinatını alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.X` ve `com.aspose.imaging.RectangleF.Width` toplamı olan x-koordinatı.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.X` ve `com.aspose.imaging.RectangleF.Width` toplamı olan x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.Y` ve `com.aspose.imaging.RectangleF.Height` toplamı olan y koordinatını alır veya ayarlar.

**Returns:**
float - Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.Y` ve `com.aspose.imaging.RectangleF.Height` toplamı olan y-koordinatı.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.Y` ve `com.aspose.imaging.RectangleF.Height` toplamı olan y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu `com.aspose.imaging.RectangleF` nesnesinin `com.aspose.imaging.RectangleF.Width` veya `com.aspose.imaging.RectangleF.Height` özelliğinin sıfır olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Bu `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.Width` veya `com.aspose.imaging.RectangleF.Height` özelliği sıfır değerine sahipse true döndürür; aksi takdirde false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Belirtilen iki noktadan yeni bir `Rectangle` oluşturur. Oluşturulan `Rectangle`'ın iki köşesi verilen `point1` ve `point2` değerlerine eşit olur. Bunlar genellikle karşıt köşelerdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Yeni dikdörtgen için ilk `Point`. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Yeni dikdörtgen için ikinci `Point`. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Belirtilen `com.aspose.imaging.RectangleF` yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Kopyalanacak `com.aspose.imaging.RectangleF`. Bu dikdörtgen değiştirilmez. |
| x | float | Dikdörtgenin kopyasını yatay olarak şişirmek için miktar. |
| y | float | Dikdörtgenin kopyasını dikey olarak şişirmek için miktar. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


İki dikdörtgenin kesişimini temsil eden bir `com.aspose.imaging.RectangleF` yapısı döndürür. Kesişme yoksa boş bir `com.aspose.imaging.RectangleF` döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Kesişmek için birinci dikdörtgen. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Kesişmek için ikinci dikdörtgen. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Birleşim oluşturan iki dikdörtgeni içerebilecek en küçük üçüncü dikdörtgeni oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Birleştirmek için birinci dikdörtgen. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Birleştirmek için ikinci dikdörtgen. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


İki `com.aspose.imaging.RectangleF` yapısının konum ve boyutunun eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | Eşitlik operatörünün solunda bulunan `com.aspose.imaging.RectangleF` yapısı. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | Eşitlik operatörünün sağında bulunan `com.aspose.imaging.RectangleF` yapısı. |

**Returns:**
boolean - Bu operatör, belirtilen iki `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` ve `com.aspose.imaging.RectangleF.Height` özellikleri eşitse true döndürür.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


İki `com.aspose.imaging.RectangleF` yapısının konum veya boyutta farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | Eşitsizlik operatörünün solunda bulunan `com.aspose.imaging.RectangleF` yapısı. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | Eşitsizlik operatörünün sağında bulunan `com.aspose.imaging.RectangleF` yapısı. |

**Returns:**
boolean - Bu operatör, iki `com.aspose.imaging.RectangleF` yapısının `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` veya `com.aspose.imaging.RectangleF.Height` özelliklerinden herhangi biri eşit değilse true döndürür; aksi takdirde false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


\* operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Dikdörtgen. |
| çarpan | float | Çarpan. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


/ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Dikdörtgen. |
| bölen | float | Bölen. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Belirtilen `com.aspose.imaging.Rectangle` yapısını bir `com.aspose.imaging.RectangleF` yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Dönüştürülecek `com.aspose.imaging.Rectangle` yapısı. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Sol üst köşe ve sağ alt köşe belirtilen konumlarda olan bir `com.aspose.imaging.RectangleF` yapısı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | float | Dikdörtgen bölgenin sol üst köşesinin x koordinatı. |
| üst | float | Dikdörtgen bölgenin sol üst köşesinin y koordinatı. |
| sağ | float | Dikdörtgen bölgenin sağ alt köşesinin x koordinatı. |
| alt | float | Dikdörtgen bölgenin sağ alt köşesinin y koordinatı. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Genişlik ve yüksekliği pozitif, solun sağdan, üstün alttan küçük olmasını sağlayarak dikdörtgeni normalleştirir.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Belirtilen noktanın bu `com.aspose.imaging.RectangleF` yapısı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem, `x` ve `y` ile tanımlanan nokta bu `com.aspose.imaging.RectangleF` yapısı içinde bulunuyorsa true döndürür; aksi takdirde false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Belirtilen noktanın bu `com.aspose.imaging.RectangleF` yapısı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Test edilecek `com.aspose.imaging.PointF`. |

**Returns:**
boolean - Bu yöntem, `point` parametresiyle temsil edilen nokta bu `com.aspose.imaging.RectangleF` yapısı içinde bulunuyorsa true döndürür; aksi takdirde false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Bu `com.aspose.imaging.RectangleF` yapısı içinde, `rect` tarafından temsil edilen dikdörtgen bölgenin tamamen içerilip içerilmediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Test edilecek `com.aspose.imaging.RectangleF`. |

**Returns:**
boolean - Bu yöntem, `rect` ile temsil edilen dikdörtgen bölge bu `com.aspose.imaging.RectangleF` tarafından temsil edilen dikdörtgen bölge içinde tamamen bulunuyorsa true döndürür; aksi takdirde false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Bu `com.aspose.imaging.RectangleF` yapısını belirtilen miktarda genişletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Bu `com.aspose.imaging.RectangleF` yapısını yatay olarak şişirme miktarı. |
| y | float | Bu `com.aspose.imaging.RectangleF` yapısını dikey olarak şişirme miktarı. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Bu `com.aspose.imaging.RectangleF`'i belirtilen miktarda genişletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Bu dikdörtgeni şişirme miktarı. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Bu `com.aspose.imaging.RectangleF` yapısını, kendisi ile belirtilen `com.aspose.imaging.RectangleF` yapısının kesişimiyle değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Kesişecek dikdörtgen. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Bu dikdörtgenin `rect` ile kesişip kesişmediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Test edilecek dikdörtgen. |

**Returns:**
boolean - Bu yöntem, herhangi bir kesişme varsa true döndürür.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | Konumu kaydırma miktarı. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Konumu yatay olarak kaydırma miktarı. |
| y | float | Konumu dikey olarak kaydırma miktarı. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


`obj`'nin bu `com.aspose.imaging.RectangleF` ile aynı konuma ve boyuta sahip bir `com.aspose.imaging.RectangleF` olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek `System.Object`. |

**Returns:**
boolean - Bu yöntem, `obj` bir `com.aspose.imaging.RectangleF` ise ve X, Y, Width ve Height özellikleri bu `com.aspose.imaging.RectangleF` nesnesinin ilgili özelliklerine eşitse true döndürür; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu `com.aspose.imaging.RectangleF` yapısı için karma kodunu alır.

**Returns:**
int - Bu `com.aspose.imaging.RectangleF` nesnesinin hash kodu.
### toString() {#toString--}
```
public String toString()
```


Bu `com.aspose.imaging.RectangleF`'in özelliklerini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu `com.aspose.imaging.RectangleF` yapısının konum, genişlik ve yükseklik değerlerini içeren bir dize.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
