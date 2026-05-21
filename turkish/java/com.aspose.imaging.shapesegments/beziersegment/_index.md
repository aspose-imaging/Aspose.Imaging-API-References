---
title: "BezierSegment"
second_title: "Aspose.Imaging for Java API Referansı"
description: "İki kontrol noktası kullanarak bir noktadan bir sonraki noktaya giden bezier segmenti."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

İki kontrol noktası kullanarak bir noktadan bir sonraki noktaya giden bezier segmenti.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Yeni bir `BezierSegment` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Bir bezier spline'ının ilk kontrol noktasını alır. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Bir bezier spline'ının ikinci kontrol noktasını alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Yeni bir `BezierSegment` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | Başlangıç noktası. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | İlk kontrol noktası. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | İkinci kontrol noktası. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | Bitiş noktası. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Bir bezier spline'ının ilk kontrol noktasını alır.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Bir bezier spline'ının ikinci kontrol noktasını alır.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
