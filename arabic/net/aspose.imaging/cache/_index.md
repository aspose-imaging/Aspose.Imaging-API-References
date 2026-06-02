---
title: "Class Cache"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.Cache class. يحتوي على إعدادات الذاكرة المؤقتة."
type: docs
weight: 250
url: /ar/net/aspose.imaging/cache/
---
## Cache class

يحتوي على إعدادات الذاكرة المؤقتة.

```csharp
public static class Cache
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.imaging/cache/allocateddiskbytescount/) { get; } | يحصل على عدد البايتات المخصصة على القرص. |
| static [AllocatedMemoryBytesCount](../../aspose.imaging/cache/allocatedmemorybytescount/) { get; } | يحصل على عدد البايتات المخصصة في الذاكرة. |
| static [CacheFolder](../../aspose.imaging/cache/cachefolder/) { get; set; } | يحصل أو يضبط مجلد الذاكرة المؤقتة. |
| static [CacheType](../../aspose.imaging/cache/cachetype/) { get; set; } | يحصل أو يضبط مخطط الذاكرة المؤقتة المستخدم. |
| static [ExactReallocateOnly](../../aspose.imaging/cache/exactreallocateonly/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة، يجب أن تكون الأداء أعلى. |
| static [MaxDiskSpaceForCache](../../aspose.imaging/cache/maxdiskspaceforcache/) { get; set; } | يحصل أو يضبط الحد الأقصى للمساحة المتاحة على القرص للذاكرة المؤقتة. القيمة المحددة هي عدد الميغابايت. |
| static [MaxMemoryForCache](../../aspose.imaging/cache/maxmemoryforcache/) { get; set; } | يحصل أو يضبط الحد الأقصى للذاكرة المتاحة للذاكرة المؤقتة في الذاكرة. القيمة المحددة هي عدد الميغابايت. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [SetDefaults](../../aspose.imaging/cache/setdefaults/)() | يضبط إعدادات `Cache` إلى القيم الافتراضية. |

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

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


