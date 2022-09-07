---
title: PathMulticolorGradientBrush
second_title: Aspose.Imaging för .NET API-referens
description: Kapslar in enBrush../aspose.imaging/brush objekt med en gradient. Denna klass kan inte ärvas.
type: docs
weight: 200
url: /sv/net/aspose.imaging.brushes/pathmulticolorgradientbrush/
---
## PathMulticolorGradientBrush class

Kapslar in en[`Brush`](../../aspose.imaging/brush) objekt med en gradient. Denna klass kan inte ärvas.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor)(GraphicsPath) | Initierar en ny instans av[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) klass med den angivna sökvägen. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_1)(PointF[]) | Initierar en ny instans av[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) klass med de angivna punkterna. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_3)(Point[]) | Initierar en ny instans av[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) klass med de angivna punkterna. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_2)(PointF[], WrapMode) | Initierar en ny instans av[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) klass med de angivna punkterna och lindningsläget. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_4)(Point[], WrapMode) | Initierar en ny instans av[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush) klass med de angivna punkterna och lindningsläget. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Hämtar eller ställer in mittpunkten för banans gradient. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Hämtar eller ställer in fokuspunkten för gradientnedgången. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Får den grafiska vägen som denna pensel byggdes på. |
| [InterpolationColors](../../aspose.imaging.brushes/pathmulticolorgradientbrush/interpolationcolors) { get; set; } | Hämtar eller sätter en[`ColorBlend`](../../aspose.imaging/colorblend) som definierar en linjär flerfärgsgradient. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Får vägpunkterna som denna pensel byggdes på. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Hämtar eller ställer in en kopia[`Matrix`](../../aspose.imaging/matrix) som definierar en lokal geometrisk transformation för detta[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Hämtar eller sätter en[`WrapMode`](../../aspose.imaging/wrapmode) uppräkning som anger lindningsläget för detta[`TransformBrush`](../transformbrush) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Skapar en ny djup klon av strömmen[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Multiplicerar[`Matrix`](../../aspose.imaging/matrix) som representerar den lokala geometriska transformationen av detta[`LinearGradientBrush`](../lineargradientbrush) av den angivna[`Matrix`](../../aspose.imaging/matrix) genom att föregå det angivna[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Multiplicerar[`Matrix`](../../aspose.imaging/matrix) som representerar den lokala geometriska transformationen av detta[`LinearGradientBrush`](../lineargradientbrush) av den angivna[`Matrix`](../../aspose.imaging/matrix) i angiven ordning. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Återställer[`Transform`](../transformbrush/transform) egenskap till identitet. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Roterar den lokala geometriska transformationen med angivet belopp. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med angivet belopp i angiven ordning. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna mängderna. Den här metoden lägger in skalningsmatrisen i transformationen. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna mängderna i angiven ordning. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Se även

* class [PathGradientBrushBase](../pathgradientbrushbase)
* namnutrymme [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
