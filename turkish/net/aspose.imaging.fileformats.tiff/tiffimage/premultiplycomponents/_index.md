---
title: PremultiplyComponents
second_title: Aspose.Imaging for .NET API Referansı
description: Bileşenlerin önceden çoğaltılmasının gerekip gerekmediğini belirten bir değer alır veya ayarlar.
type: docs
weight: 110
url: /tr/net/aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/
---
## TiffImage.PremultiplyComponents property

Bileşenlerin önceden çoğaltılmasının gerekip gerekmediğini belirten bir değer alır veya ayarlar.

```csharp
public override bool PremultiplyComponents { get; set; }
```

### Mülk değeri

`doğru` bileşenlerin önceden çoğaltılması gerekiyorsa; aksi halde,`yanlış` .

### Örnekler

Aşağıdaki örnek, yeni bir TIFF görüntüsü oluşturur, belirtilen yarı saydam pikselleri kaydeder, ardından bu pikselleri yükler ve son renkleri önceden çarpılmış biçimde alır.

```csharp
[C#]

int imageWidth = 3;
int imageHeight = 2;

Aspose.Imaging.Color[] colors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 255, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 255),
};

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Create(createOptions, imageWidth, imageHeight))
{
    // Tüm görüntü için pikselleri kaydedin.
    image.SavePixels(image.Bounds, colors);

    // Pikseller orijinal görüntüde önceden çarpılmamış biçimde saklanır.
    // Önceden çarpılmış renk bileşenlerini elde etmek için ilgili seçeneği açıkça belirtmeniz gerekiyor.
    // Önceden çarpılmış renk bileşenleri şu formüllerle hesaplanır:
    // kırmızı = orijinal_kırmızı * alfa / 255;
    // yeşil = orijinal_yeşil * alfa / 255;
    // mavi = orijinal_mavi * alfa / 255;
    image.PremultiplyComponents = true;
    Aspose.Imaging.Color[] premultipliedColors = image.LoadPixels(image.Bounds);

    for (int i = 0; i < colors.Length; i++)
    {
        System.Console.WriteLine("Original color: {0}", colors[i].ToString());
        System.Console.WriteLine("Premultiplied color: {0}", premultipliedColors[i].ToString());
    }
}

// Çıktı şöyle görünecek:
//Orijinal renk: Renk [A=127, R=255, G=0, B=0]
//Önceden çarpılmış renk: Renk [A=127, R=127, G=0, B=0]
//Orijinal renk: Renk [A=127, R=0, G=255, B=0]
//Önceden çarpılmış renk: Renk [A=127, R=0, G=127, B=0]
//Orijinal renk: Renk [A=127, R=0, G=0, B=255]
//Önceden çarpılmış renk: Renk [A=127, R=0, G=0, B=127]
//Orijinal renk: Renk [A=127, R=255, G=255, B=0]
//Önceden çarpılmış renk: Renk [A=127, R=127, G=127, B=0]
//Orijinal renk: Renk [A=127, R=255, G=0, B=255]
//Önceden çarpılmış renk: Renk [A=127, R=127, G=0, B=127]
//Orijinal renk: Renk [A=127, R=0, G=255, B=255]
//Önceden çarpılmış renk: Renk [A=127, R=0, G=127, B=127]
```

### Ayrıca bakınız

* class [TiffImage](../../tiffimage)
* ad alanı [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->