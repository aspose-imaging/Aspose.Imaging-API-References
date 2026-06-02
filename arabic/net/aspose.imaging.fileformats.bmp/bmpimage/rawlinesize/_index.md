---
title: "BmpImage.RawLineSize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية BmpImage. احصل بسرعة على حجم كل سطر خام بالبايت باستخدام هذه الخاصية البسيطة. مثالية للمطورين الذين يحتاجون إلى معالجة بيانات الصورة الخام بكفاءة."
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/rawlinesize/
---
## BmpImage.RawLineSize property

احصل بسرعة على حجم كل سطر خام بالبايت باستخدام هذه الخاصية البسيطة. مثالي للمطورين الذين يحتاجون إلى معالجة فعالة للبيانات الخام للصورة

```csharp
public override int RawLineSize { get; }
```

### Property Value

حجم السطر الخام بالبايت.

## أمثلة

المثال التالي يحصل على المعلومات العامة حول الصورة بما في ذلك تنسيق البكسل، حجم الصورة، الدقة، الضغط، إلخ.

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
        // قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //قد يبدو الإخراج هكذا:
    //تنسيق البكسل: Rgb24Bpp، القنوات المستخدمة: 8,8,8
    //حجم السطر الخام بالبايت: 1500
    //ضغط الـ bitmap: Rgb
    //عرض الـ bitmap: 500
    //ارتفاع الـ bitmap: 375
    //عدد البتات لكل بكسل: 24
    //الدقة الأفقية، بوحدات البكسل لكل بوصة: 0
    //الدقة العمودية، بوحدات البكسل لكل بوصة: 0
    //تعيين قيم الدقة إلى 96 نقطة في البوصة
    //الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.012
    //الدقة العمودية، بوحدات البكسل لكل بوصة: 96.012
}
```

المثال التالي يوضح كيف يؤثر ضغط الـ bitmap على حجم الصورة الناتجة.

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

// أنشئ لوحة ألوان أحادية اللون تحتوي فقط على اللونين الأحمر والأخضر.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // أنشئ صورة BMP بدقة 8 بت لكل بكسل بحجم 100 × 100 بكسل.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // املأ الصورة بالكامل باللون الأحمر.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // احفظ الصورة إلى تدفق للحصول على حجم الصورة الناتج.
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

// الإخراج يبدو هكذا:
// ---------------------------------------------
// ضغط الصورة = Rgb
// عدد البتات لكل بكسل = 8
// أبعاد الصورة = 100 × 100
// حجم السطر الخام = 100
// حجم الإخراج بالبايت = 11078
// ---------------------------------------------
// ضغط الصورة = Rle8
// عدد البتات لكل بكسل = 8
// أبعاد الصورة = 100 × 100
// حجم السطر الخام = 100
// حجم الإخراج بالبايت = 856
```

### انظر أيضًا

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


