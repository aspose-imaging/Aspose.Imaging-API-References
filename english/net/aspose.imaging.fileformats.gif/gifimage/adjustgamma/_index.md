---
title: GifImage.AdjustGamma
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Enhance image quality by applying gamma correction. This method adjusts the color gamma of the image to achieve optimal visual clarity. It modifies the gamma value of each pixel resulting in improved color rendition and overall image appearance
type: docs
weight: 230
url: /net/aspose.imaging.fileformats.gif/gifimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

Enhance image quality by applying gamma correction. This method adjusts the color gamma of the image to achieve optimal visual clarity. It modifies the gamma value of each pixel, resulting in improved color rendition and overall image appearance.

```csharp
public override void AdjustGamma(float gamma)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gamma | Single | Gamma for red, green and blue channels coefficient |

## Examples

The following example performs gamma-correction of a GIF image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Set gamma coefficient for red, green and blue channels.
    gifImage.AdjustGamma(2.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

Gamma-correction of an image applies a nonlinear adjustment to the pixel values, enhancing or reducing brightness based on the specified coefficients for the red, green, and blue channels. This method helps to fine-tune the color balance and luminance of the image, improving its overall appearance and visual quality.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | Single | Gamma for red channel coefficient |
| gammaGreen | Single | Gamma for green channel coefficient |
| gammaBlue | Single | Gamma for blue channel coefficient |

## Examples

The following example performs gamma-correction of a GIF image applying different coefficients for color components.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Set individual gamma coefficients for red, green and blue channels.
    gifImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


