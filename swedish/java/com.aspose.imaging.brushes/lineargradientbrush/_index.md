---
title: "LinearGradientBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "Inkapslar en Aspose.Imaging.Brush med en linjär gradient."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Inkapslar en `Aspose.Imaging.Brush` med en linjär gradient. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) med standardparametrar. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Ställer in en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
| [getLinearColors()](#getLinearColors--) | Hämtar start- och slutfärgerna för gradienten. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Ställer in start- och slutfärgerna för gradienten. |
| [getStartColor()](#getStartColor--) | Hämtar startgradientfärgen. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Ställer in startgradientfärgen. |
| [getEndColor()](#getEndColor--) | Hämtar slutgradientfärgen. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Ställer in slutgradientfärgen. |
| [getBlend()](#getBlend--) | Hämtar en `Aspose.Imaging.Blend` som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Ställer in en `Aspose.Imaging.Blend` som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |
| color1 | [Color](../../com.aspose.imaging/color) | Färgen1. |
| color2 | [Color](../../com.aspose.imaging/color) | Färgen2. |
| angle | float | vinkeln. |
| isAngleScalable | boolean | om satt till `true` [är vinkel skalbar]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| color1 | [Color](../../com.aspose.imaging/color) | Färgen1. |
| color2 | [Color](../../com.aspose.imaging/color) | Färgen2. |
| angle | float | vinkeln. |
| isAngleScalable | boolean | om satt till `true` [är vinkel skalbar]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |
| color1 | [Color](../../com.aspose.imaging/color) | Färgen1. |
| color2 | [Color](../../com.aspose.imaging/color) | Färgen2. |
| angle | float | vinkeln. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| color1 | [Color](../../com.aspose.imaging/color) | Färgen1. |
| color2 | [Color](../../com.aspose.imaging/color) | Färgen2. |
| angle | float | vinkeln. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Punkt1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Punkt2. |
| color1 | [Color](../../com.aspose.imaging/color) | Färgen1. |
| color2 | [Color](../../com.aspose.imaging/color) | Färgen2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Punkt1. |
| point2 | [Point](../../com.aspose.imaging/point) | Punkt2. |
| color1 | [Color](../../com.aspose.imaging/color) | Färgen1. |
| color2 | [Color](../../com.aspose.imaging/color) | Färgen2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initierar en ny instans av klassen [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1).

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

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Hämtar start- och slutfärgerna för gradienten.

**Returns:**
com.aspose.imaging.Color[] - En array av två `Color`-strukturer som representerar start- och slutfärgerna för gradienten.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Ställer in start- och slutfärgerna för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | En array av två `Color`-strukturer som representerar start- och slutfärgerna för gradienten. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Hämtar startgradientfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Ställer in startgradientfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Startgradientfärgen. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Hämtar slutgradientfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Ställer in slutgradientfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Slutgradientfärgen. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Hämtar en `Aspose.Imaging.Blend` som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Ställer in en `Aspose.Imaging.Blend` som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | En `Aspose.Imaging.Blend` som representerar ett anpassat avtagande för gradienten. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar centrum för gradienten (punkten där startfärgen och slutfärgen blandas lika). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar centrum för gradienten (punkten där gradienten endast består av slutfärgen). |
| skala | float | Ett värde från 0 till 1 som anger hur snabbt färgerna avtar från `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar centrum för gradienten (punkten där gradienten endast består av slutfärgen). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar centrum för gradienten (punkten där gradienten endast består av slutfärgen). |
| skala | float | Ett värde från 0 till 1 som anger hur snabbt färgerna avtar från startfärgen till `focus` (slutfärg). |

