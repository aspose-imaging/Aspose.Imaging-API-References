---
title: "JpegImage.SetResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة JpegImage. تُحدد الدقة للصورة النقطية المحددة (RasterImage) مع ضمان التحجيم والطباعة بدقة. تمكّن هذه الطريقة المستخدمين من تعديل دقة الصورة لتناسب متطلباتهم الخاصة سواء للعرض الرقمي أو النسخ المطبوع. من خلال ضبط الدقة يمكن للمستخدمين تحسين جودة الصورة وضمان التوافق مع مختلف أجهزة الإخراج والوسائط، مما يعزز التجربة البصرية العامة وقابلية استخدام الصورة."
type: docs
weight: 210
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/setresolution/
---
## JpegImage.SetResolution method

تُحدد الدقة للصورة النقطية [`RasterImage`](../../../aspose.imaging/rasterimage/)، مع ضمان التحجيم والطباعة بدقة. تمكّن هذه الطريقة المستخدمين من تعديل دقة الصورة لتناسب متطلباتهم الخاصة، سواء للعرض الرقمي أو النسخ المطبوع. من خلال ضبط الدقة، يمكن للمستخدمين تحسين جودة الصورة وضمان التوافق مع مختلف أجهزة الإخراج والوسائط، مما يعزز التجربة البصرية العامة وقابلية استخدام الصورة.

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | Double | الدقة الأفقية، بوحدة النقاط في البوصة، لـ [`RasterImage`](../../../aspose.imaging/rasterimage/). |
| dpiY | Double | الدقة العمودية، بوحدة النقاط في البوصة، لـ [`RasterImage`](../../../aspose.imaging/rasterimage/). |

## أمثلة

المثال التالي يوضح كيفية ضبط الدقة الأفقية/العمودية لصورة JPEG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = jpegImage.HorizontalResolution;
    double verticalResolution = jpegImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpegImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpegImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpegImage.VerticalResolution);
    }

    // قد يبدو الإخراج هكذا:
    // الدقة الأفقية، بوحدة البكسل في البوصة: 300
    // الدقة العمودية، بوحدة البكسل في البوصة: 300
    // تعيين قيم الدقة إلى 96 نقطة في البوصة
    // الدقة الأفقية، بوحدة البكسل في البوصة: 96
    // الدقة العمودية، بوحدة البكسل في البوصة: 96
}
```

### انظر أيضًا

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


