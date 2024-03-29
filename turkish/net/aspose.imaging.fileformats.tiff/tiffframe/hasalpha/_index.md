---
title: HasAlpha
second_title: Aspose.Imaging for .NET API Referansı
description: Bu örneğin alfa olup olmadığını gösteren bir değer alır.
type: docs
weight: 80
url: /tr/net/aspose.imaging.fileformats.tiff/tiffframe/hasalpha/
---
## TiffFrame.HasAlpha property

Bu örneğin alfa olup olmadığını gösteren bir değer alır.

```csharp
public override bool HasAlpha { get; }
```

### Mülk değeri

`doğru` bu örnekte alfa varsa; aksi halde,`yanlış` .

### Örnekler

Aşağıdaki örnek, bir TIFF görüntüsü yükler ve ham veri formatı ve alfa kanalı hakkında bilgi yazdırır.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.tif";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Etkin TIFF çerçevesinin alfa kanalı varsa, tüm TIFF görüntüsünün alfa kanalı olduğu kabul edilir.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, tiffImage.RawDataFormat, tiffImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", ++i, frame.RawDataFormat, frame.HasAlpha);
    }
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, kullanılan kanallar: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, kullanılan kanallar: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, kullanılan kanallar: 1, HasAlpha=False
```

### Ayrıca bakınız

* class [TiffFrame](../../tiffframe)
* ad alanı [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
