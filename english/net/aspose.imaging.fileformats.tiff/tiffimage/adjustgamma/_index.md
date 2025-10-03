---
title: TiffImage.AdjustGamma
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Apply gamma correction to the image adjusting pixel intensities to achieve desired color balance. Incorporate this method into your image processing workflow to enhance visual quality and improve the accuracy of subsequent analysis or display tasks within your application
type: docs
weight: 180
url: /net/aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

Apply gamma correction to the image, adjusting pixel intensities to achieve desired color balance. Incorporate this method into your image processing workflow to enhance visual quality and improve the accuracy of subsequent analysis or display tasks within your application.

```csharp
public override void AdjustGamma(float gamma)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gamma | Single | Gamma for red, green and blue channels coefficient |

## Examples

The following example performs gamma-correction of a TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Set gamma coefficient for red, green and blue channels.
    tiffImage.AdjustGamma(2.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

Perform gamma correction on the image using individual coefficients for red, green, and blue channels, allowing for fine-tuned adjustments of color balance and contrast. Integrate this method into your image processing pipeline to achieve precise control over color rendering and enhance visual fidelity within your application.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | Single | Gamma for red channel coefficient |
| gammaGreen | Single | Gamma for green channel coefficient |
| gammaBlue | Single | Gamma for blue channel coefficient |

## Examples

The following example performs gamma-correction of a TIFF image applying different coefficients for color components.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Set individual gamma coefficients for red, green and blue channels.
    tiffImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


