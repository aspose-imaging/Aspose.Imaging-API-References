---
title: "Image.GetFileFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. يحصل على تنسيق الملف"
type: docs
weight: 350
url: /ar/net/aspose.imaging/image/getfileformat/
---
## GetFileFormat(string) {#getfileformat_1}

يحصل على تنسيق الملف.

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |

### قيمة الإرجاع

تنسيق الملف المحدد.

## ملاحظات

تنسيق الملف المحدد لا يعني أن الصورة المحددة يمكن تحميلها. استخدم أحد إصدارات طريقة CanLoad لتحديد ما إذا كان يمكن تحميل الملف.

## أمثلة

يوضح هذا المثال كيفية تحديد تنسيق الصورة دون تحميل الصورة بالكامل من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدم مسارًا مطلقًا للملف
Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(dir + "sample.gif");
System.Console.WriteLine("The file format is {0}", format);
```

### انظر أيضًا

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

يحصل على تنسيق الملف.

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |

### قيمة الإرجاع

تنسيق الملف المحدد.

## ملاحظات

تنسيق الملف المحدد لا يعني أن الصورة المحددة يمكن تحميلها. استخدم أحد إصدارات طريقة CanLoad لتحديد ما إذا كان يمكن تحميل التدفق.

## أمثلة

يوضح هذا المثال كيفية تحديد تنسيق الصورة دون تحميل الصورة بالكامل من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدم تدفق ملف
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}

// البيانات التالية ليست تدفق صورة صالح، لذا تُعيد GetFileFormat القيمة FileFormat.Undefined.
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}
```

### انظر أيضًا

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


