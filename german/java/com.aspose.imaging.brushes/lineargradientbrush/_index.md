---
title: "LinearGradientBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Kapselt einen Aspose.Imaging.Brush mit einem linearen Farbverlauf."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Kapselt einen `Aspose.Imaging.Brush` mit einem linearen Farbverlauf. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse. |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse mit Standardparametern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Ruft ein `com.aspose.imaging.ColorBlend` ab, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [getLinearColors()](#getLinearColors--) | Liefert die Anfangs- und Endfarben des Farbverlaufs. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Setzt die Anfangs- und Endfarben des Farbverlaufs. |
| [getStartColor()](#getStartColor--) | Liefert die Anfangsfarbe des Farbverlaufs. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Setzt die Anfangsfarbe des Farbverlaufs. |
| [getEndColor()](#getEndColor--) | Liefert die Endfarbe des Farbverlaufs. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Setzt die Endfarbe des Farbverlaufs. |
| [getBlend()](#getBlend--) | Liefert ein `Aspose.Imaging.Blend`, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Setzt ein `Aspose.Imaging.Blend`, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Erstellt einen Farbverlaufsabfall basierend auf einer glockenförmigen Kurve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Erstellt einen Farbverlaufsabfall basierend auf einer glockenförmigen Kurve. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck. |
| color1 | [Color](../../com.aspose.imaging/color) | Die Farbe1. |
| color2 | [Color](../../com.aspose.imaging/color) | Die Farbe2. |
| angle | float | Der Winkel. |
| isAngleScalable | boolean | wenn auf `true` gesetzt, [ist Winkel skalierbar]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |
| color1 | [Color](../../com.aspose.imaging/color) | Die Farbe1. |
| color2 | [Color](../../com.aspose.imaging/color) | Die Farbe2. |
| angle | float | Der Winkel. |
| isAngleScalable | boolean | wenn auf `true` gesetzt, [ist Winkel skalierbar]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck. |
| color1 | [Color](../../com.aspose.imaging/color) | Die Farbe1. |
| color2 | [Color](../../com.aspose.imaging/color) | Die Farbe2. |
| angle | float | Der Winkel. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |
| color1 | [Color](../../com.aspose.imaging/color) | Die Farbe1. |
| color2 | [Color](../../com.aspose.imaging/color) | Die Farbe2. |
| angle | float | Der Winkel. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Der Punkt1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Der Punkt2. |
| color1 | [Color](../../com.aspose.imaging/color) | Die Farbe1. |
| color2 | [Color](../../com.aspose.imaging/color) | Die Farbe2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Der Punkt1. |
| point2 | [Point](../../com.aspose.imaging/point) | Der Punkt2. |
| color1 | [Color](../../com.aspose.imaging/color) | Die Farbe1. |
| color2 | [Color](../../com.aspose.imaging/color) | Die Farbe2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initialisiert eine neue Instanz der [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush)-Klasse mit Standardparametern. Die Anfangsfarbe ist schwarz, die Endfarbe ist weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1).

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Ruft ein `com.aspose.imaging.ColorBlend` ab, das einen mehrfarbigen linearen Farbverlauf definiert.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Farbverlauf definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | Ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Farbverlauf definiert. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Liefert die Anfangs- und Endfarben des Farbverlaufs.

**Returns:**
com.aspose.imaging.Color[] - Ein Array von zwei `Color`-Strukturen, das die Anfangs- und Endfarben des Farbverlaufs darstellt.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Setzt die Anfangs- und Endfarben des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Ein Array von zwei `Color`-Strukturen, das die Anfangs- und Endfarben des Farbverlaufs darstellt. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Liefert die Anfangsfarbe des Farbverlaufs.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Setzt die Anfangsfarbe des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Die Anfangsfarbe des Farbverlaufs. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Liefert die Endfarbe des Farbverlaufs.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Setzt die Endfarbe des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Die Endfarbe des Farbverlaufs. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Liefert ein `Aspose.Imaging.Blend`, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Setzt ein `Aspose.Imaging.Blend`, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | Ein `Aspose.Imaging.Blend`, das einen benutzerdefinierten Falloff für den Farbverlauf darstellt. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Erstellt einen Farbverlaufsabfall basierend auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem die Ausgangsfarbe und die Endfarbe zu gleichen Teilen gemischt werden). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Erstellt einen Farbverlaufsabfall basierend auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben vom `focus` abfallen. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben von der Ausgangsfarbe zum `focus` (Endfarbe) abfallen. |

