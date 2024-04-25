---
title: LinearMulticolorGradientBrush
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta aBrush../aspose.imaging/brush con gradiente lineare definito da più colori e posizioni appropriate. Questa classe non può essere ereditata.
type: docs
weight: 170
url: /it/aspose.imaging.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

Rappresenta a[`Brush`](../../aspose.imaging/brush) con gradiente lineare definito da più colori e posizioni appropriate. Questa classe non può essere ereditata.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor)() | Inizializza una nuova istanza di[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) classe con parametri di default. Il colore iniziale è nero, il colore finale è bianco, l'angolo è 45 gradi e il rettangolo si trova in (0,0) con dimensione (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_1)(Point, Point) | Inizializza una nuova istanza di[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) classe con i punti specificati. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_2)(PointF, PointF) | Inizializza una nuova istanza di[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) classe con i punti specificati. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_3)(Rectangle, float) | Inizializza una nuova istanza di[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) classe basata su un rettangolo e un angolo di orientamento. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_5)(RectangleF, float) | Inizializza una nuova istanza di[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) classe basata su un rettangolo e un angolo di orientamento. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_4)(Rectangle, float, bool) | Inizializza una nuova istanza di[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) classe basata su un rettangolo e un angolo di orientamento. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_6)(RectangleF, float, bool) | Inizializza una nuova istanza di[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) classe basata su un rettangolo e un angolo di orientamento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Ottiene o imposta l'angolo del gradiente. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [InterpolationColors](../../aspose.imaging.brushes/linearmulticolorgradientbrush/interpolationcolors) { get; set; } | Ottiene o imposta a[`ColorBlend`](../../aspose.imaging/colorblend) che definisce un gradiente lineare multicolore. |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Ottiene o imposta un valore che indica se[`Angle`](../lineargradientbrushbase/angle) viene modificato durante le trasformazioni con questo[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio, impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà è stata introdotta per la compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Ottiene o imposta una regione rettangolare che definisce i punti di inizio e fine del gradiente. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Ottiene o imposta una copia[`Matrix`](../../aspose.imaging/matrix) che definisce una trasformata geometrica locale per questo[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Ottiene o imposta a[`WrapMode`](../../aspose.imaging/wrapmode) enumerazione che indica la modalità di avvolgimento per questo[`TransformBrush`](../transformbrush) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Crea un nuovo clone profondo della corrente[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Moltiplica il[`Matrix`](../../aspose.imaging/matrix) che rappresenta la trasformata geometrica locale di questo[`LinearGradientBrush`](../lineargradientbrush) dal specificato[`Matrix`](../../aspose.imaging/matrix) anteponendo quello specificato[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Moltiplica il[`Matrix`](../../aspose.imaging/matrix) che rappresenta la trasformata geometrica locale di questo[`LinearGradientBrush`](../lineargradientbrush) dal specificato[`Matrix`](../../aspose.imaging/matrix) nell'ordine specificato. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Reimposta il[`Transform`](../transformbrush/transform) proprietà su identità. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Ridimensiona la trasformazione geometrica locale degli importi specificati. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale degli importi specificati nell'ordine specificato. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Converte la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Converte la trasformazione geometrica locale in base alle dimensioni specificate nell'ordine specificato. |

### Guarda anche

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* spazio dei nomi [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
