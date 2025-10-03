---
title: RasterImage.AdjustGamma
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Gammacorrection of an image
type: docs
weight: 200
url: /net/aspose.imaging/rasterimage/adjustgamma/
---
## AdjustGamma(float, float, float) {#adjustgamma_1}

Gamma-correction of an image.

```csharp
public virtual void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | Single | Gamma for red channel coefficient |
| gammaGreen | Single | Gamma for green channel coefficient |
| gammaBlue | Single | Gamma for blue channel coefficient |

## Examples

The following example performs gamma-correction of an image applying different coefficients for color components.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Set individual gamma coefficients for red, green and blue channels.
    rasterImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float) {#adjustgamma}

Gamma-correction of an image.

```csharp
public virtual void AdjustGamma(float gamma)
```

| Parameter | Type | Description |
| --- | --- | --- |
| gamma | Single | Gamma for red, green and blue channels coefficient |

## Examples

The following example performs gamma-correction of an image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Set gamma coefficient for red, green and blue channels.
    rasterImage.AdjustGamma(2.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


