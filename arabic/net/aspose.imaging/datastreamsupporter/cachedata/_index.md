---
title: CacheData
second_title: Aspose.Imaging لمرجع NET API
description: يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساسDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 30
url: /ar/net/aspose.imaging/datastreamsupporter/cachedata/
---
## DataStreamSupporter.CacheData method

يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../datastreamcontainer) .

```csharp
public abstract void CacheData()
```

### أمثلة

يوضح المثال التالي كيف يؤثر التخزين المؤقت للصور على الأداء. بشكل عام ، يتم تنفيذ قراءة البيانات المخزنة مؤقتًا بشكل أسرع من قراءة البيانات غير المخزنة مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة من ملف PNG.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // تخزين جميع بيانات البكسل مؤقتًا بحيث لا يتم إجراء تحميل بيانات إضافي من دفق البيانات الأساسي
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // قراءة جميع وحدات البكسل سريعة جدًا.
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

    // قراءة جميع وحدات البكسل ليست بالسرعة التي يتم بها التخزين المؤقت
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

// قد يبدو الإخراج كالتالي:
// استغرقت قراءة جميع وحدات البكسل المخزنة مؤقتًا 1500 مللي ثانية.
// استغرقت قراءة جميع وحدات البكسل بدون التخزين المؤقت الأولي 150000 مللي ثانية.
```

### أنظر أيضا

* class [DataStreamSupporter](../../datastreamsupporter)
* مساحة الاسم [Aspose.Imaging](../../datastreamsupporter)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
