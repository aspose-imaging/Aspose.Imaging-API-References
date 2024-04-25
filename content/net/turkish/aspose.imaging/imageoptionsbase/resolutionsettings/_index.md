---
title: ResolutionSettings
second_title: Aspose.Imaging for .NET API Referansı
description: Çözünürlük ayarlarını alır veya ayarlar.
type: docs
weight: 60
url: /tr/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

Çözünürlük ayarlarını alır veya ayarlar.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

### Örnekler

Aşağıdaki örnek, bir BMP görüntüsünü yükler ve çeşitli kaydetme seçeneklerini kullanarak onu BMP'ye geri kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // BmpOptions Oluştur
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Çıktı görüntüsünün boyutunu küçültmek için piksel başına 8 bit kullanın.
    saveOptions.BitsPerPixel = 8;

    // Maksimum görüntü pikseli sayısını kapsayan en yakın 8 bitlik renk paletini ayarlayın, böylece paletlenmiş bir görüntü
    // paletlenmemiş olandan neredeyse görsel olarak ayırt edilemez.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Sıkıştırmadan kaydet.
    // Çıktı görüntüsünün boyutunu küçültmek için RLE-8 sıkıştırmasını da kullanabilirsiniz.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Yatay ve dikey çözünürlüğü 96 dpi olarak ayarlayın.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

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

Aşağıdaki örnek, paletlenmiş bir gri tonlamalı BMP görüntüsü oluşturur ve ardından bunu bir dosyaya kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Bir dosyaya kaydet
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Çıktı görüntüsünün boyutunu küçültmek için piksel başına 8 bit kullanın.
createOptions.BitsPerPixel = 8;

// Tüm gri tonlamalı renkleri kapsayan standart 8 bit gri tonlamalı renk paletini ayarlayın.
// İşlenen görüntü yalnızca gri tonlamalı renkler içeriyorsa, paletlenmiş versiyonu
// paletlenmemiş olandan görsel olarak ayırt edilemez.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Sıkıştırmadan kaydet.
// Çıktı görüntüsünün boyutunu küçültmek için RLE-8 sıkıştırmasını da kullanabilirsiniz.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Yatay ve dikey çözünürlüğü 96 dpi olarak ayarlayın.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// 100 x 100 piksellik bir BMP görüntüsü oluşturun ve bir dosyaya kaydedin.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Resmi gri tonlamalı bir gradyanla doldurun
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
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

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* ad alanı [Aspose.Imaging](../../imageoptionsbase)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
