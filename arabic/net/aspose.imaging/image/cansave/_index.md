---
title: "Image.CanSave"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة"
type: docs
weight: 200
url: /ar/net/aspose.imaging/image/cansave/
---
## Image.CanSave method

يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة.

```csharp
public bool CanSave(ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الخيارات | ImageOptionsBase | خيارات الحفظ التي سيتم استخدامها. |

### قيمة الإرجاع

`true` إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة؛ وإلا، `false`.

## أمثلة

يوضح هذا المثال كيفية تحديد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
    saveOptions.Quality = 50;

    // تحديد ما إذا كان يمكن حفظ الصورة بصيغة JPEG
    bool canSave = image.CanSave(saveOptions);
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


