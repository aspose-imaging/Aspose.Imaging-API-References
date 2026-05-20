---
title: "BezierSegment"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Bézier‑Segment, das von einem Punkt zum nächsten Punkt verläuft und zwei Kontrollpunkte verwendet."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Das Bézier‑Segment, das von einem Punkt zum nächsten Punkt verläuft und zwei Kontrollpunkte verwendet.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Initialisiert eine neue Instanz der `BezierSegment`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Liefert den ersten Kontrollpunkt einer Bezier-Kurve. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Liefert den zweiten Kontrollpunkt einer Bezier-Kurve. |
| [equals(Object obj)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Initialisiert eine neue Instanz der `BezierSegment`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | Der Startpunkt. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | Der erste Kontrollpunkt. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | Der zweite Kontrollpunkt. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | Der Endpunkt. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Liefert den ersten Kontrollpunkt einer Bezier-Kurve.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Liefert den zweiten Kontrollpunkt einer Bezier-Kurve.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
