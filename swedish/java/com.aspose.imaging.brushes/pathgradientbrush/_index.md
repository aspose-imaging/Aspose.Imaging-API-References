---
title: "PathGradientBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "Inkapslar ett Aspose.Imaging.Brush-objekt med en gradient."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Inkapslar ett `Aspose.Imaging.Brush`-objekt med en gradient. Denna klass kan inte ärvas.

Centrumfärgen är vit som standard. En användare kan ändra detta värde när som helst senare.

Arrayen med omgivningsfärger initieras med ett enda element som innehåller vit färg som standard. Omgivningsfärgerna kan ändras senare, men minst ett element krävs när omgivningsfärgerna ställs in.

Se `Blend` för mer detaljer om dess initiering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna och omslagsläget. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna och omslagsläget. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Initierar en ny instans av klassen `PathGradientBrush` med den angivna banan. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Ställer in en `com.aspose.imaging.ColorBlend` som definierar en flerfärgad linjär gradient. |
| [getCenterColor()](#getCenterColor--) | Hämtar färgen i centrum av banans gradient. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Ställer in färgen i centrum av banans gradient. |
| [getSurroundColors()](#getSurroundColors--) | Hämtar en array av färger som motsvarar punkterna i den bana som detta `PathGradientBrush` fyller. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | Ställer in en array av färger som motsvarar punkterna i den bana som detta `PathGradientBrush` fyller. |
| [getBlend()](#getBlend--) | Hämtar en `Aspose.Imaging.Blend` som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Ställer in en `Aspose.Imaging.Blend` som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Skapar en gradientpensel som ändrar färg från banans centrum utåt till banans gräns. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Skapar en gradientpensel som ändrar färg från banans centrum utåt till banans gräns. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Skapar en gradient med en centrumfärg och ett linjärt avtagande till en omgivande färg. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Skapar en gradient med en centrumfärg och ett linjärt avtagande till varje omgivande färg. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | En array av `Aspose.Imaging.PointF`-strukturer som representerar de punkter som utgör banans hörn. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | En array av `Aspose.Imaging.PointF`-strukturer som representerar de punkter som utgör banans hörn. |
| wrapMode | int | En `Aspose.Imaging.WrapMode` som specificerar hur fyllningar ritade med detta `PathGradientBrush` upprepas. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | En array av `Aspose.Imaging.Point`-strukturer som representerar de punkter som utgör banans hörn. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | En array av `Aspose.Imaging.Point`-strukturer som representerar de punkter som utgör banans hörn. |
| wrapMode | int | En `Aspose.Imaging.WrapMode` som specificerar hur fyllningar ritade med detta `PathGradientBrush` upprepas. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initierar en ny instans av klassen `PathGradientBrush` med den angivna banan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` som definierar området som fylls av detta `PathGradientBrush`. |

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

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Hämtar färgen i centrum av banans gradient.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Ställer in färgen i centrum av banans gradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | En `com.aspose.imaging.Color` som representerar färgen i centrum av banans gradient. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Hämtar en array av färger som motsvarar punkterna i den bana som detta `PathGradientBrush` fyller.

**Returns:**
com.aspose.imaging.Color[] - En array av `com.aspose.imaging.Color`-strukturer som representerar färgerna som är associerade med varje punkt i den bana som detta `PathGradientBrush` fyller.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


Ställer in en array av färger som motsvarar punkterna i den bana som detta `PathGradientBrush` fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | En array av `com.aspose.imaging.Color`-strukturer som representerar färgerna som är associerade med varje punkt i den bana som detta `PathGradientBrush` fyller. |

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


Skapar en gradientpensel som ändrar färg från banans centrum utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Skapar en gradientpensel som ändrar färg från banans centrum utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |
| skala | float | Ett värde mellan 0 och 1 som specificerar den maximala intensiteten för centrumfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för centrumfärgen, och det är standardvärdet. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Skapar en gradient med en centrumfärg och ett linjärt avtagande till en omgivande färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Skapar en gradient med en centrumfärg och ett linjärt avtagande till varje omgivande färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar var, längs någon radie från banans centrum till banans gräns, centrumfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans centrum. |
| skala | float | Ett värde mellan 0 och 1 som specificerar den maximala intensiteten för centrumfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för centrumfärgen, och det är standardvärdet. |

