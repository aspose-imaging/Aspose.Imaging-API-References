---
title: Compression
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntü sıkıştırmasını alır.
type: docs
weight: 40
url: /tr/aspose.imaging.fileformats.bmp/bmpimage/compression/
---
## BmpImage.Compression property

Görüntü sıkıştırmasını alır.

```csharp
public BitmapCompression Compression { get; }
```

### Mülk değeri

Görüntü sıkıştırma.

### Örnekler

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

Aşağıdaki örnek, bitmap sıkıştırmasının çıktı görüntü boyutunu nasıl etkilediğini gösterir.

```csharp
[C#]

Aspose.Imaging.FileFormats.Bmp.BitmapCompression[] compressions = new Aspose.Imaging.FileFormats.Bmp.BitmapCompression[]
{
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb,
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rle8,
};

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Yalnızca kırmızı ve yeşil renkleri içeren tek renkli bir palet oluşturun.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // 100 x 100 piksellik 8-bpp BMP görüntüsü oluşturun.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Resmin tamamını kırmızı ile doldurun.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Çıktı görüntü boyutunu elde etmek için görüntüyü bir akışa kaydedin.
        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            bmpImage.Save(stream);

            System.Console.WriteLine("---------------------------------------------");
            System.Console.WriteLine("The compression={0}", bmpImage.Compression);
            System.Console.WriteLine("The number of bits per pixel={0}", bmpImage.BitsPerPixel);
            System.Console.WriteLine("The image dimensions={0} x {1}", bmpImage.Width, bmpImage.Height);
            System.Console.WriteLine("The raw line size={0}", bmpImage.RawLineSize);
            System.Console.WriteLine("The output size in bytes={0}", stream.Length);
        }
    }
}

// Çıktı şöyle görünür:
// ---------------------------------------------------
// Sıkıştırma = RGB
// Piksel başına bit sayısı = 8
// Görüntü boyutları = 100 x 100
// Ham satır boyutu = 100
// Bayt cinsinden çıktı boyutu = 11078
// ---------------------------------------------------
// Sıkıştırma = Rle8
// Piksel başına bit sayısı = 8
// Görüntü boyutları = 100 x 100
// Ham satır boyutu = 100
// Bayt cinsinden çıktı boyutu = 856
```

### Ayrıca bakınız

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
