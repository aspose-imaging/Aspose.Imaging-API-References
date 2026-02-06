---
title: Class EmfPlusTextureBrushData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTextureBrushData class. The EmfPlusTextureBrushData object specifies a texture image for a graphics brush
type: docs
weight: 5930
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
## EmfPlusTextureBrushData class

The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

```csharp
public sealed class EmfPlusTextureBrushData : EmfPlusBaseBrushData
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusTextureBrushData](emfplustexturebrushdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BrushDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/brushdataflags/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a texture brush BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/optionaldata/) { get; set; } | Gets or sets an optional EmfPlusTextureBrushOptionalData object (section 2.2.2.46) that specifies additional data for the texture brush. The specific contents of this field are determined by the value of the BrushDataFlags field |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/wrapmode/) { get; set; } | Gets or sets a 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies how to repeat the texture image across a shape, when the image is smaller than the area being filled. |

### See Also

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


