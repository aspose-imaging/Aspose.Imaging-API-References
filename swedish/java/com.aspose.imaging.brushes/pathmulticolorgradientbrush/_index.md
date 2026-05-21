---
title: "PathMulticolorGradientBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "Inkapslar ett Aspose.Imaging.Brush-objekt med en gradient."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.brushes/pathmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Inkapslar ett `Aspose.Imaging.Brush`-objekt med en gradient. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---) | Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna. |
| [PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-) | Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna och wrap‑läget. |
| [PathMulticolorGradientBrush(Point[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---) | Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna. |
| [PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-) | Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna och wrap‑läget. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-) | Initierar en ny instans av klassen `PathMulticolorGradientBrush` med den angivna vägen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar eller anger ett `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Hämtar eller anger ett `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
### PathMulticolorGradientBrush(PointF[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---}
```
public PathMulticolorGradientBrush(PointF[] pathPoints)
```


Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | En matris av [PointF](../../com.aspose.imaging/pointf)-strukturer som representerar de punkter som utgör banans hörn. |

### PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)
```


Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna och wrap‑läget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | En matris av [PointF](../../com.aspose.imaging/pointf)-strukturer som representerar de punkter som utgör banans hörn. |
| wrapMode | int | Ett [WrapMode](../../com.aspose.imaging/wrapmode) som anger hur fyllningar som ritas med denna [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) upprepas. |

### PathMulticolorGradientBrush(Point[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---}
```
public PathMulticolorGradientBrush(Point[] pathPoints)
```


Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | En matris av [Point](../../com.aspose.imaging/point)-strukturer som representerar de punkter som utgör banans hörn. |

### PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-}
```
public PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)
```


Initierar en ny instans av klassen [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) med de angivna punkterna och wrap‑läget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | En matris av [Point](../../com.aspose.imaging/point)-strukturer som representerar de punkter som utgör banans hörn. |
| wrapMode | int | Ett [WrapMode](../../com.aspose.imaging/wrapmode) som anger hur fyllningar som ritas med denna [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) upprepas. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Initierar en ny instans av klassen `PathMulticolorGradientBrush` med den angivna vägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Den `GraphicsPath` som definierar området som fylls av denna `PathMulticolorGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Hämtar eller anger ett `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient.

Värde: Ett `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Hämtar eller anger ett `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient.

Värde: Ett `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) |  |

