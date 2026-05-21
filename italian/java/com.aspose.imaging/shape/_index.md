---
title: "Forma"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La forma."
type: docs
weight: 102
url: /it/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

La forma. Un insieme continuo di punti collegati mediante una regola specifica.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Shape()](#Shape--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCenter()](#getCenter--) | Ottiene il centro della forma. |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |
| [hasSegments()](#hasSegments--) | Ottiene un valore che indica se la forma ha segmenti. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Ottiene il centro della forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Ottiene i segmenti della forma.

**Returns:**
com.aspose.imaging.ShapeSegment[] - I segmenti della forma.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Ottiene un valore che indica se la forma ha segmenti.

**Returns:**
boolean - `True` se la forma ha segmenti; altrimenti, `false`.
