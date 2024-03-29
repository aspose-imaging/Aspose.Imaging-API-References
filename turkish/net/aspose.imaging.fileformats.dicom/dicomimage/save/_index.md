---
title: Save
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntünün verilerini kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.
type: docs
weight: 320
url: /tr/net/aspose.imaging.fileformats.dicom/dicomimage/save/
---
## DicomImage.Save method

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntü verilerinin kaydedileceği akış. |
| optionsBase | ImageOptionsBase | Kaydet seçenekleri. |
| boundsRectangle | Rectangle | Hedef görüntü dikdörtgeni sınırlar. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### Örnekler

Aşağıdaki örnek, bir dosyadan bir DICOM görüntüsü yükler, ardından görüntüyü bir PNG dosya akışına kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width / 2, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Resmin sol üst çeyreğini bir dosya akışına kaydedin.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [DicomImage](../../dicomimage)
* ad alanı [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
