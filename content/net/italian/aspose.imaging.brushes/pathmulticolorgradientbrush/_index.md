---
title: PathMulticolorGradientBrush
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Incapsula aBrush../aspose.imaging/brush oggetto con una sfumatura. Questa classe non può essere ereditata.
type: docs
weight: 200
url: /it/aspose.imaging.brushes/pathmulticolorgradientbrush/
---
## PathMulticolorGradientBrush class

Incapsula a[`Brush`](../../aspose.imaging/brush) oggetto con una sfumatura. Questa classe non può essere ereditata.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor)(GraphicsPath) | Inizializza una nuova istanza di[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) classe con il percorso specificato. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_1)(PointF[]) | Inizializza una nuova istanza di[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) classe con i punti specificati. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_3)(Point[]) | Inizializza una nuova istanza di[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) classe con i punti specificati. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_2)(PointF[], WrapMode) | Inizializza una nuova istanza di[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) classe con i punti specificati e la modalità di avvolgimento. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_4)(Point[], WrapMode) | Inizializza una nuova istanza di[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) classe con i punti specificati e la modalità di avvolgimento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Ottiene o imposta il punto centrale del gradiente del percorso. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Ottiene o imposta il punto focale per la diminuzione del gradiente. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Ottiene il percorso grafico su cui è stato creato questo pennello. |
| [InterpolationColors](../../aspose.imaging.brushes/pathmulticolorgradientbrush/interpolationcolors) { get; set; } | Ottiene o imposta a[`ColorBlend`](../../aspose.imaging/colorblend) che definisce un gradiente lineare multicolore. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio, impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà è stata introdotta per la compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Ottiene i punti del percorso su cui è stato creato questo pennello. |
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

* class [PathGradientBrushBase](../pathgradientbrushbase)
* spazio dei nomi [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
