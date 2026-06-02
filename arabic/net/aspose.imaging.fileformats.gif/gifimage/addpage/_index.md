---
title: "GifImage.AddPage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. دمج صفحة جديدة بسلاسة في الصورة الحالية، مما يعزز محتواها ويوسع نطاقها. تتيح هذه الطريقة توسيع مجموعات الصور بمحتوى إضافي، مما يعزز الإبداع والمرونة في إدارة وتكوين الصور."
type: docs
weight: 200
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/addpage/
---
## GifImage.AddPage method

أدمج صفحة جديدة بسلاسة في الصورة الحالية، معزّزًا محتواها وموسعًا نطاقها. تُضيف هذه الطريقة مجموعات الصور بمحتوى إضافي، مما يعزز الإبداع والمرونة في إدارة وتكوين الصور.

```csharp
public void AddPage(RasterImage page)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| page | RasterImage | الصفحة المراد إضافتها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *page* فارغ. |

## أمثلة

إنشاء صورة GIF متعددة الصفحات باستخدام صور نقطية ذات صفحة واحدة.

```csharp
[C#]

static void Main(string[] args)
{
    // تحميل الإطارات
    var frames = LoadFrames("Animation frames").ToArray();

    // إنشاء صورة GIF باستخدام الإطار الأول
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // إضافة إطارات إلى صورة GIF باستخدام طريقة AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // حفظ صورة GIF
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


