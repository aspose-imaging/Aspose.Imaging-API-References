---
title: ColorPaletteHelper.GetCloseTransparentImagePalette
second_title: Aspose.Imaging for .NET API Reference
description: ColorPaletteHelper method. Gets color palette from raster image palletizes image in case the image does not have one. In case palette exists it will be used instead performing calculations
type: docs
weight: 70
url: /net/aspose.imaging/colorpalettehelper/getclosetransparentimagepalette/
---
## ColorPaletteHelper.GetCloseTransparentImagePalette method

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

```csharp
public static IColorPalette GetCloseTransparentImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| entriesCount | Int32 | The desired entries count. |

### Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)


