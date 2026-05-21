---
title: "RectangleProjectedShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en form som projiceras över en rektangel som är vriden till en viss orientering."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Representerar en form som projiceras över en rektangel vriden till en viss orientering. Anges av fyra punkter som kan roteras i rymden samtidigt som samma kantlängd och 90 grader mellan intilliggande kanter bibehålls.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | Hämtar den övre vänstra rektangelpunkten. |
| [getRightTop()](#getRightTop--) | Hämtar den övre högra rektangelpunkten. |
| [getLeftBottom()](#getLeftBottom--) | Hämtar den nedre vänstra rektangelpunkten. |
| [getRightBottom()](#getRightBottom--) | Hämtar den nedre högra rektangelpunkten. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getRectangleWidth()](#getRectangleWidth--) | Hämtar rektangelns bredd. |
| [getRectangleHeight()](#getRectangleHeight--) | Hämtar rektangelns höjd. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Hämtar objektets gränser. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna `Object` är lika med detta objekt. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Hämtar den övre vänstra rektangelpunkten.

Värde: Den övre vänstra rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Hämtar den övre högra rektangelpunkten.

Värde: Den övre högra rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Hämtar den nedre vänstra rektangelpunkten.

Värde: Den nedre vänstra rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Hämtar den nedre högra rektangelpunkten.

Värde: Den nedre högra rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Hämtar formens centrum.

Värde: Formens centrum.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar objektets gränser.

Värde: Objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Hämtar rektangelns bredd.

Värde: Rektangelns bredd.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Hämtar rektangelns höjd.

Värde: Rektangelns höjd.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Hämtar ett värde som indikerar om formen har segment.

Värde: `True` om formen har segment; annars `false`.

**Returns:**
boolean
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
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Transformationen att tillämpa. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna `Object` är lika med detta objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `Object` att jämföra med den här instansen. |

**Returns:**
boolean - `true` om det angivna `Object` är lika med den här instansen; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
