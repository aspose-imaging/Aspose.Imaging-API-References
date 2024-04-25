---
title: Palette
second_title: Aspose.Imaging for .NET API Referansı
description: Renk paletini alır veya ayarlar.
type: docs
weight: 40
url: /tr/aspose.imaging/imageoptionsbase/palette/
---
## ImageOptionsBase.Palette property

Renk paletini alır veya ayarlar.

```csharp
public virtual IColorPalette Palette { get; set; }
```

### Mülk değeri

Renk paleti.

### Örnekler

Aşağıdaki örnek, en uygun paletle dizine alınmış renk kullanılarak PNG görüntüsünün nasıl sıkıştırılacağını gösterir.

```csharp
[C#]

// png görüntüsünü yükler        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Dizine alınmış renk türünü kullan
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Maksimum sıkıştırmayı kullan
         CompressionLevel = 9,
      // Mümkün olduğu kadar çok pikseli kapsayan en yakın 8 bitlik renk paletini alın, böylece paletlenmiş bir görüntü
         // paletlenmemiş olandan neredeyse görsel olarak ayırt edilemez.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // Çıktı dosyası boyutu önemli ölçüde azaltılmalıdır
```

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

Aşağıdaki örnek, çıktı boyutunu küçültmek için bir BMP görüntüsünün nasıl paletleneceğini gösterir.

```csharp
[C#]

// 100 x 100 piksellik bir BMP görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Resmin sol üst köşesinden sağ alt köşesine doğru doğrusal gradyan.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Resmin tamamını doğrusal gradyan fırçasıyla doldurun.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Mümkün olduğu kadar çok pikseli kapsayan en yakın 8 bitlik renk paletini alın, böylece paletlenmiş bir görüntü
    // paletlenmemiş olandan neredeyse görsel olarak ayırt edilemez.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8 bitlik palet en fazla 256 renk içerir.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// Çıktı şöyle görünür:
// Paletlenmiş görüntü boyutu 11078 bayttır.
// Paletlenmemiş görüntü boyutu 40054 bayttır.
```

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette)
* class [ImageOptionsBase](../../imageoptionsbase)
* ad alanı [Aspose.Imaging](../../imageoptionsbase)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
