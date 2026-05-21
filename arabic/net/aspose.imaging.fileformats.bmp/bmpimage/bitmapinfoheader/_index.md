---
title: "BmpImage.BitmapInfoHeader"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية BmpImage. احصل بسرعة على التفاصيل الأساسية حول صورة البت ماب الخاصة بك باستخدام هذه الدالة المبسطة. مثالي للمطورين الذين يحتاجون إلى استرجاع معلومات الرأس لصورهم."
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/
---
## BmpImage.BitmapInfoHeader property

احصل بسرعة على التفاصيل الأساسية حول صورة الـ bitmap الخاصة بك باستخدام هذه الدالة البسيطة. مثالي للمطورين الذين يحتاجون إلى استرجاع معلومات الرأس لصورهم

```csharp
public BitmapInfoHeader BitmapInfoHeader { get; }
```

### Property Value

رأس معلومات البت ماب.

## أمثلة

المثال التالي يحصل على المعلومات من رأس BMP ويطبعها على وحدة التحكم.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    Aspose.Imaging.FileFormats.Bmp.BitmapInfoHeader header = bmpImage.BitmapInfoHeader;

    System.Console.WriteLine("The number of palette colors that are required for displaying the bitmap: {0}", header.BitmapColorsImportant);
    System.Console.WriteLine("The number of palette colors used in the bitmap: {0}", header.BitmapColorsUsed);
    System.Console.WriteLine("The bitmap compression: {0}", header.BitmapCompression);
    System.Console.WriteLine("The bitmap height: {0}", header.BitmapHeight);
    System.Console.WriteLine("The bitmap width: {0}", header.BitmapWidth);
    System.Console.WriteLine("The bitmap raw data size in bytes: {0}", header.BitmapImageSize);
    System.Console.WriteLine("The number of planes: {0}", header.BitmapPlanes);
    System.Console.WriteLine("The horizontal resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapXPelsPerMeter);
    System.Console.WriteLine("The vertical resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapYPelsPerMeter);
    System.Console.WriteLine("The number of bits per pixel: {0}", header.BitsPerPixel);
    System.Console.WriteLine("The extra bits masks: {0}", header.ExtraBitMasks);
    System.Console.WriteLine("The header size in bytes: {0}", header.HeaderSize);
}

//قد يبدو الإخراج هكذا:
//عدد ألوان اللوحة المطلوبة لعرض الصورة النقطية: 0
//عدد ألوان اللوحة المستخدمة في الصورة النقطية: 0
//ضغط الصورة النقطية: 0
//ارتفاع الـ bitmap: 375
//عرض الـ bitmap: 500
//حجم البيانات الخام للصورة النقطية بالبايت: 562500
//عدد المستويات: 1
//الدقة الأفقية للصورة النقطية، بوحدات بكسل لكل متر: 0
//الدقة العمودية للصورة النقطية، بوحدات بكسل لكل متر: 0
//عدد البتات لكل بكسل: 24
//قناع البتات الإضافية: 
//حجم الرأس بالبايت: 40
```

### انظر أيضًا

* class [BitmapInfoHeader](../../bitmapinfoheader/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


