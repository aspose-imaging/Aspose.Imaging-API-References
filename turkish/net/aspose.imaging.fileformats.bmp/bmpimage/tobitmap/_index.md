---
title: ToBitmap
second_title: Aspose.Imaging for .NET API Referansı
description: Raster görüntüyü bitmape dönüştürür.
type: docs
weight: 140
url: /tr/net/aspose.imaging.fileformats.bmp/bmpimage/tobitmap/
---
## BmpImage.ToBitmap method

Raster görüntüyü bitmap'e dönüştürür.

```csharp
public override Bitmap ToBitmap()
```

### Geri dönüş değeri

bit eşlem

### Örnekler

Aşağıdaki örnek, bir BMP görüntüsünü bir GDI bit eşlemine dönüştürür.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    System.Drawing.Bitmap bitmap = bmpImage.ToBitmap();

    // GDI bit eşlemini işle.
}
```

### Ayrıca bakınız

* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
