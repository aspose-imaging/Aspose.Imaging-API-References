---
title: "PsdOptions.ChannelsCount"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PsdOptions. يحصل أو يضبط عدد قنوات اللون"
type: docs
weight: 30
url: /ar/net/aspose.imaging.imageoptions/psdoptions/channelscount/
---
## PsdOptions.ChannelsCount property

يحصل أو يعيّن عدد قنوات اللون.

```csharp
public short ChannelsCount { get; set; }
```

### Property Value

عدد قنوات اللون.

## أمثلة

يوضح هذا المثال كيفية حفظ صورة PNG إلى تنسيق PSD باستخدام خيارات PSD المتنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha))
{
    // حدد تدرجًا خطيًا أزرقًا شفافًا.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ صورة PNG بالتدرج الخطّي الأزرق الشفاف.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // سيتم استخدام الخيارات التالية لحفظ صورة PNG إلى تنسيق PSD.
    Aspose.Imaging.ImageOptions.PsdOptions saveOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // عدد البتات لكل قناة
    saveOptions.ChannelBitsCount = 8;

    // عدد القنوات. قناة واحدة لكل مكوّن لوني R,G,B,A
    saveOptions.ChannelsCount = 4;

    // وضع اللون
    saveOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Rgb;

    // بدون ضغط
    saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.Raw;

    // الإصدار الافتراضي هو 6
    saveOptions.Version = 6;            

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.psd"))
    {
        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RAW compression: {0}", stream.Length);
    }

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.RLE.psd"))
    {
        // ضغط RLE يسمح بتقليل حجم الصورة الناتجة
        saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.RLE;

        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RLE compression: {0}", stream.Length);
    }

    // قد يبدو الإخراج هكذا:
    // حجم صورة PSD مع ضغط RAW: 40090
    // حجم صورة PSD مع ضغط RLE: 16185
}
```

### انظر أيضًا

* class [PsdOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../psdoptions/)
* assembly [Aspose.Imaging](../../../)


