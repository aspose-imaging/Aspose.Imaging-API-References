---
title: Class EmfColorAdjustment
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfColorAdjustment class. The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bitblock transfers
type: docs
weight: 3020
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the blue primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness/) { get; set; } | Gets or sets a 16-bit signed integer that specifies the amount of brightness to be applied to the source object. This value SHOULD be in the range from –100 to 100. A value of zero means brightness adjustment MUST NOT be performed. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness/) { get; set; } | Gets or sets a 16-bit signed integer that specifies the amount of colorfulness to be applied to the source object. This value SHOULD be in the range from –100 to 100. A value of zero means colorfulness adjustment MUST NOT be performed |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast/) { get; set; } | Gets or sets a 16-bit signed integer that specifies the amount of contrast to be applied to the source object. This value SHOULD be in the range from –100 to 100. A value of zero means contrast adjustment MUST NOT be performed. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the green primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the type of standard light source under which the image is viewed, from the Illuminant enumeration (section 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the red primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint/) { get; set; } | Gets or sets 16-bit signed integer that specifies the amount of red or green tint adjustment to be applied to the source object. This value SHOULD be in the range from –100 to 100. Positive numbers adjust towards red and negative numbers adjust towards green. A value of zero means tint adjustment MUST NOT be performed |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the black reference for the source colors. Any colors that are darker than this are treated as black. This value SHOULD be in the range from zero to 4,000 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the white reference for the source colors. Any colors that are lighter than this are treated as white. This value SHOULD be in the range from 6,000 to 10,000. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the size in bytes of this object. This MUST be 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies how to prepare the output image. This field can be set to NULL or to any combination of values in the ColorAdjustment enumeration (section 2.1.5). |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


