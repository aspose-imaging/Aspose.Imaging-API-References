---
title: BinarizeBradley
second_title: Aspose.Imaging for .NET API Referansı
description: Entegre görüntü eşikleme kullanılarak Bradleyin uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi
type: docs
weight: 160
url: /tr/net/aspose.imaging.fileformats.dicom/dicomimage/binarizebradley/
---
## DicomImage.BinarizeBradley method

Entegre görüntü eşikleme kullanılarak Bradley'in uyarlamalı eşikleme algoritması kullanılarak bir görüntünün ikilileştirilmesi

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| brightnessDifference | Double | Piksel ile sxs penceresinin ortalama piksel arasındaki parlaklık farkı bu pikselin etrafında toplanmıştır. |
| windowSize | Int32 | Bu pikselin etrafında ortalanmış piksellerin sxs penceresinin boyutu |

### Örnekler

Aşağıdaki örnek, bir DICOM görüntüsünü Bradley'in uyarlanabilir eşikleme algoritmasıyla belirtilen pencere boyutuyla ikili hale getirir. İkilileştirilmiş görüntüler yalnızca 2 renk içerir - siyah ve beyaz.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Görüntüyü 5 parlaklık farkıyla ikili hale getirin. Parlaklık, bir piksel ile bu pikselin etrafında ortalanmış 10 x 10 piksellik bir pencerenin ortalaması arasındaki farktır.
    dicomImage.BinarizeBradley(5, 10);
    dicomImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* class [DicomImage](../../dicomimage)
* ad alanı [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
