---
title: Compression
second_title: Aspose.Imaging لمرجع NET API
description: يحصل على ضغط الصورة .
type: docs
weight: 40
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/compression/
---
## BmpImage.Compression property

يحصل على ضغط الصورة .

```csharp
public BitmapCompression Compression { get; }
```

### Property_Value

ضغط الصورة .

### أمثلة

يحصل المثال التالي على المعلومات العامة حول الصورة بما في ذلك تنسيق البكسل وحجم الصورة والدقة والضغط وما إلى ذلك.

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
        // قد تفكر في استخدام طريقة SetResolution لتحديث قيمتي الدقة في مكالمة واحدة.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    // قد يبدو الإخراج كالتالي:
    // تنسيق البكسل: Rgb24Bpp ، القنوات المستخدمة: 8،8،8
    // حجم الخط الخام بالبايت: 1500
    // ضغط الصورة النقطية: Rgb
    // عرض الصورة النقطية: 500
    // ارتفاع الصورة النقطية: 375
    // عدد البتات لكل بكسل: 24
    // الدقة الأفقية ، بالبكسل في البوصة: 0
    // الدقة الرأسية ، بالبكسل في البوصة: 0
    // ضبط قيم الدقة على 96 نقطة في البوصة
    // الدقة الأفقية بالبكسل في البوصة: 96.012
    // الدقة الرأسية ، بالبكسل في البوصة: 96.012
}
```

يوضح المثال التالي كيف يؤثر ضغط الصورة النقطية على حجم الصورة الناتجة.

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

// قم بإنشاء لوحة أحادية اللون تحتوي فقط على ألوان حمراء وخضراء.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // أنشئ صورة BMP 8-bpp بحجم 100 × 100 بكسل.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // املأ الصورة بأكملها باللون الأحمر.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // حفظ الصورة في دفق للحصول على حجم الصورة الناتجة.
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

// يبدو الإخراج كالتالي:
// ---------------------------------------------
// الضغط = Rgb
// عدد البتات لكل بكسل = 8
// أبعاد الصورة = 100 × 100
// حجم الخط الخام = 100
// حجم الإخراج بالبايت = 11078
// ---------------------------------------------
// الضغط = Rle8
// عدد البتات لكل بكسل = 8
// أبعاد الصورة = 100 × 100
// حجم الخط الخام = 100
// حجم الإخراج بالبايت = 856
```

### أنظر أيضا

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
