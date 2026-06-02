---
title: "BezierShape"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir bezier eğrisi temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Bir bezier eğrisi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BezierShape()](#BezierShape--) | Yeni bir `BezierShape` sınıfı örneğini başlatır. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | Yeni bir `BezierShape` sınıfı örneğini başlatır. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | Yeni bir `BezierShape` sınıfı örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [getCenter()](#getCenter--) | Şeklin merkezini alır. |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| [getEndPoint()](#getEndPoint--) | Bitiş şekil noktasını alır. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Nesnenin sınırlarını alır. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Yeni bir `BezierShape` sınıfı örneğini başlatır.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


Yeni bir `BezierShape` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Yeni bir `BezierShape` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Nokta dizisi. |
| isClosed | boolean | `true` olarak ayarlanırsa bezier spline kapatılır. |

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
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır.

Değer: Şeklin segmentleri varsa `True`; aksi takdirde `false`.

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Bitiş şekil noktasını alır.

Değer: Bitiş şekil noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
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
