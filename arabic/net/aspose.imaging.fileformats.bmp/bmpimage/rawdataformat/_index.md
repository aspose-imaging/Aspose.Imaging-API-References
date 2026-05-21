---
title: "BmpImage.RawDataFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية BmpImage. احصل بسهولة على تنسيق بياناتك الخام باستخدام هذه الدالة سهلة الاستخدام. مثالية للمطورين الذين يرغبون في الوصول السريع إلى المعلومات الحيوية حول تنسيق بياناتهم"
type: docs
weight: 90
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/rawdataformat/
---
## BmpImage.RawDataFormat property

احصل بسهولة على تنسيق البيانات الخام الخاصة بك باستخدام هذه الدالة سهلة الاستخدام. مثالي للمطورين الذين يرغبون في الوصول السريع إلى معلومات حيوية حول تنسيق بياناتهم

```csharp
public override PixelDataFormat RawDataFormat { get; }
```

### Property Value

تنسيق البيانات الخام.

## أمثلة

المثال التالي يوضح كيفية استخراج معلومات حول تنسيق البيانات الخام وقناة ألفا من صورة BMP.

```csharp
[C#]

// إنشاء صورة BMP بعمق 32 بت بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 32, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// إنشاء صورة BMP بعمق 24 بت بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 24, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// عمومًا، لا يدعم BMP قناة ألفا لذا سيظهر الناتج هكذا:
// FileFormat = Bmp, RawDataFormat = Rgb32Bpp, used channels: 8,8,8,8, HasAlpha = False
// FileFormat = Bmp, RawDataFormat = Rgb24Bpp, used channels: 8,8,8, HasAlpha = False
```

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

### انظر أيضًا

* class [PixelDataFormat](../../../aspose.imaging/pixeldataformat/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


