---
title: "BezierShape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Bézier-Kurve dar."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Stellt eine Bézier-Kurve dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BezierShape()](#BezierShape--) | Initialisiert eine neue Instanz der `BezierShape`-Klasse. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | Initialisiert eine neue Instanz der `BezierShape`-Klasse. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | Initialisiert eine neue Instanz der `BezierShape`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab. |
| [getCenter()](#getCenter--) | Liefert das Zentrum der Form. |
| [getSegments()](#getSegments--) | Liefert die Segmente der Form. |
| [hasSegments()](#hasSegments--) | Liefert einen Wert, der angibt, ob die Form Segmente hat. |
| [getEndPoint()](#getEndPoint--) | Ruft den Endpunkt der Form ab. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Initialisiert eine neue Instanz der `BezierShape`-Klasse.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


Initialisiert eine neue Instanz der `BezierShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Initialisiert eine neue Instanz der `BezierShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |
| isClosed | boolean | Wenn auf `true` gesetzt, ist der Bezier-Spline geschlossen. |

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
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Liefert einen Wert, der angibt, ob die Form Segmente hat.

Wert: `True`, wenn die Form Segmente hat; andernfalls `false`.

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Ruft den Endpunkt der Form ab.

Wert: Der Endpunkt der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
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
