---
title: ImageMasking.ApplyMask
second_title: Aspose.Imaging for .NET API Reference
description: ImageMasking method. Applies the mask to specified source image
type: docs
weight: 60
url: /net/aspose.imaging.masking/imagemasking/applymask/
---
## ImageMasking.ApplyMask method

Applies the mask to specified source image.

```csharp
public static void ApplyMask(RasterImage targetImage, RasterImage mask, 
    MaskingOptions maskingOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| targetImage | RasterImage | The target image. |
| mask | RasterImage | The mask image to apply. |
| maskingOptions | MaskingOptions | The masking options. |

## Examples

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

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [MaskingOptions](../../../aspose.imaging.masking.options/maskingoptions/)
* class [ImageMasking](../)
* namespace [Aspose.Imaging.Masking](../../imagemasking/)
* assembly [Aspose.Imaging](../../../)


