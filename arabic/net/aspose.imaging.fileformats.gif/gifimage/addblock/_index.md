---
title: "GifImage.AddBlock"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. إضافة كتلة GIF جديدة تتيح لك تضمين بيانات إضافية داخل الصورة. تتيح لك هذه الطريقة إلحاق كتل مخصصة إلى صورة GIF والتي يمكن أن تحتوي على أنواع مختلفة من المعلومات"
type: docs
weight: 190
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/addblock/
---
## GifImage.AddBlock method

إضافة كتلة GIF جديدة تتيح لك تضمين بيانات إضافية داخل الصورة. تمكّن هذه الطريقة من إلحاق كتل مخصصة إلى صورة GIF، والتي يمكن أن تحتوي على أنواع مختلفة من المعلومات.

```csharp
public void AddBlock(IGifBlock block)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كتلة | IGifBlock | كتلة GIF المراد إضافتها. |

## أمثلة

المثال التالي يوضح كيفية تجميع صورة GIF متحركة من كتل GIF فردية.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة GIF بحجم 100 × 100 بكسل.
// الكتلة الأولى تكون سوداء بالكامل بشكل افتراضي.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد تدريجياً زاوية الشكل القوسي الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // زد تدريجياً زاوية القوس الأسود وأزل القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### انظر أيضًا

* interface [IGifBlock](../../igifblock/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


