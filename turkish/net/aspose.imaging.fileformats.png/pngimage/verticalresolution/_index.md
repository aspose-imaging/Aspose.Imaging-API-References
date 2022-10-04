---
title: VerticalResolution
second_title: Aspose.Imaging for .NET API Referansı
description: Dikey çözünürlüğü alır veya ayarlar.
type: docs
weight: 140
url: /tr/net/aspose.imaging.fileformats.png/pngimage/verticalresolution/
---
## PngImage.VerticalResolution property

Dikey çözünürlüğü alır veya ayarlar.

```csharp
public override double VerticalResolution { get; set; }
```

### Örnekler

Aşağıdaki örnek, bir PNG görüntüsünün yatay/dikey çözünürlüğünün nasıl ayarlanacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

    // PngImage'ın yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = pngImage.HorizontalResolution;
    double verticalResolution = pngImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Tek bir çağrıda her iki çözünürlük değerini güncellemek için SetResolution yöntemini kullanın.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        pngImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", pngImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", pngImage.VerticalResolution);
    }
}
```

### Ayrıca bakınız

* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->