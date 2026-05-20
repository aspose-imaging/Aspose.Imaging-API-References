---
title: "LinearGradientBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Incapsula un Aspose.Imaging.Brush con una sfumatura lineare."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Incapsula un `Aspose.Imaging.Brush` con una sfumatura lineare. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush()](#LinearGradientBrush--) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) con parametri predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Restituisce un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Imposta un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore. |
| [getLinearColors()](#getLinearColors--) | Ottiene i colori di inizio e fine della sfumatura. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Imposta i colori di inizio e fine della sfumatura. |
| [getStartColor()](#getStartColor--) | Ottiene il colore di inizio della sfumatura. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Imposta il colore di inizio della sfumatura. |
| [getEndColor()](#getEndColor--) | Ottiene il colore di fine della sfumatura. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Imposta il colore di fine della sfumatura. |
| [getBlend()](#getBlend--) | Ottiene un `Aspose.Imaging.Blend` che specifica le posizioni e i fattori che definiscono una caduta personalizzata per la sfumatura. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Imposta un `Aspose.Imaging.Blend` che specifica le posizioni e i fattori che definiscono una caduta personalizzata per la sfumatura. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea una caduta della sfumatura basata su una curva a campana. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea una caduta della sfumatura basata su una curva a campana. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea una sfumatura lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea una sfumatura lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |
| color1 | [Color](../../com.aspose.imaging/color) | Il colore1. |
| color2 | [Color](../../com.aspose.imaging/color) | Il colore2. |
| angle | float | L'angolo. |
| isAngleScalable | boolean | se impostato su `true` [is angle scalable]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| color1 | [Color](../../com.aspose.imaging/color) | Il colore1. |
| color2 | [Color](../../com.aspose.imaging/color) | Il colore2. |
| angle | float | L'angolo. |
| isAngleScalable | boolean | se impostato su `true` [is angle scalable]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |
| color1 | [Color](../../com.aspose.imaging/color) | Il colore1. |
| color2 | [Color](../../com.aspose.imaging/color) | Il colore2. |
| angle | float | L'angolo. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| color1 | [Color](../../com.aspose.imaging/color) | Il colore1. |
| color2 | [Color](../../com.aspose.imaging/color) | Il colore2. |
| angle | float | L'angolo. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Il punto1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Il punto2. |
| color1 | [Color](../../com.aspose.imaging/color) | Il colore1. |
| color2 | [Color](../../com.aspose.imaging/color) | Il colore2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Il punto1. |
| point2 | [Point](../../com.aspose.imaging/point) | Il punto2. |
| color1 | [Color](../../com.aspose.imaging/color) | Il colore1. |
| color2 | [Color](../../com.aspose.imaging/color) | Il colore2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) con parametri predefiniti. Il colore di inizio è nero, il colore di fine è bianco, l'angolo è di 45 gradi e il rettangolo è posizionato in (0,0) con dimensioni (1,1).

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Restituisce un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Imposta un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | Un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Ottiene i colori di inizio e fine della sfumatura.

**Returns:**
com.aspose.imaging.Color[] - Un array di due strutture `Color` che rappresenta i colori di inizio e fine della sfumatura.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Imposta i colori di inizio e fine della sfumatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Un array di due strutture `Color` che rappresenta i colori di inizio e fine della sfumatura. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Ottiene il colore di inizio della sfumatura.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Imposta il colore di inizio della sfumatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Il colore di inizio della sfumatura. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Ottiene il colore di fine della sfumatura.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Imposta il colore di fine della sfumatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Il colore di fine della sfumatura. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Ottiene un `Aspose.Imaging.Blend` che specifica le posizioni e i fattori che definiscono una caduta personalizzata per la sfumatura.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Imposta un `Aspose.Imaging.Blend` che specifica le posizioni e i fattori che definiscono una caduta personalizzata per la sfumatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | Un `Aspose.Imaging.Blend` che rappresenta una caduta personalizzata per il gradiente. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea una caduta della sfumatura basata su una curva a campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il colore iniziale e il colore finale sono mescolati in modo uguale). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea una caduta della sfumatura basata su una curva a campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scala | float | Un valore da 0 a 1 che specifica la rapidità con cui i colori diminuiscono dal `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea una sfumatura lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea una sfumatura lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scala | float | Un valore da 0 a 1 che specifica la rapidità con cui i colori diminuiscono dal colore iniziale al `focus` (colore finale) |

