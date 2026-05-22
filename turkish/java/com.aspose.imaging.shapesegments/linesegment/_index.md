---
title: "LineSegment"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Belirli bir noktadan bir sonraki noktaya doğrudan giden bir segmenti temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.shapesegments/linesegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment)
```
public class LineSegment extends ShapeSegment
```

Belirli bir noktadan bir sonraki noktaya doğrudan giden bir segmenti temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LineSegment(PointF startPoint, PointF endPoint)](#LineSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Yeni bir `LineSegment` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStartPoint()](#getStartPoint--) | Başlangıç noktasını alır. |
| [getEndPoint()](#getEndPoint--) | Bitiş noktasını alır. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### LineSegment(PointF startPoint, PointF endPoint) {#LineSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LineSegment(PointF startPoint, PointF endPoint)
```


Yeni bir `LineSegment` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | Başlangıç noktası. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | Bitiş noktası. |

### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Başlangıç noktasını alır.

Değer: Başlangıç noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Bitiş noktasını alır.

Değer: Bitiş noktası.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
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
