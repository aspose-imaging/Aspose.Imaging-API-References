---
title: "TiffFrame.CreateFrameFrom"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffFrame. تنشئ الإطار من tiffFrame المحدد باستخدام الخيارات المحددة. يتم الحفاظ على بيانات البكسل ولكنها تُحوَّل إلى الصيغة المطلوبة."
type: docs
weight: 30
url: /ar/net/aspose.imaging.fileformats.tiff/tiffframe/createframefrom/
---
## TiffFrame.CreateFrameFrom method

ينشئ الإطار من *tiffFrame* المحدد باستخدام *options* المحددة. يتم الحفاظ على بيانات البكسل ولكن يتم تحويلها إلى التنسيق المطلوب.

```csharp
public static TiffFrame CreateFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| tiffFrame | TiffFrame | إطار TIFF لإنشاء الإطار منه. |
| الخيارات | TiffOptions | الخيارات الجديدة للاستخدام. |

### قيمة الإرجاع

الإطار الذي تم إنشاؤه حديثًا.

## أمثلة

المثال التالي يوضح كيفية إنشاء نسخة بالأبيض والأسود من إطار موجود وإضافتها إلى صورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم، وليس مؤقت.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // ملء الإطار النشط بفرشاة تدرج خطي.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // خيارات التدرج الرمادي
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // إنشاء نسخة تدرج رمادي من الإطار النشط.
    // يتم الحفاظ على بيانات البكسل ولكن يتم تحويلها إلى الصيغة المطلوبة.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // إضافة الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### انظر أيضًا

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


