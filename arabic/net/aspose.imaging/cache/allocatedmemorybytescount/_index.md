---
title: "Cache.AllocatedMemoryBytesCount"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية Cache. يحصل على عدد البايتات المخصصة في الذاكرة"
type: docs
weight: 20
url: /ar/net/aspose.imaging/cache/allocatedmemorybytescount/
---
## Cache.AllocatedMemoryBytesCount property

يحصل على عدد البايتات المخصصة في الذاكرة.

```csharp
public static long AllocatedMemoryBytesCount { get; }
```

### Property Value

عدد البايتات المخصصة في الذاكرة.

## أمثلة

هذا المثال يوضح استخدام Aspose.Imaging.Cache

```csharp
[C#]

// بشكل افتراضي يتم تعيين مجلد الذاكرة المؤقتة إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد ذاكرة مؤقتة آخر غير الافتراضي كما يلي:
// Cache.CacheFolder = @"D:\\MyTemp";

// الوضع التلقائي مرن وفعال
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

// القيمة الافتراضية هي 0، مما يعني أنه لا يوجد حد أعلى
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
Aspose.Imaging.Cache.ExactReallocateOnly = false;

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة عن طريق فحص الخصائص التالية
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

// قم ببعض معالجة الصور كما يلي
Aspose.Imaging.ImageOptions.GifOptions options = new Aspose.Imaging.ImageOptions.GifOptions();
options.Palette = new ColorPalette(new Aspose.Imaging.Color[] { Aspose.Imaging.Color.Red, Aspose.Imaging.Color.Blue, Aspose.Imaging.Color.Black, Aspose.Imaging.Color.White });
options.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(options, 100, 100))
{
    Aspose.Imaging.Color[] pixels = new Aspose.Imaging.Color[10000];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Aspose.Imaging.Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على أي كائن، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### انظر أيضًا

* class [Cache](../)
* namespace [Aspose.Imaging](../../cache/)
* assembly [Aspose.Imaging](../../../)


