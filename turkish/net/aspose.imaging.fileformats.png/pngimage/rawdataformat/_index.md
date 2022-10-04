---
title: RawDataFormat
second_title: Aspose.Imaging for .NET API Referansı
description: Ham veri biçimini alır.
type: docs
weight: 120
url: /tr/net/aspose.imaging.fileformats.png/pngimage/rawdataformat/
---
## PngImage.RawDataFormat property

Ham veri biçimini alır.

```csharp
public override PixelDataFormat RawDataFormat { get; }
```

### Örnekler

Aşağıdaki örnek, PNG resimlerini yükler ve ham veri formatı ve alfa kanalı hakkındaki bilgileri yazdırır.

```csharp
[C#]

// Yüklenecek PNG görüntüleri.
string[] fileNames = new string[]
{
    @"c:\temp\sample.png",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, pngImage.RawDataFormat, pngImage.HasAlpha);
    }
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, kullanılan kanallar: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, kullanılan kanallar: 8,8,8,8, HasAlpha=True
```

### Ayrıca bakınız

* class [PixelDataFormat](../../../aspose.imaging/pixeldataformat)
* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->