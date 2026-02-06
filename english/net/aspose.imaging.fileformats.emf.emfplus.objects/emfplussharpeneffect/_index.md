---
title: Class EmfPlusSharpenEffect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusSharpenEffect class. The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image
type: docs
weight: 5880
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
## EmfPlusSharpenEffect class

The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.

```csharp
public sealed class EmfPlusSharpenEffect : EmfPlusImageEffectsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSharpenEffect](emfplussharpeneffect/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Amount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/amount/) { get; set; } | Gets or sets A 32-bit floating-point number that specifies the difference in intensity between a given pixel and the surrounding pixels. 0 Specifies that sharpening MUST NOT be performed. 0 &lt; value ≤ 100 As this value increases, the difference in intensity between pixels SHOULD increase. |
| [Radius](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/radius/) { get; set; } | Gets or sets A 32-bit floating-point number that specifies the sharpening radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. As this value increases, the number of pixels involved in the calculation increases, and the resulting bitmap SHOULD become sharper. |

### See Also

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


