---
title: "CurveShape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Kıvrımlı bir eğri şekli temsil eder."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.shapes/curveshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Kıvrımlı bir eğri şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CurveShape()](#CurveShape--) | Yeni bir `CurveShape` sınıfının örneğini başlatır. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.imaging.PointF---) | Yeni bir `CurveShape` sınıfının örneğini başlatır. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---boolean-) | Yeni bir `CurveShape` sınıfının örneğini başlatır. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.imaging.PointF---float-) | Yeni bir `CurveShape` sınıfının örneğini başlatır. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---float-boolean-) | Yeni bir `CurveShape` sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTension()](#getTension--) | Eğri gerginliğini alır veya ayarlar. |
| [setTension(float value)](#setTension-float-) | Eğri gerginliğini alır veya ayarlar. |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [getCenter()](#getCenter--) | Şeklin merkezini alır. |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Nesnenin sınırlarını alır. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Yeni bir `CurveShape` sınıfının örneğini başlatır.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.imaging.PointF---}
```
public CurveShape(PointF[] points)
```


`CurveShape` sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerginlik kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


`CurveShape` sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerginlik kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.imaging.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Yeni bir `CurveShape` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |
| gerginlik | float | Eğri gerginliği. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Yeni bir `CurveShape` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |
| gerginlik | float | Eğri gerginliği. |
| isClosed | boolean | Eğer `true` olarak ayarlanırsa eğri kapalıdır. |

### getTension() {#getTension--}
```
public float getTension()
```


Eğri gerginliğini alır veya ayarlar.

Değer: Eğri gerginliği.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Eğri gerginliğini alır veya ayarlar.

Değer: Eğri gerginliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Nesnenin sınırlarını alır.

Değer: Nesnenin sınırları.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Şeklin merkezini alır.

Değer: Şeklin merkezi.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Şekil segmentlerini alır.

Değer: Şekil segmentleri.

**Returns:**
com.aspose.imaging.ShapeSegment[]
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
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
