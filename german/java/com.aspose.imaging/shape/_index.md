---
title: "Form"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Form."
type: docs
weight: 102
url: /de/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

Die Form. Eine kontinuierliche Menge von Punkten, die mittels einer bestimmten Regel verbunden sind.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Shape()](#Shape--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCenter()](#getCenter--) | Liefert das Zentrum der Form. |
| [getSegments()](#getSegments--) | Liefert die Segmente der Form. |
| [hasSegments()](#hasSegments--) | Liefert einen Wert, der angibt, ob die Form Segmente hat. |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Liefert das Zentrum der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Liefert die Segmente der Form.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Die Segmente der Form.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Liefert einen Wert, der angibt, ob die Form Segmente hat.

**Returns:**
boolean - `True` wenn die Form Segmente hat; andernfalls `false`.
