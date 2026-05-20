---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt einen Brush dar, der einen linearen Farbverlauf mit mehreren Farben und entsprechenden Positionen definiert."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Stellt einen `Brush` mit einem linearen Farbverlauf dar, der durch mehrere Farben und entsprechende Positionen definiert ist. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`‑Klasse mit Standardparametern. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Ruft ein `com.aspose.imaging.ColorBlend` ab, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Farbverlauf definiert. |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse mit Standardparametern. Die Startfarbe ist Schwarz, die Endfarbe ist Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Eine `Aspose.Imaging.Point`-Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [Point](../../com.aspose.imaging/point) | Eine `Aspose.Imaging.Point`-Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Eine `Aspose.Imaging.PointF`-Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Eine `Aspose.Imaging.PointF`-Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Eine `Aspose.Imaging.RectangleF`-Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Eine `Aspose.Imaging.RectangleF`-Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Eine `Aspose.Imaging.RectangleF`-Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | boolean | Wenn auf `true` gesetzt, wird der Winkel während Transformationen mit diesem `LinearMulticolorGradientBrush` geändert. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der `LinearMulticolorGradientBrush`-Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Eine `Aspose.Imaging.RectangleF`-Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | boolean | Wenn auf `true` gesetzt, wird der Winkel während Transformationen mit diesem `LinearMulticolorGradientBrush` geändert. |

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

