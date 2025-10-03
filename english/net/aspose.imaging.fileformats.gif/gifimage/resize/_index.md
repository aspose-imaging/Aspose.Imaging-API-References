---
title: GifImage.Resize
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Resizes this Image instance
type: docs
weight: 360
url: /net/aspose.imaging.fileformats.gif/gifimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Resizes this [`Image`](../../../aspose.imaging/image/) instance.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | The resize type. |

## Examples

This example loads a GIF image and resizes it using various resizing methods.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Resizes this [`Image`](../../../aspose.imaging/image/) instance.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The settings. |

## Examples

This example loads a GIF image and resizes it using various resizing settings.

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

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Scale down by 2 times using adaptive resampling.
    gifImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // Save to PNG
    gifImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


