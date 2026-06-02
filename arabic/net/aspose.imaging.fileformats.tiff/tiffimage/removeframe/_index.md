---
title: "TiffImage.RemoveFrame"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. احذف بسهولة الإطار المحدد بواسطة فهرسه من تسلسل الصور لتبسيط إدارة الإطارات داخل تطبيقك. دمج هذه الوظيفة لتعزيز الكفاءة والدقة في معالجة الإطارات مما يسهل تنظيم وعرض محتوى الصورة بسلاسة."
type: docs
weight: 300
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/removeframe/
---
## RemoveFrame(int) {#removeframe}

قم بإزالة الإطار المحدد بواسطة فهرسه من تسلسل الصور بسهولة، مما يبسط إدارة الإطارات داخل تطبيقك. دمج هذه الوظيفة لتعزيز الكفاءة والدقة في معالجة الإطارات، وتسهيل تنظيم وعرض محتوى الصورة بسلاسة.

```csharp
public TiffFrame RemoveFrame(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | Int32 | فهرس الإطار الذي سيتم إزالته. |

### قيمة الإرجاع

الإطار المُزال.

## ملاحظات

ملاحظة: لا تنسَ تحرير (Dispose) الإطار إذا لم تقم بإضافته إلى TiffImage آخر.

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

---

## RemoveFrame(TiffFrame) {#removeframe_1}

قم بإزالة الإطار المحدد من تسلسل الصور بفعالية، مما يسهل إدارة الإطارات داخل تطبيقك. دمج هذه الوظيفة لتعزيز الدقة والمرونة في معالجة الإطارات، وضمان تنظيم وعرض محتوى الصورة بسلاسة.

```csharp
public void RemoveFrame(TiffFrame frame)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | TiffFrame | الإطار المراد إزالته. |

## ملاحظات

ملاحظة: لا تنسَ تحرير (Dispose) الإطار إذا لم تقم بإضافته إلى TiffImage آخر.

### انظر أيضًا

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


