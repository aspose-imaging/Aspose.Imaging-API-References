---
title: RasterImage.Resize
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Resizes the image with extended options
type: docs
weight: 510
url: /net/aspose.imaging/rasterimage/resize/
---
## RasterImage.Resize method

Resizes the image with extended options.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The resize settings. |

## Examples

This example loads a raster image and resizes it using various resizing settings.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// The adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// The small rectangular filter
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// The number of colors in the palette.
resizeSettings.EntriesCount = 256;

// The color quantization is not used
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// The euclidian method
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using adaptive resampling.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### See Also

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


