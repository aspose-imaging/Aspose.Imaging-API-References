---
title: "ObjectWithBounds"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Objekt mit Begrenzungen."
type: docs
weight: 77
url: /de/java/com.aspose.imaging/objectwithbounds/
---
**Inheritance:**
java.lang.Object
```
public abstract class ObjectWithBounds
```

Das Objekt mit Begrenzungen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ObjectWithBounds()](#ObjectWithBounds--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ruft die Begrenzungen des Objekts ab. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
### ObjectWithBounds() {#ObjectWithBounds--}
```
public ObjectWithBounds()
```


### getBounds() {#getBounds--}
```
public abstract RectangleF getBounds()
```


Ruft die Begrenzungen des Objekts ab.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
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
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
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
public abstract void transform(Matrix transform)
```


Wendet die angegebene Transformation auf die Form an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Die anzuwendende Transformation. |

