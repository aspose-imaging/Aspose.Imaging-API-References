---
title: "Image.CanLoad"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد"
type: docs
weight: 340
url: /ar/net/aspose.imaging/image/canload/
---
## CanLoad(string) {#canload_2}

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد.

```csharp
public static bool CanLoad(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |

### قيمة الإرجاع

`true` إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا `false`.

## أمثلة

يوضح هذا المثال ما إذا كان يمكن تحميل الصورة من ملف.

```csharp
[C#]

// استخدم مسارًا مطلقًا للملف
bool canLoad = Aspose.Imaging.Image.CanLoad(@"c:\temp\sample.gif");
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(string, LoadOptions) {#canload_3}

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختيارياً باستخدام خيارات الفتح المحددة.

```csharp
public static bool CanLoad(string filePath, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

`true` إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا `false`.

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(Stream) {#canload}

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد.

```csharp
public static bool CanLoad(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق للتحميل منه. |

### قيمة الإرجاع

`true` إذا كان يمكن تحميل الصورة من التدفق المحدد؛ وإلا `false`.

## أمثلة

يوضح هذا المثال ما إذا كان يمكن تحميل الصورة من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

bool canLoad;

// استخدم تدفق ملف
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}

// البيانات التالية ليست تدفق صورة صالح، لذا تُعيد CanLoad القيمة false.
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(Stream, LoadOptions) {#canload_1}

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختيارياً باستخدام *loadOptions* المحددة.

```csharp
public static bool CanLoad(Stream stream, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق للتحميل منه. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

`true` إذا كان يمكن تحميل الصورة من التدفق المحدد؛ وإلا `false`.

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


