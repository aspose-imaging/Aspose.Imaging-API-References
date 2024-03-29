---
title: VerticalResolution
second_title: Aspose.Imaging for .NET API Referansı
description: Bunun dikey çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.RasterImageaspose.imaging/rasterimage .
type: docs
weight: 100
url: /tr/net/aspose.imaging.fileformats.bmp/bmpimage/verticalresolution/
---
## BmpImage.VerticalResolution property

Bunun dikey çözünürlüğünü inç başına piksel cinsinden alır veya ayarlar.[`RasterImage`](../../../aspose.imaging/rasterimage) .

```csharp
public override double VerticalResolution { get; set; }
```

### Mülk değeri

Dikey çözünürlük.

### Notlar

Varsayılan olarak bu değerin her zaman 96 olduğuna dikkat edin, çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Tek bir çağrıda her iki çözünürlük değerini de güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

### Örnekler

Aşağıdaki örnek, bir BMP görüntüsünün yatay/dikey çözünürlüğünün nasıl ayarlanacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;

    // BmpImage'ın yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = bmpImage.HorizontalResolution;
    double verticalResolution = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Tek bir çağrıda her iki çözünürlük değerini güncellemek için SetResolution yöntemini kullanın.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    // Çıktı şöyle görünebilir:
    // İnç başına piksel cinsinden yatay çözünürlük: 0
    // İnç başına piksel cinsinden dikey çözünürlük: 0
    // Çözünürlük değerlerini 96 dpi olarak ayarla
    // Yatay çözünürlük, inç başına piksel olarak: 96.012
    // İnç başına piksel cinsinden dikey çözünürlük: 96.012
}
```

Aşağıdaki örnek, piksel formatı, görüntü boyutu, çözünürlük, sıkıştırma vb. dahil olmak üzere görüntü hakkında genel bilgileri alır.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;                

    System.Console.WriteLine("The pixel format: {0}", bmpImage.RawDataFormat);                
    System.Console.WriteLine("The raw line size in bytes: {0}", bmpImage.RawLineSize);
    System.Console.WriteLine("The bitmap compression: {0}", bmpImage.Compression);
    System.Console.WriteLine("The bitmap width: {0}", bmpImage.Width);
    System.Console.WriteLine("The bitmap height: {0}", bmpImage.Height);
    System.Console.WriteLine("The number of bits per pixel: {0}", bmpImage.BitsPerPixel);

    double hres = bmpImage.HorizontalResolution;
    double vres = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", hres);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", vres);

    if (hres != 96.0 || vres != 96.0)
    {
        // Tek bir çağrıda her iki çözünürlük değerini de güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    // Çıktı şöyle görünebilir:
    //Piksel formatı: Rgb24Bpp, kullanılan kanallar: 8,8,8
    // Bayt cinsinden ham satır boyutu: 1500
    //Bitmap sıkıştırması: Rgb
    //Bit eşlem genişliği: 500
    //Bit eşlem yüksekliği: 375
    //Piksel başına bit sayısı: 24
    //Piksel/inç cinsinden yatay çözünürlük: 0
    //Piksel/inç olarak dikey çözünürlük: 0
    // Çözünürlük değerlerini 96 dpi olarak ayarla
    //Piksel/inç cinsinden yatay çözünürlük: 96.012
    //Piksel/inç olarak dikey çözünürlük: 96.012
}
```

### Ayrıca bakınız

* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
