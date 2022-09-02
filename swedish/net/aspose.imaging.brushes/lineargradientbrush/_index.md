---
title: LinearGradientBrush
second_title: Aspose.Imaging för .NET API-referens
description: Kapslar in enBrush../aspose.imaging/brush med en linjär gradient. Denna klass kan inte ärvas.
type: docs
weight: 150
url: /sv/net/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Kapslar in en[`Brush`](../../aspose.imaging/brush) med en linjär gradient. Denna klass kan inte ärvas.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | Initierar en ny instans av[`LinearGradientBrush`](../lineargradientbrush) klass med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1). |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | Initierar en ny instans av[`LinearGradientBrush`](../lineargradientbrush) klass med de angivna punkterna och färgerna. |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | Initierar en ny instans av[`LinearGradientBrush`](../lineargradientbrush) klass med de angivna punkterna och färgerna. |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | Initierar en ny instans av[`LinearGradientBrush`](../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | Initierar en ny instans av[`LinearGradientBrush`](../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | Initierar en ny instans av[`LinearGradientBrush`](../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | Initierar en ny instans av[`LinearGradientBrush`](../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Hämtar eller ställer in gradientvinkeln. |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend) { get; set; } | Hämtar eller sätter en[`Blend`](../../aspose.imaging/blend) som anger positioner och faktorer som definierar en anpassad falloff för gradienten. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor) { get; set; } | Hämtar eller ställer in slutgradientfärgen. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Hämtar eller ställer in ett värde som indikerar om gammakorrigering är aktiverad för detta[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Hämtar eller ställer in ett värde som anger om[`Angle`](../lineargradientbrushbase/angle) ändras vid omvandlingar med detta[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Hämtar eller ställer in ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor) { get; set; } | Hämtar eller ställer in startgradientfärgen. |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Skapar en linjär gradient med en mittfärg och en linjär nedgång till en enda färg i båda ändar. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Skapar en linjär gradient med en mittfärg och en linjär nedgång till en enda färg i båda ändar. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | Skapar en gradientnedgång baserat på en klockformad kurva. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Skapar en gradientnedgång baserat på en klockformad kurva. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Se även

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* namnutrymme [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
