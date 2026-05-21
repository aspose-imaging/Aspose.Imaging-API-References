---
title: "StreamSource.StreamSource"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ StreamSource. ينشئ مثلاً جديداً من الفئة StreamSource"
type: docs
weight: 10
url: /ar/net/aspose.imaging.sources/streamsource/streamsource/
---
## StreamSource() {#constructor}

ينشئ مثلاً جديداً من الفئة [`StreamSource`](../).

```csharp
public StreamSource()
```

### انظر أيضًا

* class [StreamSource](../)
* namespace [Aspose.Imaging.Sources](../../streamsource/)
* assembly [Aspose.Imaging](../../../)

---

## StreamSource(Stream) {#constructor_1}

ينشئ مثلاً جديداً من الفئة [`StreamSource`](../).

```csharp
public StreamSource(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الـ stream للفتح. |

## أمثلة

يوضح هذا المثال كيفية تحميل معلومات البكسل في مصفوفة من النوع Color، تعديل المصفوفة وإعادتها إلى الصورة. لتنفيذ هذه العمليات، ينشئ هذا المثال ملف صورة جديد (بتنسيق GIF) باستخدام كائن MemoryStream.

```csharp
[C#]

//إنشاء مثيل من MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //إنشاء مثيل من GifOptions وتعيين خصائصه المتنوعة بما في ذلك خاصية Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //احصل على بكسلات الصورة عن طريق تحديد المنطقة كحدود الصورة
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //التكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //تعيين لون البكسل المفهرس إلى الأصفر
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //تعيين لون البكسل المفهرس إلى الأزرق
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //تطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    // كتابة MemoryStream إلى ملف
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### انظر أيضًا

* class [StreamSource](../)
* namespace [Aspose.Imaging.Sources](../../streamsource/)
* assembly [Aspose.Imaging](../../../)

---

## StreamSource(Stream, bool) {#constructor_2}

ينشئ مثلاً جديداً من الفئة [`StreamSource`](../).

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الـ stream للفتح. |
| disposeStream | Boolean | إذا تم تعيينه إلى `true` سيتم تحرير الـ stream. |

## أمثلة

يوضح هذا المثال استخدام System.IO.Stream لإنشاء ملف صورة جديد (نوع JPEG).

```csharp
[C#]

//ينشئ مثيلًا من JpegOptions ويضبط خصائصه المتنوعة.
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//إنشاء مثيل من System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//حدد خاصية المصدر للمثيل من JpegOptions.
//المعامل المنطقي الثاني يحدد ما إذا كان سيتم التخلص من الـ Stream بمجرد الخروج من النطاق.
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//ينشئ مثيلًا من Image ويستدعي طريقة Create مع JpegOptions كمعامل لتهيئة كائن Image.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.
}
```

### انظر أيضًا

* class [StreamSource](../)
* namespace [Aspose.Imaging.Sources](../../streamsource/)
* assembly [Aspose.Imaging](../../../)


