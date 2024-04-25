---
title: Progressive
second_title: Aspose.Imaging for .NET API Referansı
description: Bunun olup olmadığını gösteren bir değer alır veya ayarlar.PngOptionsaspose.imaging.imageoptions/pngoptions ilericidir.
type: docs
weight: 60
url: /tr/aspose.imaging.imageoptions/pngoptions/progressive/
---
## PngOptions.Progressive property

Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`PngOptions`](../../pngoptions) ilericidir.

```csharp
public bool Progressive { get; set; }
```

### Mülk değeri

`doğru` ilerici ise; aksi halde,`yanlış` .

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

Bu örnek, belirtilen seçeneklerle bir PNG görüntüsünün nasıl oluşturulacağını, doğrusal gradyan renklerle nasıl doldurulacağını ve bir dosyaya nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Renk kanalı başına bit sayısı
createOptions.BitDepth = 8;

// Her piksel bir (kırmızı, yeşil, mavi) üçlüsüdür ve ardından alfa bileşeni gelir.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Maksimum sıkıştırma seviyesi.
createOptions.CompressionLevel = 9;

// Filtrelerin kullanımı, sürekli tonlu görüntülerin daha etkin bir şekilde sıkıştırılmasını sağlar.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Aşamalı yüklemeyi kullan
createOptions.Progressive = true;

// Özel parametrelerle bir PNG görüntüsü oluşturun.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Resmi yarı saydam bir gradyanla doldurun.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Bir dosyaya kaydet.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

Aşağıdaki örnek, çeşitli seçenekler kullanılarak bir görüntünün PNG formatına nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// 100x100 piksellik bir PNG görüntüsü oluşturun.
// Bir dosyadan veya bir akıştan desteklenen herhangi bir formattaki görüntüyü de yükleyebilirsiniz.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Resmi mavi-saydam gradyanla doldurun.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Aşamalı yükleme.
    saveOptions.Progressive = true;

    // Yatay ve dikey çözünürlüğü inç başına 96 piksel olarak ayarlayın.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Her piksel bir (kırmızı, yeşil, mavi) üçlü ve ardından alfadır.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Maksimum sıkıştırma seviyesini ayarlayın.
    saveOptions.CompressionLevel = 9;

    // Bu, en iyi sıkıştırma, ancak en yavaş yürütme süresidir.
    // Uyarlamalı filtreleme, kaydetme işleminin her veri satırı için en uygun filtreyi seçeceği anlamına gelir.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // Kanal başına bit sayısı.
    saveOptions.BitDepth = 8;

    // Bir dosyaya kaydet.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Ayrıca bakınız

* class [PngOptions](../../pngoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../pngoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
