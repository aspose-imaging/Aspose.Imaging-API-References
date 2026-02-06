---
title: Class EmfPlusBitmapData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBitmapData class. The EmfPlusBitmapData object specifies a bitmap image with pixel data
type: docs
weight: 5300
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
## EmfPlusBitmapData class

The EmfPlusBitmapData object specifies a bitmap image with pixel data.

```csharp
public sealed class EmfPlusBitmapData : EmfPlusBaseBitmapData
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusBitmapData](emfplusbitmapdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/colors/) { get; set; } | Gets or sets the palette colors Colors (variable): An optional [`EmfPlusPalette`](../emfpluspalette/) object (section 2.2.2.28), which specifies the palette of colors used in the pixel data. This field MUST be present if the I flag is set in the PixelFormat field of the [`EmfPlusBitmap`](../emfplusbitmap/) object. |
| [PixelData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/pixeldata/) { get; set; } | Gets or sets pixel data PixelData (variable): An array of bytes that specify the pixel data. The size and format of this data can be computed from fields in the EmfPlusBitmap object, including the pixel format from the [`EmfPlusPixelFormat`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) enumeration (section 2.1.1.25). |

### See Also

* class [EmfPlusBaseBitmapData](../emfplusbasebitmapdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


