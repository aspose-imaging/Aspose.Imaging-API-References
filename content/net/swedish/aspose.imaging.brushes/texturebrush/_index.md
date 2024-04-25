---
title: TextureBrush
second_title: Aspose.Imaging för .NET API-referens
description: Varje egenskap iTextureBrush./texturebrush klass är enBrush../aspose.imaging/brush objekt som använder en bild för att fylla det inre av en form. Denna klass kan inte ärvas.
type: docs
weight: 220
url: /sv/aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

Varje egenskap i[`TextureBrush`](../texturebrush) klass är en[`Brush`](../../aspose.imaging/brush) objekt som använder en bild för att fylla det inre av en form. Denna klass kan inte ärvas.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden och avgränsande rektangel. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden och avgränsande rektangel. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden och radbrytningsläget. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden, begränsningsrektangeln och bildattributen. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden, begränsningsrektangeln och bildattributen. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden, radbrytningsläge och avgränsande rektangel. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Initierar en ny instans av[`TextureBrush`](../texturebrush) klass som använder den angivna bilden, radbrytningsläge och avgränsande rektangel. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [Image](../../aspose.imaging.brushes/texturebrush/image) { get; } | Får[`Image`](../../aspose.imaging/image) objekt associerat med detta[`TextureBrush`](../texturebrush) objekt. |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes) { get; } | Får[`ImageAttributes`](./imageattributes) i samband med detta[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle) { get; } | Får[`Rectangle`](../../aspose.imaging/rectangle) i samband med detta[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
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

* class [TransformBrush](../transformbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
