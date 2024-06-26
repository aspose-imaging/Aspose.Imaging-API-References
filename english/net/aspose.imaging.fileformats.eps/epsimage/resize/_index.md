---
title: EpsImage.Resize
second_title: Aspose.Imaging for .NET API Reference
description: EpsImage method. This method resizes the image adjusting its dimensions according to specified parameters. It offers a straightforward way to modify the size of the image ensuring flexibility and ease of use for developers
type: docs
weight: 200
url: /net/aspose.imaging.fileformats.eps/epsimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

This method resizes the image, adjusting its dimensions according to specified parameters. It offers a straightforward way to modify the size of the image, ensuring flexibility and ease of use for developers.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | The resize type. |

## Examples

Resize EPS image and export it to PNG format.

```csharp
[C#]

// Load EPS image
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Resize the image using the Mitchell cubic interpolation method
    image.Resize(400, 400, ResizeType.Mitchell);

    // Export image to PNG format
    image.Save("ExportResult.png", new PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

This method resizes the image using predefined settings, allowing for efficient adjustment of dimensions. It provides a convenient way to modify the image size while maintaining control over various parameters, ensuring optimal results for different use cases.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The resize settings. |

## Examples

Resize EPS image using advanced settings.

```csharp
[C#]

// Load EPS image
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Resize the image using advanced resize settings
    image.Resize(400, 400, new ImageResizeSettings
    {
        // Set the interpolation mode
        Mode = ResizeType.LanczosResample,

        // Set the type of the filter
        FilterType = ImageFilterType.SmallRectangular,

        // Sets the color compare method
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // Set the color quantization method
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // Export image to PNG format
    image.Save("ExportResult.png", new PngOptions());
}
```

### See Also

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)


