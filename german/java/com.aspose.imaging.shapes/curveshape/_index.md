---
title: "CurveShape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine gekrümmte Spline-Form dar."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.shapes/curveshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Stellt eine gekrümmte Spline-Form dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurveShape()](#CurveShape--) | Initialisiert eine neue Instanz der `CurveShape`-Klasse. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.imaging.PointF---) | Initialisiert eine neue Instanz der `CurveShape`-Klasse. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---boolean-) | Initialisiert eine neue Instanz der `CurveShape`-Klasse. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.imaging.PointF---float-) | Initialisiert eine neue Instanz der `CurveShape`-Klasse. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---float-boolean-) | Initialisiert eine neue Instanz der `CurveShape`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTension()](#getTension--) | Liest oder setzt die Kurvenspannung. |
| [setTension(float value)](#setTension-float-) | Liest oder setzt die Kurvenspannung. |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab. |
| [getCenter()](#getCenter--) | Liefert das Zentrum der Form. |
| [getSegments()](#getSegments--) | Liefert die Segmente der Form. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ruft die Begrenzungen des Objekts ab. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Initialisiert eine neue Instanz der `CurveShape`-Klasse.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.imaging.PointF---}
```
public CurveShape(PointF[] points)
```


Initialisiert eine neue Instanz der `CurveShape`-Klasse. Die Standardspannung von 0,5 wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Initialisiert eine neue Instanz der `CurveShape`-Klasse. Die Standardspannung von 0,5 wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.imaging.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Initialisiert eine neue Instanz der `CurveShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |
| tension | float | Die Kurvenspannung. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Initialisiert eine neue Instanz der `CurveShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |
| tension | float | Die Kurvenspannung. |
| isClosed | boolean | Wenn auf `true` gesetzt, ist die Kurve geschlossen. |

### getTension() {#getTension--}
```
public float getTension()
```


Liest oder setzt die Kurvenspannung.

Wert: Die Kurvenspannung.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Liest oder setzt die Kurvenspannung.

Wert: Die Kurvenspannung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ruft die Begrenzungen des Objekts ab.

Wert: Die Begrenzungen des Objekts.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Liefert das Zentrum der Form.

Wert: Der Mittelpunkt der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Liefert die Segmente der Form.

Wert: Die Formsegmente.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ruft die Begrenzungen des Objekts ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ruft die Begrenzungen des Objekts ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Objektgrenzen beeinflussen. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
