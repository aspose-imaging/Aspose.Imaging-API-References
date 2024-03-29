---
title: AdjustGamma
second_title: Aspose.Imaging for .NET API Referansı
description: Bir görüntünün gama düzeltmesi.
type: docs
weight: 150
url: /tr/net/aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

Bir görüntünün gama düzeltmesi.

```csharp
public override void AdjustGamma(float gamma)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| gamma | Single | Kırmızı, yeşil ve mavi kanal katsayısı için gama |

### Örnekler

Aşağıdaki örnek, bir DICOM görüntüsünün gama düzeltmesini gerçekleştirir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Kırmızı, yeşil ve mavi kanallar için gama katsayısını ayarlayın.
    dicomImage.AdjustGamma(2.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* class [DicomImage](../../dicomimage)
* ad alanı [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* toplantı [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

Bir görüntünün gama düzeltmesi.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| gammaRed | Single | Kırmızı kanal katsayısı için gama |
| gammaGreen | Single | Yeşil kanal katsayısı için gama |
| gammaBlue | Single | Mavi kanal katsayısı için gama |

### Örnekler

Aşağıdaki örnek, renk bileşenleri için farklı katsayılar uygulayarak bir DICOM görüntüsünün gama düzeltmesini gerçekleştirir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Kırmızı, yeşil ve mavi kanallar için ayrı gama katsayılarını ayarlayın.
    dicomImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* class [DicomImage](../../dicomimage)
* ad alanı [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
