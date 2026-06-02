---
title: "JpegImage.RgbColorProfile"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية JpegImage. ملف تعريف اللون RGB لصور JPEG بنظام CMYK وYCCK يضمن تحويل اللون وتمثيله بدقة. يجب أن يُقترن بـ CMYKColorProfile للحفاظ على التناسق والموثوقية في عرض الألوان. هذه المجموعة أساسية للتطبيقات التي تتطلب إدارة لون دقيقة وإعادة إنتاج الصور، مما يضمن تفسير وعرض بيانات RGB بشكل صحيح."
type: docs
weight: 150
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile/
---
## JpegImage.RgbColorProfile property

ملف تعريف اللون RGB لصور JPEG بنظام CMYK وYCCK يضمن تحويل اللون وتمثيله بدقة. يجب إقرانه بـ **CMYKColorProfile** للحفاظ على التناسق والدقة في عرض الألوان. هذا الإقران ضروري للتطبيقات التي تتطلب إدارة لون دقيقة وإعادة إنتاج الصور، مما يضمن تفسير بيانات RGB وعرضها بشكل صحيح.

```csharp
public StreamSource RgbColorProfile { get; set; }
```

## أمثلة

المثال التالي يقوم بتحميل PNG ويحفظه كـ CMYK JPEG باستخدام ملف ICC مخصص. ثم يقوم بتحميل CMYK JPEG ويحفظه مرة أخرى كـ PNG. يتم إجراء تحويل اللون من RGB إلى CMYK ومن CMYK إلى RGB باستخدام ملفات ICC مخصصة.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل PNG واحفظه كـ CMYK JPEG
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // استخدم ملفات ICC مخصصة
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// حمّل CMYK JPEG واحفظه كـ PNG
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // استخدم ملفات ICC مخصصة
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
}
```

### انظر أيضًا

* class [StreamSource](../../../aspose.imaging.sources/streamsource/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


