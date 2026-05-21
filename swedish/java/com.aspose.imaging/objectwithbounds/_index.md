---
title: "ObjectWithBounds"
second_title: "Aspose.Imaging för Java API-referens"
description: "Objektet som har gränser."
type: docs
weight: 77
url: /sv/java/com.aspose.imaging/objectwithbounds/
---
**Inheritance:**
java.lang.Object
```
public abstract class ObjectWithBounds
```

Objektet som har gränser.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ObjectWithBounds()](#ObjectWithBounds--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Hämtar objektets gränser. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Tillämpar den angivna transformationen på formen. |
### ObjectWithBounds() {#ObjectWithBounds--}
```
public ObjectWithBounds()
```


### getBounds() {#getBounds--}
```
public abstract RectangleF getBounds()
```


Hämtar objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
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
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
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
public abstract void transform(Matrix transform)
```


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Transformationen att tillämpa. |

