---
title: "CurveShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en kurvad splineform."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.shapes/curveshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Representerar en kurvad splineform.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CurveShape()](#CurveShape--) | Initierar en ny instans av klassen `CurveShape`. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.imaging.PointF---) | Initierar en ny instans av klassen `CurveShape`. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---boolean-) | Initierar en ny instans av klassen `CurveShape`. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.imaging.PointF---float-) | Initierar en ny instans av klassen `CurveShape`. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---float-boolean-) | Initierar en ny instans av klassen `CurveShape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTension()](#getTension--) | Hämtar eller anger kurvspänningen. |
| [setTension(float value)](#setTension-float-) | Hämtar eller anger kurvspänningen. |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Hämtar objektets gränser. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Initierar en ny instans av klassen `CurveShape`.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.imaging.PointF---}
```
public CurveShape(PointF[] points)
```


Initierar en ny instans av klassen `CurveShape`. Standardspänningen 0,5 används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Initierar en ny instans av klassen `CurveShape`. Standardspänningen 0,5 används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.imaging.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Initierar en ny instans av klassen `CurveShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |
| tension | float | Kurvspänningen. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Initierar en ny instans av klassen `CurveShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |
| tension | float | Kurvspänningen. |
| isClosed | boolean | Om den är satt till `true` är kurvan sluten. |

### getTension() {#getTension--}
```
public float getTension()
```


Hämtar eller anger kurvspänningen.

Värde: Kurvspänningen.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Hämtar eller anger kurvspänningen.

Värde: Kurvspänningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar objektets gränser.

Värde: Objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Hämtar formens centrum.

Värde: Formens centrum.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
