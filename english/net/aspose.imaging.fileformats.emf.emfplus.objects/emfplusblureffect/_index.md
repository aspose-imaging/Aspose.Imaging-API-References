---
title: Class EmfPlusBlurEffect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlurEffect class. The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image
type: docs
weight: 5340
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
## EmfPlusBlurEffect class

The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

```csharp
public sealed class EmfPlusBlurEffect : EmfPlusImageEffectsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusBlurEffect](emfplusblureffect/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlurRadius](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/blurradius/) { get; set; } | Gets or sets a 32-bit floating-point number that specifies the blur radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. This value MUST be in the range 0.0 through 255.0. |
| [ExpandEdge](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/expandedge/) { get; set; } | Gets or sets a 32-bit Boolean value that specifies whether the bitmap expands by an amount equal to the value of the BlurRadius to produce soft edges. This value MUST be one of the following: FALSE 0x00000000 The size of the bitmap MUST NOT change, and its soft edges SHOULD be clipped to the size of the BlurRadius. TRUE 0x00000001 The size of the bitmap SHOULD expand by an amount equal to the BlurRadius to produce soft edges. |

### See Also

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


