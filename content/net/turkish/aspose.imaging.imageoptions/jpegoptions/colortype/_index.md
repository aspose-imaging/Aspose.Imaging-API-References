---
title: ColorType
second_title: Aspose.Imaging for .NET API Referansı
description: jpeg görüntüsü için renk türünü alır veya ayarlar.
type: docs
weight: 40
url: /tr/aspose.imaging.imageoptions/jpegoptions/colortype/
---
## JpegOptions.ColorType property

jpeg görüntüsü için renk türünü alır veya ayarlar.

```csharp
public JpegCompressionColorMode ColorType { get; set; }
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

Aşağıdaki örnek PNG'yi yükler ve özel ICC profilini kullanarak CMYK JPEG'e kaydeder. Ardından CMYK JPEG'i yükler ve onu tekrar PNG'ye kaydeder. RGB'den CMYK'ya ve CMYK'dan RGB'ye renk dönüşümü, özel ICC profilleri kullanılarak gerçekleştirilir.

```csharp
[C#]

string dir = "c:\\temp\\";

// PNG'yi yükleyin ve CMYK JPEG'e kaydedin
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // Özel ICC profillerini kullan
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// CMYK JPEG yükleyin ve PNG'ye kaydedin
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // Özel ICC profillerini kullan
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
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

* enum [JpegCompressionColorMode](../../../aspose.imaging.fileformats.jpeg/jpegcompressioncolormode)
* class [JpegOptions](../../jpegoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../jpegoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
