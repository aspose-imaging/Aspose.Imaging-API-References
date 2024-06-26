---
title: DjvuImage.AdjustGamma
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Gamma correction specifically for the red green and blue channels involves adjusting the brightness of each color component separately. By applying different gamma coefficients to the RGB channels you can finetune the overall brightness and contrast of an image. This technique ensures accurate color representation and improves the visual quality of the image across different display devices
type: docs
weight: 170
url: /net/aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

Gamma correction, specifically for the red, green, and blue channels, involves adjusting the brightness of each color component separately. By applying different gamma coefficients to the RGB channels, you can fine-tune the overall brightness and contrast of an image. This technique ensures accurate color representation and improves the visual quality of the image across different display devices.

```csharp
public override void AdjustGamma(float gamma)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gamma | Single | Gamma for red, green and blue channels coefficient |

## Examples

The following example performs gamma-correction of a DJVU image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Set gamma coefficient for red, green and blue channels.
    djvuImage.AdjustGamma(2.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

Gamma correction is applied to an image with customizable parameters for the red, green, and blue channels, allowing precise adjustment of color balance and brightness. This method enhances image quality by fine-tuning color representation, ensuring optimal rendering across different display devices. Adjusting gamma values for individual channels improves color balance and visual appeal.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | Single | Gamma for red channel coefficient |
| gammaGreen | Single | Gamma for green channel coefficient |
| gammaBlue | Single | Gamma for blue channel coefficient |

## Examples

The following example performs gamma-correction of a DJVU image applying different coefficients for color components.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Set individual gamma coefficients for red, green and blue channels.
    djvuImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


