---
title: "Forme"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La forme."
type: docs
weight: 102
url: /fr/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

La forme. Un ensemble continu de points reliés selon une règle spécifique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Shape()](#Shape--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCenter()](#getCenter--) | Obtient le centre de la forme. |
| [getSegments()](#getSegments--) | Obtient les segments de la forme. |
| [hasSegments()](#hasSegments--) | Obtient une valeur indiquant si la forme possède des segments. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Obtient le centre de la forme.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Obtient les segments de la forme.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Les segments de la forme.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Obtient une valeur indiquant si la forme possède des segments.

**Returns:**
boolean - `True` si la forme possède des segments ; sinon, `false`.
