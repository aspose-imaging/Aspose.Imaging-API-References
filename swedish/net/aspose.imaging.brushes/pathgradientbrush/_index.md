---
title: PathGradientBrush
second_title: Aspose.Imaging för .NET API-referens
description: Kapslar in enBrush../aspose.imaging/brush objekt med en gradient. Denna klass kan inte ärvas.
type: docs
weight: 180
url: /sv/net/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

Kapslar in en[`Brush`](../../aspose.imaging/brush) objekt med en gradient. Denna klass kan inte ärvas.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | Initierar en ny instans av[`PathGradientBrush`](../pathgradientbrush) klass med den angivna sökvägen. |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | Initierar en ny instans av[`PathGradientBrush`](../pathgradientbrush) klass med de angivna punkterna. |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | Initierar en ny instans av[`PathGradientBrush`](../pathgradientbrush) klass med de angivna punkterna. |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | Initierar en ny instans av[`PathGradientBrush`](../pathgradientbrush) klass med de angivna punkterna och lindningsläget. |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | Initierar en ny instans av[`PathGradientBrush`](../pathgradientbrush) klass med de angivna punkterna och lindningsläget. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | Hämtar eller sätter en[`Blend`](../../aspose.imaging/blend) som anger positioner och faktorer som definierar en anpassad falloff för gradienten. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | Hämtar eller ställer in färgen i mitten av banans gradient. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Hämtar eller ställer in mittpunkten för banans gradient. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Hämtar eller ställer in fokuspunkten för gradientnedgången. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Får den grafiska vägen som denna pensel byggdes på. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Får vägpunkterna som denna pensel byggdes på. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | Hämtar eller ställer in en rad färger som motsvarar punkterna i vägen denna[`PathGradientBrush`](../pathgradientbrush) fyller. |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Skapar en gradient med en mittfärg och en linjär nedgång till en omgivande färg. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Skapar en övertoning med en mittfärg och en linjär nedgång till varje omgivande färg. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | Skapar en övertoningspensel som ändrar färg från mitten av banan utåt till banans gräns. Övergången från en färg till en annan är baserad på en klockformad kurva. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Skapar en övertoningspensel som ändrar färg från mitten av banan utåt till banans gräns. Övergången från en färg till en annan är baserad på en klockformad kurva. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Anmärkningar

Mittfärgen är vit som standard. En användare kan ändra detta värde när som helst senare.

Surroundfärgsarrayen initieras av ett enda element som innehåller vit färg som standard. Surroundfärgerna kan ändras senare, men minst ett enda element krävs när du ställer in surroundfärgerna.

Se den[`Blend`](./blend) för mer information om dess initiering.

### Se även

* class [PathGradientBrushBase](../pathgradientbrushbase)
* namnutrymme [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
