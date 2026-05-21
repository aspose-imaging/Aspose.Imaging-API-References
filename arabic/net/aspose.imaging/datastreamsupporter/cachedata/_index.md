---
title: "DataStreamSupporter.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DataStreamSupporter. تخزن البيانات مؤقتًا وتضمن عدم تحميل بيانات إضافية من الـ DataStreamContainer الأساسي"
type: docs
weight: 30
url: /ar/net/aspose.imaging/datastreamsupporter/cachedata/
---
## DataStreamSupporter.CacheData method

تخزن البيانات مؤقتًا وتضمن عدم تحميل بيانات إضافية من الـ [`DataStreamContainer`](../datastreamcontainer/) الأساسي.

```csharp
public abstract void CacheData()
```

## أمثلة

المثال التالي يوضح كيف يؤثر تخزين الصور مؤقتًا على الأداء. في الحالة العامة، قراءة البيانات المخزنة مؤقتًا يتم أسرع من قراءة البيانات غير المخزنة مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة من ملف PNG.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // قم بتخزين جميع بيانات البكسل في الذاكرة المؤقتة بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // قراءة جميع البكسلات سريعة إلى حد ما.
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// تحميل صورة من ملف PNG
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // قراءة جميع البكسلات ليست سريعة كما هي عند التخزين المؤقت
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
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

* class [DataStreamSupporter](../)
* namespace [Aspose.Imaging](../../datastreamsupporter/)
* assembly [Aspose.Imaging](../../../)


