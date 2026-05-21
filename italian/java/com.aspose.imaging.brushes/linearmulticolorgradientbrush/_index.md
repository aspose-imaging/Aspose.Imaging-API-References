---
title: "LinearMulticolorGradientBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un Brush con gradiente lineare definito da più colori e posizioni appropriate."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Rappresenta un `Brush` con gradiente lineare definito da più colori e posizioni appropriate. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` con parametri predefiniti. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` con i punti specificati. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` con i punti specificati. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Restituisce un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Imposta un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore. |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` con i parametri predefiniti. Il colore iniziale è nero, il colore finale è bianco, l'angolo è 45 gradi e il rettangolo si trova in (0,0) con dimensioni (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Una struttura `Aspose.Imaging.Point` che rappresenta il punto iniziale del gradiente lineare. |
| point2 | [Point](../../com.aspose.imaging/point) | Una struttura `Aspose.Imaging.Point` che rappresenta il punto finale del gradiente lineare. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Una struttura `Aspose.Imaging.PointF` che rappresenta il punto iniziale del gradiente lineare. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Una struttura `Aspose.Imaging.PointF` che rappresenta il punto finale del gradiente lineare. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una struttura `Aspose.Imaging.RectangleF` che specifica i limiti del gradiente lineare. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una struttura `Aspose.Imaging.RectangleF` che specifica i limiti del gradiente lineare. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una struttura `Aspose.Imaging.RectangleF` che specifica i limiti del gradiente lineare. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScalable | boolean | se impostato su `true` l'angolo viene modificato durante le trasformazioni con questo `LinearMulticolorGradientBrush`. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Inizializza una nuova istanza della classe `LinearMulticolorGradientBrush` basata su un rettangolo e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una struttura `Aspose.Imaging.RectangleF` che specifica i limiti del gradiente lineare. |
| angle | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScalable | boolean | se impostato su `true` l'angolo viene modificato durante le trasformazioni con questo `LinearMulticolorGradientBrush`. |

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

