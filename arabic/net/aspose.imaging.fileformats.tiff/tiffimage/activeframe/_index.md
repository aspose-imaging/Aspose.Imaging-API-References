---
title: "TiffImage.ActiveFrame"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffImage. إدارة الإطار النشط بسلاسة لتسهيل التنقل الديناميكي والتلاعب داخل السياق المحدد. مكن تطبيقك من التفاعل بفعالية مع المحتوى المتعدد الوسائط مما يعزز تفاعل المستخدم والإنتاجية."
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/activeframe/
---
## TiffImage.ActiveFrame property

قم بإدارة الإطار النشط بسلاسة، مما يسهل التنقل الديناميكي والتلاعب داخل السياق المحدد. مكن تطبيقك من التفاعل بفعالية مع المحتوى المتعدد الوسائط، مما يعزز تفاعل المستخدم والإنتاجية.

```csharp
public TiffFrame ActiveFrame { get; set; }
```

### Property Value

الإطار النشط.

## أمثلة

المثال التالي يوضح كيفية تجميع ملف TIFF متعدد الصفحات من صور نقطية فردية.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.AddFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. لنقم بإزالته.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // لا تنسَ تحرير الإطار إذا لم تقم بإضافته إلى TiffImage آخر
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### انظر أيضًا

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


