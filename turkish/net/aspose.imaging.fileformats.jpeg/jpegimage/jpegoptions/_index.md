---
title: JpegOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Bunu oluşturmak veya yüklemek için kullanılan JPEG seçeneklerini alırJpegImageaspose.imaging.fileformats.jpeg/jpegimage örnek.
type: docs
weight: 130
url: /tr/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

Bunu oluşturmak veya yüklemek için kullanılan JPEG seçeneklerini alır[`JpegImage`](../../jpegimage) örnek.

```csharp
public JpegOptions JpegOptions { get; }
```

### Mülk değeri

JPEG seçenekleri.

### Örnekler

Aşağıdaki örnek, bir JPEG görüntüsünden başlık bilgilerinin nasıl çıkarılacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = image.JpegOptions;

    System.Console.WriteLine("The number of bits per channel: {0}", jpegOptions.BitsPerChannel);
    System.Console.WriteLine("The max allowed size for all internal buffers: {0}", jpegOptions.BufferSizeHint);
    System.Console.WriteLine("The color type: {0}", jpegOptions.ColorType);
    System.Console.WriteLine("The compression type: {0}", jpegOptions.CompressionType);
    System.Console.WriteLine("The image quality: {0}", jpegOptions.Quality);

    if (jpegOptions.ResolutionSettings != null)
    {
        System.Console.WriteLine("The horizontal resolution: {0}", jpegOptions.ResolutionSettings.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution: {0}", jpegOptions.ResolutionSettings.VerticalResolution);
    }

    for (int i = 0; i < jpegOptions.HorizontalSampling.Length; i++)
    {
        System.Console.WriteLine("The sampling for component {0}: {1}x{2}", i, jpegOptions.HorizontalSampling[i], jpegOptions.VerticalSampling[i]);
    }
}

// Çıktı şöyle görünür:
//Kanal başına bit sayısı: 8
//Tüm dahili arabellekler için izin verilen maksimum boyut: 0
//Renk türü: YCbCr
//Sıkıştırma türü: Temel
//Görüntü kalitesi: 75
// 0: 1x1 bileşeni için örnekleme
// Bileşen 1: 1x1 için örnekleme
// Bileşen 2 için örnekleme: 1x1
```

### Ayrıca bakınız

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* ad alanı [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
