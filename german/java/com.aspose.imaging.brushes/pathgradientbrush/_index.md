---
title: "PathGradientBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Kapselt ein Aspose.Imaging.Brush-Objekt mit einem Verlauf."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Kapselt ein `Aspose.Imaging.Brush`-Objekt mit einem Verlauf. Diese Klasse kann nicht abgeleitet werden.

Die zentrale Farbe ist standardmäßig weiß. Ein Benutzer kann diesen Wert jederzeit später ändern.

Das Array der Umgebungsfarben wird standardmäßig mit einem einzelnen Element, das die weiße Farbe enthält, initialisiert. Die Umgebungsfarben können später geändert werden, jedoch ist mindestens ein einzelnes Element erforderlich, wenn die Umgebungsfarben festgelegt werden.

Siehe `Blend` für weitere Details zur Initialisierung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten und dem Wrap‑Modus. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten und dem Wrap‑Modus. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit dem angegebenen Pfad. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Ruft ein `com.aspose.imaging.ColorBlend` ab, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Setzt ein `com.aspose.imaging.ColorBlend`, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [getCenterColor()](#getCenterColor--) | Ermittelt die Farbe im Zentrum des Pfadverlaufs. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Legt die Farbe im Zentrum des Pfadverlaufs fest. |
| [getSurroundColors()](#getSurroundColors--) | Ermittelt ein Array von Farben, das den Punkten im Pfad entspricht, den dieser `PathGradientBrush` füllt. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | Legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser `PathGradientBrush` füllt. |
| [getBlend()](#getBlend--) | Liefert ein `Aspose.Imaging.Blend`, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Setzt ein `Aspose.Imaging.Blend`, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadrand ändert. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadrand ändert. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Erstellt einen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu einer umgebenden Farbe. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Erstellt einen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu jeder umgebenden Farbe. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von `Aspose.Imaging.PointF`‑Strukturen, das die Punkte darstellt, aus denen die Eckpunkte des Pfads bestehen. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten und dem Wrap‑Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von `Aspose.Imaging.PointF`‑Strukturen, das die Punkte darstellt, aus denen die Eckpunkte des Pfads bestehen. |
| wrapMode | int | Ein `Aspose.Imaging.WrapMode`, das angibt, wie mit diesem `PathGradientBrush` gezeichnete Füllungen gekachelt werden. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Ein Array von `Aspose.Imaging.Point`‑Strukturen, das die Punkte darstellt, aus denen die Eckpunkte des Pfads bestehen. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit den angegebenen Punkten und dem Wrap‑Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Ein Array von `Aspose.Imaging.Point`‑Strukturen, das die Punkte darstellt, aus denen die Eckpunkte des Pfads bestehen. |
| wrapMode | int | Ein `Aspose.Imaging.WrapMode`, das angibt, wie mit diesem `PathGradientBrush` gezeichnete Füllungen gekachelt werden. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initialisiert eine neue Instanz der Klasse `PathGradientBrush` mit dem angegebenen Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der `GraphicsPath`, der den von diesem `PathGradientBrush` gefüllten Bereich definiert. |

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

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Ermittelt die Farbe im Zentrum des Pfadverlaufs.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Legt die Farbe im Zentrum des Pfadverlaufs fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Ein `com.aspose.imaging.Color`, der die Farbe im Zentrum des Pfadverlaufs darstellt. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Ermittelt ein Array von Farben, das den Punkten im Pfad entspricht, den dieser `PathGradientBrush` füllt.

**Returns:**
com.aspose.imaging.Color[] – Ein Array von `com.aspose.imaging.Color`‑Strukturen, das die Farben darstellt, die jedem Punkt im Pfad zugeordnet sind, den dieser `PathGradientBrush` füllt.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


Legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser `PathGradientBrush` füllt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Ein Array von `com.aspose.imaging.Color`‑Strukturen, das die Farben darstellt, die jedem Punkt im Pfad zugeordnet sind, den dieser `PathGradientBrush` füllt. |

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


Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittel­farbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittel­farbe und ist der Standardwert. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Erstellt einen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu einer umgebenden Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Erstellt einen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu jeder umgebenden Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zum Pfadrand die Mittel­farbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittel­farbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittel­farbe und ist der Standardwert. |

