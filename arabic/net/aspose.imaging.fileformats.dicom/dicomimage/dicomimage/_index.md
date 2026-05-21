---
title: "DicomImage.DicomImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ DicomImage. أنشئ نسخة جديدة من فئة DicomImage بسهولة باستخدام هذا المنشئ مع معلمات dicomOptions. مثالي للمطورين الذين يرغبون في الغوص في كائنات DicomImage بسرعة وكفاءة في مشاريعهم"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/dicomimage/
---
## DicomImage(DicomOptions, int, int) {#constructor}

أنشئ نسخة جديدة من فئة DicomImage بسهولة باستخدام هذا المنشئ، مع معلمات dicomOptions. مثالي للمطورين الذين يرغبون في الغوص في كائنات [`DicomImage`](../) بسرعة وكفاءة في مشاريعهم.

```csharp
public DicomImage(DicomOptions dicomOptions, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| dicomOptions | DicomOptions | خيارات الـ dicom. |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |

### انظر أيضًا

* class [DicomOptions](../../../aspose.imaging.imageoptions/dicomoptions/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## DicomImage(Stream, LoadOptions) {#constructor_2}

ابدأ نسخة جديدة من فئة DicomImage بسلاسة عن طريق استخدام stream و معلمات loadOptions في هذا المنشئ. مثالية للمطورين المتحمسين لبدء العمل مع كائنات [`DicomImage`](../) بسرعة وفعالية في مشاريعهم.

```csharp
public DicomImage(Stream stream, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| loadOptions | LoadOptions | خيارات التحميل. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DICOM من تدفق ملف للبقاء ضمن الحد المحدد للذاكرة.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة DICOM من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    // الحد الأقصى المسموح لحجم جميع المخازن الداخلية هو 256KB.
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 256 * 1024;

    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream, loadOptions))
    {
        // احفظ كل صفحة كصورة PNG منفردة.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // إنشاء اسم ملف بناءً على فهرس الصفحة.
            string fileName = string.Format("multiframe.{0}.png", dicomPage.Index);

            // صفحة DICOM هي صورة نقطية، لذا جميع العمليات المسموح بها مع الصورة النقطية قابلة للتطبيق على صفحة DICOM.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### انظر أيضًا

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## DicomImage(Stream) {#constructor_1}

إنشاء نسخة جديدة من فئة DicomImage باستخدام معامل تدفق في هذا المُنشئ. مثالي للمطورين الذين يبحثون عن طريقة مبسطة لتهيئة كائنات [`DicomImage`](../) من تدفقات البيانات الموجودة في مشاريعهم.

```csharp
public DicomImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DICOM من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة DICOM من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // احفظ كل صفحة كصورة PNG منفصلة.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // إنشاء اسم ملف بناءً على فهرس الصفحة.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // صفحة DICOM هي صورة نقطية، لذا جميع العمليات المسموح بها مع الصورة النقطية قابلة للتطبيق على صفحة DICOM.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


