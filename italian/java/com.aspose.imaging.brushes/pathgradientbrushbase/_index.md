---
title: "PathGradientBrushBase"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un Brush con funzionalità di gradiente di percorso di base."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Rappresenta un `Brush` con funzionalità di gradiente del percorso di base.

Nota che quando si crea la classe `PathGradientBrushBase` dovrebbe essere inizializzata con almeno 2 punti. Il percorso interno creato sarà sempre una figura chiusa, l'ultimo punto collega il primo punto. Tale forma è riempita con questo `PathGradientBrushBase`. L'implementazione GDI+ genera un `OutOfMemoryError` quando si passano array vuoti o punti con le stesse coordinate. Il `PathGradientBrushBase` genera un'eccezione quando l'array di punti contiene meno di 2 punti, l'`ArgumentException` viene lanciata invece di `OutOfMemoryError` quando l'array di punti è inaccettabile. Il punto centrale è calcolato come centro di massa dei punti forniti per impostazione predefinita. Un utente può modificare questo punto in seguito. La scala di messa a fuoco è un punto vuoto (0.0, 0.0) per impostazione predefinita.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Restituisce i punti del percorso su cui è stato costruito questo brush. |
| [getGraphicsPath()](#getGraphicsPath--) | Restituisce il percorso grafico su cui è stato costruito questo brush. |
| [getCenterPoint()](#getCenterPoint--) | Ottiene o imposta il punto centrale del gradiente di percorso. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Ottiene o imposta il punto centrale del gradiente di percorso. |
| [getFocusScales()](#getFocusScales--) | Restituisce il punto di messa a fuoco per la caduta del gradiente. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Ottiene o imposta il punto di messa a fuoco per la caduta del gradiente. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Restituisce i punti del percorso su cui è stato costruito questo brush.

**Returns:**
com.aspose.imaging.PointF[] - I punti del percorso.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Restituisce il percorso grafico su cui è stato costruito questo brush.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Ottiene o imposta il punto centrale del gradiente di percorso.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Ottiene o imposta il punto centrale del gradiente di percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Una `Aspose.Imaging.PointF` che rappresenta il punto centrale del gradiente di percorso. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Restituisce il punto di messa a fuoco per la caduta del gradiente.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Ottiene o imposta il punto di messa a fuoco per la caduta del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Un `Aspose.Imaging.PointF` che rappresenta il punto focale per la diminuzione del gradiente. |

