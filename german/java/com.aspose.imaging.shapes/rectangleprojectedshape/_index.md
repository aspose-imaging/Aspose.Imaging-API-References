---
title: "RectangleProjectedShape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Form dar, die über ein Rechteck projiziert wird, das in eine bestimmte Ausrichtung gedreht ist."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Stellt eine Form dar, die über ein Rechteck projiziert wird, das in eine bestimmte Ausrichtung gedreht ist. Sie wird durch vier Punkte definiert, die im Raum rotiert werden können, wobei die gleiche Kantenlänge und 90 Grad zwischen benachbarten Kanten beibehalten werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | Ruft den linken oberen Rechteckpunkt ab. |
| [getRightTop()](#getRightTop--) | Ruft den rechten oberen Rechteckpunkt ab. |
| [getLeftBottom()](#getLeftBottom--) | Ruft den linken unteren Rechteckpunkt ab. |
| [getRightBottom()](#getRightBottom--) | Ruft den rechten unteren Rechteckpunkt ab. |
| [getCenter()](#getCenter--) | Liefert das Zentrum der Form. |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab. |
| [getRectangleWidth()](#getRectangleWidth--) | Ruft die Rechteckbreite ab. |
| [getRectangleHeight()](#getRectangleHeight--) | Ruft die Rechteckhöhe ab. |
| [hasSegments()](#hasSegments--) | Liefert einen Wert, der angibt, ob die Form Segmente hat. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ruft die Begrenzungen des Objekts ab. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Ruft den linken oberen Rechteckpunkt ab.

Wert: Der linke obere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Ruft den rechten oberen Rechteckpunkt ab.

Wert: Der rechte obere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Ruft den linken unteren Rechteckpunkt ab.

Wert: Der linke untere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Ruft den rechten unteren Rechteckpunkt ab.

Wert: Der rechte untere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Liefert das Zentrum der Form.

Wert: Der Mittelpunkt der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ruft die Begrenzungen des Objekts ab.

Wert: Die Begrenzungen des Objekts.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Ruft die Rechteckbreite ab.

Wert: Die Rechteckbreite.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Ruft die Rechteckhöhe ab.

Wert: Die Rechteckhöhe.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Liefert einen Wert, der angibt, ob die Form Segmente hat.

Wert: `True`, wenn die Form Segmente hat; andernfalls `false`.

**Returns:**
boolean
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
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Wendet die angegebene Transformation auf die Form an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Die anzuwendende Transformation. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true` wenn das angegebene `Object` dieser Instanz gleich ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
