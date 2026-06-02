---
title: "Form"
second_title: "Aspose.Imaging för Java API-referens"
description: "Formen."
type: docs
weight: 102
url: /sv/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

Formen. En kontinuerlig uppsättning punkter som är sammankopplade med en specifik regel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Shape()](#Shape--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Hämtar formens centrum.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Hämtar formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Formens segment.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Hämtar ett värde som indikerar om formen har segment.

**Returns:**
boolean - `True` om formen har segment; annars `false`.
