---
title: "WebPFrameBlock.WebPFrameBlock"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ WebPFrameBlock. يهيئ مثيلاً جديداً من WebPFrameBlock"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.webp/webpframeblock/webpframeblock/
---
## WebPFrameBlock(RasterImage) {#constructor}

يهيئ مثيلاً جديداً من [`WebPFrameBlock`](../)

فئة.

```csharp
public WebPFrameBlock(RasterImage rasterImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [WebPFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## WebPFrameBlock(int, int) {#constructor_1}

يهيئ مثيلاً جديداً من الفئة [`WebPFrameBlock`](../).

```csharp
public WebPFrameBlock(int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |

## أمثلة

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

// إنشاء صورة WebP بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد تدريجياً زاوية الشكل القوسي الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // زد تدريجياً زاوية القوس الأسود وأزل القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // حفظ إلى ملف WebP
    webPImage.Save(dir + "output.webp");
}
```

### انظر أيضًا

* class [WebPFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpframeblock/)
* assembly [Aspose.Imaging](../../../)


