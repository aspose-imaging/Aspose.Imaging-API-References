---
title: Image.ResizeHeightProportionally
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Resizes the height proportionally. The default NearestNeighbourResample is used
type: docs
weight: 270
url: /net/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

Resizes the height proportionally. The default NearestNeighbourResample is used.

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | Int32 | The new height. |

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

Resizes the height proportionally.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads an image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

Using a segment mask to speed up the segmentation process

```csharp
[C#]

// Masking export options
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Use GraphCut clustering.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// The backgroung color will be transparent.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Reducing image size to speed up the segmentation process
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Create an instance of the ImageMasking class.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Getting the foreground mask
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Increase the size of the mask to the size of the original image
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Applying the mask to the original image to obtain a foreground segment
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### See Also

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

Resizes the height proportionally.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The image resize settings. |

### See Also

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


