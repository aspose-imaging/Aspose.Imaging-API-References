---
title: Enum ResizeType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ResizeType enum. Specifies the resize type
type: docs
weight: 11440
url: /net/aspose.imaging/resizetype/
---
## ResizeType enumeration

Specifies the resize type.

```csharp
public enum ResizeType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | The pixels are not preserved during resize operation. |
| LeftTopToLeftTop | `1` | Left top point of the new image will coincide with the left top point of the original image. Crop will occur if required. |
| RightTopToRightTop | `2` | Right top point of the new image will coincide with the right top point of the original image. Crop will occur if required. |
| RightBottomToRightBottom | `3` | Right bottom point of the new image will coincide with the right bottom point of the original image. Crop will occur if required. |
| LeftBottomToLeftBottom | `4` | Left bottom point of the new image will coincide with the left bottom point of the original image. Crop will occur if required. |
| CenterToCenter | `5` | Center of the new image will coincide with the center of the original image. Crop will occur if required. |
| LanczosResample | `6` | Resample using lanczos algorithm with a=3. |
| NearestNeighbourResample | `7` | Resample using nearest neighbour algorithm. |
| AdaptiveResample | `8` | Resample using adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation algorithms. |
| BilinearResample | `9` | Resample using bilinear interpolation. Image pre-filtering is allowed to remove the noice before resample, when needed |
| HighQualityResample | `10` | The high quality resample |
| CatmullRom | `11` | The Catmull-Rom cubic interpolation method. |
| CubicConvolution | `12` | The Cubic Convolution interpolation method |
| CubicBSpline | `13` | The CubicBSpline cubic interpolation method |
| Mitchell | `14` | The Mitchell cubic interpolation method |
| SinC | `15` | The Sinc (Lanczos3) cubic interpolation method |
| Bell | `16` | The Bell interpolation method |

## Examples

Resize image using specific Resize Type.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

This example loads an image and resizes it using various resizing methods.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


