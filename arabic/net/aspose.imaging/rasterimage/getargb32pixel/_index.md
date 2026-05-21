---
title: "RasterImage.GetArgb32Pixel"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحصل على بكسل ARGB 32-بت من الصورة"
type: docs
weight: 310
url: /ar/net/aspose.imaging/rasterimage/getargb32pixel/
---
## RasterImage.GetArgb32Pixel method

يحصل على بكسل صورة 32-بت ARGB.

```csharp
public int GetArgb32Pixel(int x, int y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | موقع البكسل على المحور x. |
| y | Int32 | موقع البكسل على المحور y. |

### قيمة الإرجاع

بكسل ARGB 32-بت للموقع المحدد.

## أمثلة

المثال التالي يحمل صورة نقطية ويحصل على لون بكسل عشوائي ممثل كقيمة عدد صحيح 32-بت.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // احصل على تمثيل عدد صحيح للون البكسل العلوي الأيسر في الصورة.
    int color = rasterImage.GetArgb32Pixel(0, 0);

    // للحصول على قيم مكونات اللون الفردية، قم بإزاحة قيمة اللون بعدد البتات المقابل.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

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

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


