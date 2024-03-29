---
title: WebPFrameBlock
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفWebPFrameBlockaspose.imaging.fileformats.webp/webpframeblock
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.webp/webpframeblock/webpframeblock/
---
## WebPFrameBlock(RasterImage) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`WebPFrameBlock`](../../webpframeblock)

صف دراسي.

```csharp
public WebPFrameBlock(RasterImage rasterImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPFrameBlock](../../webpframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* المجسم [Aspose.Imaging](../../../)

---

## WebPFrameBlock(int, int) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`WebPFrameBlock`](../../webpframeblock) فئة .

```csharp
public WebPFrameBlock(int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | العرض. |
| height | Int32 | الإرتفاع. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة WebP متحركة متعددة الإطارات باستخدام الخيارات المحددة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// الإطار الافتراضي بالإضافة إلى 36 + 36 إطارًا إضافيًا.
createOptions.AnimLoopCount = 36 + 36 + 1;

// قم بإنشاء صورة WebP بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد زاوية شكل القوس الأحمر تدريجيًا.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // زد زاوية القوس الأسود تدريجيًا وامسح القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // حفظ في ملف WebP
    webPImage.Save(dir + "output.webp");
}
```

### أنظر أيضا

* class [WebPFrameBlock](../../webpframeblock)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
