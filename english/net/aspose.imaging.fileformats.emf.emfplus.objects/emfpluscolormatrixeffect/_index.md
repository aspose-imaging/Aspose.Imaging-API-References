---
title: Class EmfPlusColorMatrixEffect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusColorMatrixEffect class. The ColorMatrixEffect object specifies an affine transform to be applied to an image
type: docs
weight: 5440
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
## EmfPlusColorMatrixEffect class

The ColorMatrixEffect object specifies an affine transform to be applied to an image.

```csharp
public sealed class EmfPlusColorMatrixEffect : EmfPlusImageEffectsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusColorMatrixEffect](emfpluscolormatrixeffect/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrix/) { get; set; } | Gets or sets the matrix. |
| [MatrixN0](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn0/) { get; set; } | Gets or sets the Matrix[N][0] of the 5x5 color matrix. This row is used for transforms. |
| [MatrixN1](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn1/) { get; set; } | Gets or sets the Matrix[N][1] of the 5x5 color matrix. This row is used for transforms. |
| [MatrixN2](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn2/) { get; set; } | Gets or sets the Matrix[N][2] of the 5x5 color matrix. This row is used for transforms. |
| [MatrixN3](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn3/) { get; set; } | Gets or sets the Matrix[N][3] of the 5x5 color matrix. This row is used for transforms. |
| [MatrixN4](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/matrixn4/) { get; set; } | Gets or sets the Matrix[N][4] of the 5x5 color matrix. This row is used for color translations. |

## Remarks

Bitmap images are specified by EmfPlusBitmap objects (section 2.2.2.2). A color matrix effect is performed by multiplying a color vector by a ColorMatrixEffect object. A 5x5 color matrix can perform a linear transform, including reflection, rotation, shearing, or scaling followed by a translation.

### See Also

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


