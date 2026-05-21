---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en Brush med linjär gradient definierad av flera färger och lämpliga positioner."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Representerar en `Brush` med linjär gradient definierad av flera färger och lämpliga positioner. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` med standardparametrar. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen med de angivna punkterna. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen med de angivna punkterna. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Ställer in en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | En `Aspose.Imaging.Point`-struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [Point](../../com.aspose.imaging/point) | En `Aspose.Imaging.Point`-struktur som representerar slutpunkten för den linjära gradienten. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | En `Aspose.Imaging.PointF`-struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | En `Aspose.Imaging.PointF`-struktur som representerar slutpunkten för den linjära gradienten. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | En `Aspose.Imaging.RectangleF`-struktur som specificerar gränserna för den linjära gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | En `Aspose.Imaging.RectangleF`-struktur som specificerar gränserna för den linjära gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | En `Aspose.Imaging.RectangleF`-struktur som specificerar gränserna för den linjära gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScalable | boolean | om den är satt till `true` ändras vinkeln under transformationer med detta `LinearMulticolorGradientBrush`. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Initierar en ny instans av `LinearMulticolorGradientBrush`-klassen baserad på en rektangel och en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | En `Aspose.Imaging.RectangleF`-struktur som specificerar gränserna för den linjära gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScalable | boolean | om den är satt till `true` ändras vinkeln under transformationer med detta `LinearMulticolorGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Hämtar en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Ställer in en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | En `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |

