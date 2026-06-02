---
title: "BezierSegment"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bezier-segmentet som går från en punkt till nästa punkt och använder två kontrollpunkter."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Bezier-segmentet som går från en punkt till nästa punkt och använder två kontrollpunkter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Initierar en ny instans av klassen `BezierSegment`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Hämtar den första kontrollpunkten för en bezier-spline. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Hämtar den andra kontrollpunkten för en bezier-spline. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Initierar en ny instans av klassen `BezierSegment`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | Startpunkten. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | Den första kontrollpunkten. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | Den andra kontrollpunkten. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | Slutpunkten. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Hämtar den första kontrollpunkten för en bezier-spline.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Hämtar den andra kontrollpunkten för en bezier-spline.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
