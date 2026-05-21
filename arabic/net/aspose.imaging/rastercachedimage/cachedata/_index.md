---
title: "RasterCachedImage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تخزن البيانات وتضمن عدم تحميل بيانات إضافية من DataStreamContainer الأساسي"
type: docs
weight: 110
url: /ar/net/aspose.imaging/rastercachedimage/cachedata/
---
## RasterCachedImage.CacheData method

يخزن البيانات ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../../datastreamsupporter/datastreamcontainer/).

```csharp
public override void CacheData()
```

## أمثلة

المثال التالي يوضح كيف يؤثر تخزين الصور المؤقت على الأداء. في الحالة العامة، قراءة البيانات المخزنة تكون أسرع من قراءة البيانات غير المخزنة.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة من ملف PNG.
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // قم بتخزين جميع بيانات البكسل في الذاكرة المؤقتة بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // قراءة جميع البكسلات سريعة إلى حد ما.
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = image.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// تحميل صورة من ملف PNG
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // قراءة جميع البكسلات ليست سريعة كما هي عند التخزين المؤقت
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = image.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// قد يبدو الإخراج هكذا:
// استغرق قراءة جميع البكسلات المخزنة مؤقتًا 1500 مللي ثانية.
// استغرق قراءة جميع البكسلات دون تخزين مؤقت مسبق 150000 مللي ثانية.
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


