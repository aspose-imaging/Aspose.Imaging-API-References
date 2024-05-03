---
title: WmfImage.Resize
second_title: Aspose.Imaging for .NET API Reference
description: WmfImage method. Resize the image with the specified resizing type allowing for flexible adjustment of dimensions while preserving aspect ratio or applying specific scaling algorithms. Integrate this method into your image processing workflow to achieve precise resizing operations tailored to your applications requirements
type: docs
weight: 150
url: /net/aspose.imaging.fileformats.wmf/wmfimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Resize the image with the specified resizing type, allowing for flexible adjustment of dimensions while preserving aspect ratio or applying specific scaling algorithms. Integrate this method into your image processing workflow to achieve precise resizing operations tailored to your application's requirements.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | The resize type. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException |  |

## Examples

This example loads a WMF image and resizes it using various resizing methods.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.BilinearResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Adjust the size of the image based on specified settings, enabling precise control over dimensions, aspect ratio, and scaling behavior. Integrate this method into your image processing workflow to achieve customized resizing operations tailored to the specific requirements of your application.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The resize settings. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException |  |

### See Also

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


