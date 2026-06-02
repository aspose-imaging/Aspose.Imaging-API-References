---
title: "WebPImage.AddBlock"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة WebPImage. دمج كتلة WebP جديدة في الصورة لإثراء محتواها وتسهيل التلاعب المتقدم بالصورة. دمج هذه الطريقة لتعزيز بنية وتعقيد بيانات صورة WebP داخل تطبيقك بشكل ديناميكي، مما يتيح تحكمًا دقيقًا وتحسينًا في عرض الصورة"
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/addblock/
---
## WebPImage.AddBlock method

دمج كتلة WebP جديدة في الصورة، مما يثري محتواها ويسهل معالجة الصور المتقدمة. استخدم هذه الطريقة لتعزيز بنية وتعقيد بيانات صورة WebP داخل تطبيقك بشكل ديناميكي، مما يتيح تحكمًا دقيقًا وتحسينًا لتصيير الصورة.

```csharp
public void AddBlock(IFrame block)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كتلة | IFrame | كتلة Webp لإضافتها. |

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

* interface [IFrame](../../iframe/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


