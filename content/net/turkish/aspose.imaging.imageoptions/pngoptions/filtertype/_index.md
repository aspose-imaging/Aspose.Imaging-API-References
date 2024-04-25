---
title: FilterType
second_title: Aspose.Imaging for .NET API Referansı
description: png dosyası kaydetme işlemi sırasında kullanılan filtre türünü alır veya ayarlar.
type: docs
weight: 50
url: /tr/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

png dosyası kaydetme işlemi sırasında kullanılan filtre türünü alır veya ayarlar.

```csharp
public PngFilterType FilterType { get; set; }
```

### Örnekler

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

Aşağıdaki örnek, farklı filtre türlerinin çıktı PNG görüntüsünün boyutunu nasıl etkilediğini gösterir.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Bir filtre tipi ayarla
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

// Çıktı şöyle görünebilir:
//Filtre türü Yok, çıktı görüntü boyutu 116845 bayt.
//Filtre türü Yukarı, çıktı görüntü boyutu 86360 bayttır.
//Filtre türü Sub, çıktı görüntü boyutu 94907 bayttır.
//Filtre türü Paeth, çıktı görüntü boyutu 86403 bayttır.
//Filtre türü Avg, çıktı görüntü boyutu 89956 bayttır.
//Filtre türü Uyarlanabilir, çıktı görüntü boyutu 97248 bayttır.
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

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../pngoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
