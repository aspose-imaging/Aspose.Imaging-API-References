---
title: "JpegImage.JpegOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية JpegImage. احصل على وصول إلى خيارات JPEG المستخدمة أثناء إنشاء أو تحميل هذه الحالة من JpegImage بسهولة. توفر هذه الخاصية تفاصيل قيمة حول الإعدادات المحددة المستخدمة، مما يمكّن المستخدمين من فهم وتكرار سير عمل معالجة الصور بفعالية. سواء كانت مستويات الضغط أو إعدادات الجودة أو غيرها من المعلمات، تقدم هذه الخاصية رؤى أساسية لتعديل الصور بسلاسة."
type: docs
weight: 130
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

احصل على الوصول إلى خيارات JPEG المستخدمة أثناء إنشاء أو تحميل هذه المثيلة [`JpegImage`](../) بسهولة. توفر هذه الخاصية تفاصيل قيمة حول الإعدادات المحددة المستخدمة، مما يمكّن المستخدمين من فهم وتكرار سير عمل معالجة الصور بفعالية. سواء كانت مستويات الضغط، إعدادات الجودة، أو معلمات أخرى، توفر هذه الخاصية رؤى أساسية لتعديل الصور بسلاسة.

```csharp
public JpegOptions JpegOptions { get; }
```

### Property Value

خيارات JPEG.

## أمثلة

المثال التالي يوضح كيفية استخراج معلومات الرأس من صورة JPEG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = image.JpegOptions;

    System.Console.WriteLine("The number of bits per channel: {0}", jpegOptions.BitsPerChannel);
    System.Console.WriteLine("The max allowed size for all internal buffers: {0}", jpegOptions.BufferSizeHint);
    System.Console.WriteLine("The color type: {0}", jpegOptions.ColorType);
    System.Console.WriteLine("The compression type: {0}", jpegOptions.CompressionType);
    System.Console.WriteLine("The image quality: {0}", jpegOptions.Quality);

    if (jpegOptions.ResolutionSettings != null)
    {
        System.Console.WriteLine("The horizontal resolution: {0}", jpegOptions.ResolutionSettings.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution: {0}", jpegOptions.ResolutionSettings.VerticalResolution);
    }

    for (int i = 0; i < jpegOptions.HorizontalSampling.Length; i++)
    {
        System.Console.WriteLine("The sampling for component {0}: {1}x{2}", i, jpegOptions.HorizontalSampling[i], jpegOptions.VerticalSampling[i]);
    }
}

//الإخراج يبدو هكذا:
//عدد البتات لكل قناة: 8
//الحد الأقصى المسموح لحجم جميع المخازن الداخلية: 0
//نوع اللون: YCbCr
//نوع الضغط: Baseline
//جودة الصورة: 75
//العينة للمكوّن 0: 1x1
//العينة للمكوّن 1: 1x1
//العينة للمكوّن 2: 1x1
```

### انظر أيضًا

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


