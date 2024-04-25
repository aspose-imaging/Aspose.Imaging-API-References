---
title: LinearMulticolorGradientBrush
second_title: Aspose.Imaging för .NET API-referens
description: Representerar enBrush../aspose.imaging/brush med linjär gradient definierad av flera färger och lämpliga positioner. Denna klass kan inte ärvas.
type: docs
weight: 170
url: /sv/aspose.imaging.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

Representerar en[`Brush`](../../aspose.imaging/brush) med linjär gradient definierad av flera färger och lämpliga positioner. Denna klass kan inte ärvas.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor)() | Initierar en ny instans av[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) klass med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_1)(Point, Point) | Initierar en ny instans av[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) klass med de angivna punkterna. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_2)(PointF, PointF) | Initierar en ny instans av[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) klass med de angivna punkterna. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_3)(Rectangle, float) | Initierar en ny instans av[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) klass baserad på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_5)(RectangleF, float) | Initierar en ny instans av[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) klass baserad på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_4)(Rectangle, float, bool) | Initierar en ny instans av[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) klass baserad på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_6)(RectangleF, float, bool) | Initierar en ny instans av[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) klass baserad på en rektangel och en orienteringsvinkel. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Hämtar eller ställer in gradientvinkeln. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Hämtar eller ställer in ett värde som indikerar om gammakorrigering är aktiverad för detta[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [InterpolationColors](../../aspose.imaging.brushes/linearmulticolorgradientbrush/interpolationcolors) { get; set; } | Hämtar eller sätter en[`ColorBlend`](../../aspose.imaging/colorblend) som definierar en linjär flerfärgsgradient. |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Hämtar eller ställer in ett värde som anger om[`Angle`](../lineargradientbrushbase/angle) ändras vid omvandlingar med detta[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Hämtar eller ställer in ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
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

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* namnutrymme [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
