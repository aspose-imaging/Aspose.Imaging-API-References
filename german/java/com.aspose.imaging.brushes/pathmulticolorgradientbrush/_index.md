---
title: "PathMulticolorGradientBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Kapselt ein Aspose.Imaging.Brush-Objekt mit einem Verlauf."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.brushes/pathmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Kapselt ein `Aspose.Imaging.Brush`-Objekt mit einem Verlauf. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---) | Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten. |
| [PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-) | Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten und dem Wrap‑Modus. |
| [PathMulticolorGradientBrush(Point[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---) | Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten. |
| [PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-) | Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten und dem Wrap‑Modus. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-) | Initialisiert eine neue Instanz der `PathMulticolorGradientBrush`-Klasse mit dem angegebenen Pfad. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Liest oder setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Verlauf definiert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Liest oder setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Verlauf definiert. |
### PathMulticolorGradientBrush(PointF[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---}
```
public PathMulticolorGradientBrush(PointF[] pathPoints)
```


Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von [PointF](../../com.aspose.imaging/pointf)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

### PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)
```


Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten und dem Wrap‑Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von [PointF](../../com.aspose.imaging/pointf)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrapMode | int | Ein [WrapMode](../../com.aspose.imaging/wrapmode), das festlegt, wie Füllungen, die mit diesem [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) gezeichnet werden, gekachelt werden. |

### PathMulticolorGradientBrush(Point[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---}
```
public PathMulticolorGradientBrush(Point[] pathPoints)
```


Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | Ein Array von [Point](../../com.aspose.imaging/point)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

### PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-}
```
public PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)
```


Initialisiert eine neue Instanz der [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush)-Klasse mit den angegebenen Punkten und dem Wrap‑Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | Ein Array von [Point](../../com.aspose.imaging/point)-Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrapMode | int | Ein [WrapMode](../../com.aspose.imaging/wrapmode), das festlegt, wie Füllungen, die mit diesem [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) gezeichnet werden, gekachelt werden. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Initialisiert eine neue Instanz der `PathMulticolorGradientBrush`-Klasse mit dem angegebenen Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der `GraphicsPath`, der den von diesem `PathMulticolorGradientBrush` gefüllten Bereich definiert. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Liest oder setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Verlauf definiert.

Wert: Ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Verlauf definiert.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Liest oder setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Verlauf definiert.

Wert: Ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Verlauf definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) |  |

