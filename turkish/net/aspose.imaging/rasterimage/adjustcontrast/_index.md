---
title: AdjustContrast
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntü kontrastı
type: docs
weight: 200
url: /tr/net/aspose.imaging/rasterimage/adjustcontrast/
---
## RasterImage.AdjustContrast method

Görüntü kontrastı

```csharp
public virtual void AdjustContrast(float contrast)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| contrast | Single | Kontrast değeri ([-100; 100] aralığında) |

### Örnekler

Aşağıdaki örnek, bir görüntünün kontrast düzeltmesini gerçekleştirir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### Ayrıca bakınız

* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
