---
title: "RectangleProjectedShape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Belirli bir yönlendirmeye dönüştürülmüş dikdörtgen üzerine yansıtılan bir şekli temsil eder."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Belirli bir yönlendirmeye döndürülmüş dikdörtgen üzerine yansıtılan bir şekli temsil eder. Aynı kenar uzunluğunu koruyarak ve komşu kenarlar arasında 90 derece açı bırakarak uzayda döndürülebilen dört nokta ile tanımlanır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | Sol üst dikdörtgen noktasını alır. |
| [getRightTop()](#getRightTop--) | Sağ üst dikdörtgen noktasını alır. |
| [getLeftBottom()](#getLeftBottom--) | Sol alt dikdörtgen noktasını alır. |
| [getRightBottom()](#getRightBottom--) | Sağ alt dikdörtgen noktasını alır. |
| [getCenter()](#getCenter--) | Şeklin merkezini alır. |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [getRectangleWidth()](#getRectangleWidth--) | Dikdörtgen genişliğini alır. |
| [getRectangleHeight()](#getRectangleHeight--) | Dikdörtgen yüksekliğini alır. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Nesnenin sınırlarını alır. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `Object`'in bu örnekle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Sol üst dikdörtgen noktasını alır.

Değer: Sol üst dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Sağ üst dikdörtgen noktasını alır.

Değer: Sağ üst dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Sol alt dikdörtgen noktasını alır.

Değer: Sol alt dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Sağ alt dikdörtgen noktasını alır.

Değer: Sağ alt dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Şeklin merkezini alır.

Değer: Şeklin merkezi.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Nesnenin sınırlarını alır.

Değer: Nesnenin sınırları.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Dikdörtgen genişliğini alır.

Değer: Dikdörtgen genişliği.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Dikdörtgen yüksekliğini alır.

Değer: Dikdörtgen yüksekliği.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır.

Değer: Şeklin segmentleri varsa `True`; aksi takdirde `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](../../com.aspose.imaging/pen) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Belirtilen dönüşümü şekle uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Uygulanacak dönüşüm. |

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
