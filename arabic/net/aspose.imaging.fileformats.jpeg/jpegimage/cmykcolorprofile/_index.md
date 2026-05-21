---
title: "JpegImage.CmykColorProfile"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية JpegImage. ملف تعريف اللون CMYK المرتبط بصور JPEG بنظام CMYK وYCCK يضمن تحويل لون دقيق وموثوقية. يعمل بالتنسيق مع RGBColorProfile لضمان تمثيل لون صحيح عبر مختلف الأجهزة والتطبيقات. هذه المجموعة ضرورية للحفاظ على التناسق في عرض الألوان وتحقيق جودة صورة مثالية"
type: docs
weight: 30
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/cmykcolorprofile/
---
## JpegImage.CmykColorProfile property

ملف تعريف اللون CMYK المرتبط بصور JPEG بصيغة CMYK و YCCK يضمن تحويلًا دقيقًا للألوان ومطابقة عالية. يعمل بالتنسيق مع RGBColorProfile لضمان تمثيل لون دقيق عبر مختلف الأجهزة والتطبيقات. هذه المجموعة ضرورية للحفاظ على اتساق عرض الألوان وتحقيق جودة صورة مثالية.

```csharp
public StreamSource CmykColorProfile { get; set; }
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


