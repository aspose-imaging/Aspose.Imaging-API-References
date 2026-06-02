---
title: "Forma"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La forma."
type: docs
weight: 102
url: /es/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

La forma. Un conjunto continuo de puntos conectados mediante una regla específica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Shape()](#Shape--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCenter()](#getCenter--) | Obtiene el centro de la forma. |
| [getSegments()](#getSegments--) | Obtiene los segmentos de la forma. |
| [hasSegments()](#hasSegments--) | Obtiene un valor que indica si la forma tiene segmentos. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Obtiene el centro de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Obtiene los segmentos de la forma.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Los segmentos de la forma.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Obtiene un valor que indica si la forma tiene segmentos.

**Returns:**
boolean - `True` si la forma tiene segmentos; de lo contrario, `false`.
