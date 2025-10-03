---
title: WebPImage.Resize
second_title: Aspose.Imaging for .NET API Reference
description: WebPImage method. Resize the image adjusting its dimensions while preserving the aspect ratio. Integrate this method into your image processing workflow to dynamically scale images to fit various display or storage requirements within your application
type: docs
weight: 230
url: /net/aspose.imaging.fileformats.webp/webpimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Resize the image, adjusting its dimensions while preserving the aspect ratio. Integrate this method into your image processing workflow to dynamically scale images to fit various display or storage requirements within your application.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | The resize type. |

## Examples

This example loads a WEBP image and resizes it using various resizing methods.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with default options.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with default options.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with default options.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with default options.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Resize the image according to specified settings, enabling precise control over dimensions, aspect ratio, and scaling behavior. Integrate this method into your image processing workflow to achieve customized resizing operations tailored to the specific requirements of your application.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The resize settings. |

### See Also

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


