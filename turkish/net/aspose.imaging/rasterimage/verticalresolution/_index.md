---
title: VerticalResolution
second_title: Aspose.Imaging for .NET API Referansı
description: Bunun dikey çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.RasterImageaspose.imaging/rasterimage .
type: docs
weight: 170
url: /tr/net/aspose.imaging/rasterimage/verticalresolution/
---
## RasterImage.VerticalResolution property

Bunun dikey çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../../rasterimage) .

```csharp
public virtual double VerticalResolution { get; set; }
```

### Mülk değeri

Dikey çözünürlük.

### Notlar

Varsayılan olarak bu değerin her zaman 96 olduğuna dikkat edin, çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Tek bir çağrıda her iki çözünürlük değerini de güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

### Örnekler

Aşağıdaki örnek, bir tarama görüntüsünün yatay/dikey çözünürlüğünün nasıl ayarlanacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Resmin yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = rasterImage.HorizontalResolution;
    double verticalResolution = rasterImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Tek bir çağrıda her iki çözünürlük değerini güncellemek için SetResolution yöntemini kullanın.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        rasterImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", rasterImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", rasterImage.VerticalResolution);
    }

    // Çıktı şöyle görünebilir:
    // İnç başına piksel cinsinden yatay çözünürlük: 300
    // İnç başına piksel cinsinden dikey çözünürlük: 300
    // Çözünürlük değerlerini 96 dpi olarak ayarla
    // İnç başına piksel cinsinden yatay çözünürlük: 96
    // İnç başına piksel cinsinden dikey çözünürlük: 96
}
```

### Ayrıca bakınız

* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->