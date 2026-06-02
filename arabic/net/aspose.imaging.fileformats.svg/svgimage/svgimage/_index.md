---
title: "SvgImage.SvgImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ SvgImage. ينشئ كائنًا جديدًا من فئة SvgImage باستخدام المسار المحدد لتحديد موقع الصورة وتحميلها. يسهل هذا المنشئ إنشاء نماذج صور SVG من ملفات خارجية مما يتيح دمجًا سلسًا في أنظمة البرمجيات وسير العمل."
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.svg/svgimage/svgimage/
---
## SvgImage(string) {#constructor_3}

ينشئ كائنًا جديدًا من الفئة [`SvgImage`](../)، باستخدام المسار المحدد لتحديد موقع الصورة وتحميلها. يسهل هذا المنشئ إنشاء نماذج صور SVG من ملفات خارجية، مما يتيح دمجًا سلسًا في أنظمة البرمجيات وسير العمل.

```csharp
public SvgImage(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار فارغ. |

### انظر أيضًا

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(Stream) {#constructor_2}

ينشئ نسخة جديدة من الفئة [`SvgImage`](../)، محملاً الصورة من الدفق المقدم. يتيح هذا المنشئ تحميل صور SVG مباشرةً من الدفقات، مما يعزز المرونة والكفاءة في معالجة موارد الصور داخل تطبيقات البرمجيات.

```csharp
public SvgImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | التدفق فارغ. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة SVG من تدفق ملف وتحويلها إلى PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة SVG من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // من أجل تحويل SVG إلى نقطية نحتاج إلى تحديد خيارات التحويل النقطي.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### انظر أيضًا

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(int, int) {#constructor_1}

ينشئ كائنًا جديدًا من [`SvgImage`](../) بالعرض والارتفاع المحددين. يتيح هذا المُنشئ للمطورين إنشاء صور SVG بأبعاد محددة مسبقًا، مما يسهل التحكم الدقيق في حجم الصورة أثناء التهيئة.

```csharp
public SvgImage(int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |

### انظر أيضًا

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(SvgOptions, int, int) {#constructor}

ينشئ نسخة جديدة من الفئة [`SvgImage`](../) مع خيارات SVG المحددة، وعرض الصورة، ومعلمات الارتفاع. يتيح هذا المُنشئ للمطورين تهيئة صور SVG بخيارات وأبعاد مخصصة، مما يوفر مرونة في إدارة محتوى SVG وتخطيطه.

```csharp
public SvgImage(SvgOptions svgOptions, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| svgOptions | SvgOptions | خيارات SVG. |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |

### انظر أيضًا

* class [SvgOptions](../../../aspose.imaging.imageoptions/svgoptions/)
* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)


