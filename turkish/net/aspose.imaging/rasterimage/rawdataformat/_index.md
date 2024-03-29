---
title: RawDataFormat
second_title: Aspose.Imaging for .NET API Referansı
description: Ham veri biçimini alır.
type: docs
weight: 80
url: /tr/net/aspose.imaging/rasterimage/rawdataformat/
---
## RasterImage.RawDataFormat property

Ham veri biçimini alır.

```csharp
public virtual PixelDataFormat RawDataFormat { get; }
```

### Mülk değeri

Ham veri biçimi.

### Örnekler

Aşağıdaki örnek, raster görüntüleri yükler ve ham veri formatı ve alfa kanalı hakkındaki bilgileri yazdırır.

```csharp
[C#]

// Yüklenecek resim dosyaları.
string[] fileNames = new string[]
{
    @"c:\temp\sample.bmp",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, rasterImage.RawDataFormat, rasterImage.HasAlpha);
    }
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.bmp, FileFormat=Rgb24Bpp, kullanılan kanallar: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, kullanılan kanallar: 8,8,8,8, HasAlpha=True
```

Bu örnek, bir dosya akışından bir DJVU görüntüsünün nasıl yükleneceğini ve sayfalarla ilgili bilgilerin nasıl yazdırılacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosya akışından bir DJVU görüntüsü yükleyin.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        System.Console.WriteLine("The total number of pages: {0}", djvuImage.Pages.Length);
        System.Console.WriteLine("The active page number:    {0}", djvuImage.ActivePage.PageNumber);
        System.Console.WriteLine("The first page number:     {0}", djvuImage.FirstPage.PageNumber);
        System.Console.WriteLine("The last page number:      {0}", djvuImage.LastPage.PageNumber);

        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            System.Console.WriteLine("--------------------------------------------------");
            System.Console.WriteLine("Page number:     {0}", djvuPage.PageNumber);
            System.Console.WriteLine("Page size:       {0}", djvuPage.Size);
            System.Console.WriteLine("Page raw format: {0}", djvuPage.RawDataFormat);
        }
    }
}

// Çıktı şöyle görünebilir:
//Toplam sayfa sayısı: 2
//Etkin sayfa numarası: 1
//İlk sayfa numarası: 1
//Son sayfa numarası: 2
//------------------------------------------------ --
//Sayfa numarası: 1
//Sayfa boyutu: { Genişlik = 2481, Yükseklik = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
//------------------------------------------------ --
//Sayfa numarası: 2
//Sayfa boyutu: { Genişlik = 2481, Yükseklik = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
```

### Ayrıca bakınız

* class [PixelDataFormat](../../pixeldataformat)
* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
