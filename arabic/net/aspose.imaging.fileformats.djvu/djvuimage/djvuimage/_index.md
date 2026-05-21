---
title: "DjvuImage.DjvuImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ DjvuImage. ابدأ العمل مع صور DjVu بإنشاء نسخة جديدة من فئة DjvuImage باستخدام معامل Stream. مثالي للمطورين الذين يرغبون في دمج سلس لمعالجة صور DjVu في مشاريعهم"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/djvuimage/
---
## DjvuImage(Stream) {#constructor}

ابدأ العمل مع صور DjVu بإنشاء نسخة جديدة من الفئة [`DjvuImage`](../) باستخدام معامل Stream. مثالي للمطورين الذين يرغبون في دمج سلس لمعالجة صور DjVu في مشاريعهم.

```csharp
public DjvuImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | Stream فارغ |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DJVU من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة DJVU من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // احفظ كل صفحة كصورة PNG منفردة.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // أنشئ اسم ملف استنادًا إلى رقم الصفحة.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## DjvuImage(Stream, LoadOptions) {#constructor_1}

ابدأ العمل مع صور DjVu بسلاسة باستخدام هذا المنشئ، الذي ينشئ نسخة جديدة من الفئة [`DjvuImage`](../) باستخدام معاملين: Stream و LoadOptions. مثالي للمطورين الذين يرغبون في تحكم دقيق في خيارات تحميل صور DjVu مع الحفاظ على البساطة والكفاءة.

```csharp
public DjvuImage(Stream stream, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق للتحميل منه. |
| loadOptions | LoadOptions | خيارات التحميل. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | Stream فارغ |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DJVU من تدفق ملف للبقاء ضمن الحد المحدد للذاكرة.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة DJVU من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    // الحد الأقصى المسموح لحجم جميع المخازن الداخلية هو 1 ميغابايت.
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 1 * 1024 * 1024;

    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream, loadOptions))
    {
        // احفظ كل صفحة كصورة PNG منفردة.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // أنشئ اسم ملف استنادًا إلى رقم الصفحة.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### انظر أيضًا

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


