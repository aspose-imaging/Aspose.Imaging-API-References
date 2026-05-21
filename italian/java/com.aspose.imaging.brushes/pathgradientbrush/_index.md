---
title: "PathGradientBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Incapsula un oggetto Aspose.Imaging.Brush con un gradiente."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Incapsula un oggetto `Aspose.Imaging.Brush` con un gradiente. Questa classe non può essere ereditata.

Il colore centrale è bianco per impostazione predefinita. Un utente può modificare questo valore in qualsiasi momento successivo.

L'array dei colori di contorno è inizializzato con un singolo elemento contenente il colore bianco per impostazione predefinita. I colori di contorno possono essere modificati in seguito, tuttavia è necessario almeno un elemento singolo quando si impostano i colori di contorno.

Vedi il `Blend` per maggiori dettagli sulla sua inizializzazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati e la modalità di avvolgimento. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati e la modalità di avvolgimento. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Inizializza una nuova istanza della classe `PathGradientBrush` con il percorso specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Restituisce un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Imposta un `com.aspose.imaging.ColorBlend` che definisce un gradiente lineare multicolore. |
| [getCenterColor()](#getCenterColor--) | Ottiene il colore al centro del gradiente del percorso. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Imposta il colore al centro del gradiente del percorso. |
| [getSurroundColors()](#getSurroundColors--) | Ottiene un array di colori che corrispondono ai punti nel percorso che questo `PathGradientBrush` riempie. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | Imposta un array di colori che corrispondono ai punti nel percorso che questo `PathGradientBrush` riempie. |
| [getBlend()](#getBlend--) | Ottiene un `Aspose.Imaging.Blend` che specifica le posizioni e i fattori che definiscono una caduta personalizzata per la sfumatura. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Imposta un `Aspose.Imaging.Blend` che specifica le posizioni e i fattori che definiscono una caduta personalizzata per la sfumatura. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un gradiente con un colore centrale e una diminuzione lineare verso un colore di contorno. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un gradiente con un colore centrale e una diminuzione lineare verso ciascun colore di contorno. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Un array di strutture `Aspose.Imaging.PointF` che rappresenta i punti che costituiscono i vertici del percorso. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Un array di strutture `Aspose.Imaging.PointF` che rappresenta i punti che costituiscono i vertici del percorso. |
| wrapMode | int | Un `Aspose.Imaging.WrapMode` che specifica come vengono ripetuti i riempimenti disegnati con questo `PathGradientBrush`. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Un array di strutture `Aspose.Imaging.Point` che rappresenta i punti che costituiscono i vertici del percorso. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Inizializza una nuova istanza della classe `PathGradientBrush` con i punti specificati e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Un array di strutture `Aspose.Imaging.Point` che rappresenta i punti che costituiscono i vertici del percorso. |
| wrapMode | int | Un `Aspose.Imaging.WrapMode` che specifica come vengono ripetuti i riempimenti disegnati con questo `PathGradientBrush`. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Inizializza una nuova istanza della classe `PathGradientBrush` con il percorso specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `GraphicsPath` che definisce l'area riempita da questo `PathGradientBrush`. |

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

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Ottiene il colore al centro del gradiente del percorso.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Imposta il colore al centro del gradiente del percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Un `com.aspose.imaging.Color` che rappresenta il colore al centro del gradiente del percorso. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Ottiene un array di colori che corrispondono ai punti nel percorso che questo `PathGradientBrush` riempie.

**Returns:**
com.aspose.imaging.Color[] - Un array di strutture `com.aspose.imaging.Color` che rappresenta i colori associati a ciascun punto nel percorso che questo `PathGradientBrush` riempie.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


Imposta un array di colori che corrispondono ai punti nel percorso che questo `PathGradientBrush` riempie.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Un array di strutture `com.aspose.imaging.Color` che rappresenta i colori associati a ciascun punto nel percorso che questo `PathGradientBrush` riempie. |

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


Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (il valore predefinito) posiziona la massima intensità al centro del percorso. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (il valore predefinito) posiziona la massima intensità al centro del percorso. |
| scala | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore del confine. Un valore di 1 produce l'intensità più alta possibile del colore centrale, ed è il valore predefinito. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un gradiente con un colore centrale e una diminuzione lineare verso un colore di contorno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (il valore predefinito) posiziona la massima intensità al centro del percorso. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un gradiente con un colore centrale e una diminuzione lineare verso ciascun colore di contorno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (il valore predefinito) posiziona la massima intensità al centro del percorso. |
| scala | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore del confine. Un valore di 1 produce l'intensità più alta possibile del colore centrale, ed è il valore predefinito. |

