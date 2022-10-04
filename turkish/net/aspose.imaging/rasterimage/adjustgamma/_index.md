---
title: AdjustGamma
second_title: Aspose.Imaging for .NET API Referansı
description: Bir görüntünün gama düzeltmesi.
type: docs
weight: 210
url: /tr/net/aspose.imaging/rasterimage/adjustgamma/
---
## AdjustGamma(float, float, float) {#adjustgamma_1}

Bir görüntünün gama düzeltmesi.

```csharp
public virtual void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| gammaRed | Single | Kırmızı kanal katsayısı için gama |
| gammaGreen | Single | Yeşil kanal katsayısı için gama |
| gammaBlue | Single | Mavi kanal katsayısı için gama |

### Örnekler

Aşağıdaki örnek, renk bileşenleri için farklı katsayılar uygulayan bir görüntünün gama düzeltmesini gerçekleştirir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Kırmızı, yeşil ve mavi kanallar için ayrı gama katsayılarını ayarlayın.
    rasterImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### Ayrıca bakınız

* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

---

## AdjustGamma(float) {#adjustgamma}

Bir görüntünün gama düzeltmesi.

```csharp
public virtual void AdjustGamma(float gamma)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| gamma | Single | Kırmızı, yeşil ve mavi kanal katsayısı için gama |

### Örnekler

Aşağıdaki örnek, bir görüntünün gama düzeltmesini gerçekleştirir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Kırmızı, yeşil ve mavi kanallar için gama katsayısını ayarlayın.
    rasterImage.AdjustGamma(2.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### Ayrıca bakınız

* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->