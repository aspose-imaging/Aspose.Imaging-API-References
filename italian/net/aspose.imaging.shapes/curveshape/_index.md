---
title: CurveShape
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta una forma spline curva.
type: docs
weight: 10970
url: /it/net/aspose.imaging.shapes/curveshape/
---
## CurveShape class

Rappresenta una forma spline curva.

```csharp
public sealed class CurveShape : PolygonShape
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CurveShape](curveshape#constructor)() | Inizializza una nuova istanza di[`CurveShape`](../curveshape) classe. |
| [CurveShape](curveshape#constructor_1)(PointF[]) | Inizializza una nuova istanza di[`CurveShape`](../curveshape) classe. Viene utilizzata la tensione predefinita di 0,5. |
| [CurveShape](curveshape#constructor_2)(PointF[], bool) | Inizializza una nuova istanza di[`CurveShape`](../curveshape) classe. Viene utilizzata la tensione predefinita di 0,5. |
| [CurveShape](curveshape#constructor_3)(PointF[], float) | Inizializza una nuova istanza di[`CurveShape`](../curveshape) classe. |
| [CurveShape](curveshape#constructor_4)(PointF[], float, bool) | Inizializza una nuova istanza di[`CurveShape`](../curveshape) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/curveshape/bounds) { get; } | Ottiene i limiti dell'oggetto. |
| override [Center](../../aspose.imaging.shapes/curveshape/center) { get; } | Ottiene il centro della forma. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint) { get; } | Ottiene il punto forma finale. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments) { get; } | Ottiene un valore che indica se la forma ha segmenti. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed) { get; set; } | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [Points](../../aspose.imaging.shapes/polygonshape/points) { get; set; } | Ottiene o imposta i punti della curva. |
| override [Segments](../../aspose.imaging.shapes/curveshape/segments) { get; } | Ottiene i segmenti della forma. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint) { get; } | Ottiene il punto della forma iniziale. |
| [Tension](../../aspose.imaging.shapes/curveshape/tension) { get; set; } | Ottiene o imposta la tensione della curva. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse)() | Inverte l'ordine dei punti per questa forma. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform)(Matrix) | Applica la trasformazione specificata alla forma. |

### Guarda anche

* class [PolygonShape](../polygonshape)
* spazio dei nomi [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
