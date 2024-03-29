---
title: ResolutionUnit
second_title: Aspose.Imaging for .NET API Referansı
description: Çözünürlük birimini alır veya ayarlar.
type: docs
weight: 160
url: /tr/net/aspose.imaging.imageoptions/jpegoptions/resolutionunit/
---
## JpegOptions.ResolutionUnit property

Çözünürlük birimini alır veya ayarlar.

```csharp
public ResolutionUnit ResolutionUnit { get; set; }
```

### Örnekler

Aşağıdaki örnek, bir BMP görüntüsünü yükler ve çeşitli kaydetme seçeneklerini kullanarak onu JPEG'e kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir dosyadan bir BMP görüntüsü yükleyin.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Biraz görüntü işleme yapın.

    // İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Kanal başına bit sayısı 8'dir.
    // Bir palet kullanıldığında, renk indeksi, rengin kendisi yerine görüntü verisinde saklanır.
    saveOptions.BitsPerChannel = 8;

    // Aşamalı sıkıştırma türünü ayarlayın.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Görüntü kalitesini ayarlayın. 1 ile 100 arasında bir değerdir.
    saveOptions.Quality = 100;

    // Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Kaynak görüntü renkli ise gri tonlamaya dönüştürülür.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Çıktı boyutunu küçültmek için bir palet kullanın.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

Aşağıdaki örnek, belirtilen parametrelerle belirtilen boyutta JPEG görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir JPEG görüntüsü oluşturun.
// İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Y, Cr, Cb bileşenleri için kanal başına bit sayısı 8, 8, 8'dir.
createOptions.BitsPerChannel = 8;

// Aşamalı sıkıştırma türünü ayarlayın.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Görüntü kalitesini ayarlayın. 1 ile 100 arasında bir değerdir.
createOptions.Quality = 100;

// Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Bu, JPEG görüntüleri için standart bir seçenektir.
// İki renk bileşeni (Cb ve Cr) bant genişliği azaltılabilir, alt örneklenebilir, sıkıştırılabilir.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Resmi gri tonlamalı bir gradyanla doldurun
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Bir dosyaya kaydet.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Ayrıca bakınız

* enum [ResolutionUnit](../../../aspose.imaging/resolutionunit)
* class [JpegOptions](../../jpegoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../jpegoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
