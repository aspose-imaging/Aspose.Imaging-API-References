---
title: "Image.Load"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تقوم بتحميل صورة جديدة من مسار الملف أو عنوان URL المحدد. إذا كان filePath مسار ملف فإن الطريقة تفتح الملف فقط. إذا كان filePath عنوان URL فإن الطريقة تقوم بتنزيل الملف وتخزينه مؤقتًا وتفتحه"
type: docs
weight: 20
url: /ar/net/aspose.imaging/image/load/
---
## Load(string, LoadOptions) {#load_3}

يقوم بتحميل صورة جديدة من مسار الملف أو عنوان URL المحدد. إذا كان *filePath* مسار ملف، فإن الطريقة تفتح الملف فقط. إذا كان *filePath* عنوان URL، فإن الطريقة تقوم بتنزيل الملف، وتخزينه مؤقتًا، ثم فتحه.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف أو عنوان URL لتحميل الصورة منه. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

الصورة المحملة.

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(string) {#load_2}

يقوم بتحميل صورة جديدة من مسار الملف أو عنوان URL المحدد. إذا كان *filePath* مسار ملف، فإن الطريقة تفتح الملف فقط. إذا كان *filePath* عنوان URL، فإن الطريقة تقوم بتنزيل الملف، وتخزينه مؤقتًا، ثم فتحه.

```csharp
public static Image Load(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف أو عنوان URL لتحميل الصورة منه. |

### قيمة الإرجاع

الصورة المحملة.

## أمثلة

هذا المثال يوضح تحميل ملف Image موجود إلى كائن من Aspose.Imaging.Image باستخدام مسار الملف المحدد

```csharp
[C#]

//إنشاء كائن Image وتهيئته بملف صورة موجود من موقع القرص
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    //قم ببعض معالجة الصورة.
}
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

يقوم بتحميل صورة جديدة من الدفق المحدد.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق البيانات لتحميل الصورة منه. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

الصورة المحملة.

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(Stream) {#load}

يقوم بتحميل صورة جديدة من الدفق المحدد.

```csharp
public static Image Load(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق البيانات لتحميل الصورة منه. |

### قيمة الإرجاع

الصورة المحملة.

## أمثلة

هذا المثال يوضح استخدام كائنات System.IO.Stream لتحميل ملف Image موجود

```csharp
[C#]

//إنشاء مثيل من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.bmp", System.IO.FileMode.Open))
{
    //إنشاء مثال من فئة Image وتحميل ملف موجود عبر كائن FileStream عن طريق استدعاء طريقة Load
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(stream))
    {
        //إجراء بعض معالجة الصور.
    }
}
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


