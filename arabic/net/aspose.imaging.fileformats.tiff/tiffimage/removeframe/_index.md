---
title: RemoveFrame
second_title: Aspose.Imaging لمرجع NET API
description: يزيل الإطار بفهرسه.
type: docs
weight: 310
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/removeframe/
---
## RemoveFrame(int) {#removeframe}

يزيل الإطار بفهرسه.

```csharp
public TiffFrame RemoveFrame(int index)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| index | Int32 | فهرس الإطار المراد إزالته. |

### قيمة الإرجاع

الإطار الذي تمت إزالته.

### ملاحظات

ملاحظة: لا تنس التخلص من الإطار إذا لم تقم بإضافته إلى بعض صور TiffImage الأخرى.

### أمثلة

يوضح المثال التالي كيفية تكوين TIFF متعدد الأشكال من الصور النقطية الفردية.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // هذا هو الخط والفرشاة لرسم النص على إطارات فردية.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // قم بإنشاء صورة PNG وارسم رقم الصفحة عليها.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // أضف الإطار إلى صورة TIFF.
        tiffImage.AddFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. دعونا نزيله.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // لا تنس التخلص من الإطار إذا لم تقم بإضافته إلى بعض صور TiffImage الأخرى
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### أنظر أيضا

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* المجسم [Aspose.Imaging](../../../)

---

## RemoveFrame(TiffFrame) {#removeframe_1}

يزيل الإطار المحدد.

```csharp
public void RemoveFrame(TiffFrame frame)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| frame | TiffFrame | الإطار المراد إزالته. |

### ملاحظات

ملاحظة: لا تنس التخلص من الإطار إذا لم تقم بإضافته إلى بعض صور TiffImage الأخرى.

### أنظر أيضا

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
