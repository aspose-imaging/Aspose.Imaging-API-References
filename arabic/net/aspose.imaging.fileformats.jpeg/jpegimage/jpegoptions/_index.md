---
title: JpegOptions
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على خيارات JPEG المستخدمة لإنشاء أو تحميل هذاJpegImageaspose.imaging.fileformats.jpeg/jpegimage المثال.
type: docs
weight: 130
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

الحصول على خيارات JPEG المستخدمة لإنشاء أو تحميل هذا[`JpegImage`](../../jpegimage) المثال.

```csharp
public JpegOptions JpegOptions { get; }
```

### Property_Value

خيارات JPEG .

### أمثلة

يوضح المثال التالي كيفية استخراج معلومات الرأس من صورة JPEG.

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

// يبدو الإخراج كالتالي:
// عدد البتات لكل قناة: 8
// الحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية: 0
// نوع اللون: YCbCr
// نوع الضغط: خط الأساس
// جودة الصورة: 75
// أخذ العينات للمكون 0: 1x1
// أخذ العينات للمكون 1: 1x1
// أخذ العينات للمكون 2: 1x1
```

### أنظر أيضا

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
