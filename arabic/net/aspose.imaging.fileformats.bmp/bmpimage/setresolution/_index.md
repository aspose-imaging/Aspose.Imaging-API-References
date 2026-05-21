---
title: "BmpImage.SetResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة BmpImage. اضبط دقة الـ RasterImage الخاصة بك بسهولة باستخدام هذه الطريقة الصديقة للمستخدم. مثالية للمطورين الذين يسعون إلى تحكم دقيق في دقة الصورة في تطبيقاتهم"
type: docs
weight: 140
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/setresolution/
---
## BmpImage.SetResolution method

اضبط دقة الـ [`RasterImage`](../../../aspose.imaging/rasterimage/) الخاصة بك بسهولة باستخدام هذه الطريقة الصديقة للمستخدم. مثالية للمطورين الذين يسعون إلى تحكم دقيق في دقة الصورة في تطبيقاتهم.

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | Double | الدقة الأفقية، بوحدة النقاط في البوصة، لـ [`RasterImage`](../../../aspose.imaging/rasterimage/). |
| dpiY | Double | الدقة العمودية، بوحدة النقاط في البوصة، لـ [`RasterImage`](../../../aspose.imaging/rasterimage/). |

## أمثلة

المثال التالي يوضح كيفية ضبط الدقة الأفقية/العمودية لصورة BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = bmpImage.HorizontalResolution;
    double verticalResolution = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    // قد يبدو الإخراج هكذا:
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 0
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 0
    // تعيين قيم الدقة إلى 96 نقطة في البوصة
    // الدقة الأفقية، بوحدات البكسل لكل بوصة: 96.012
    // الدقة العمودية، بوحدات البكسل لكل بوصة: 96.012
}
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

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


