---
title: MakerNote
second_title: Aspose.Imaging لمرجع NET API
description: يمثل سجل واحد لملاحظات Maker .
type: docs
weight: 1100
url: /ar/net/aspose.imaging.exif/makernote/
---
## MakerNote class

يمثل سجل واحد لملاحظات Maker .

```csharp
public class MakerNote
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Name](../../aspose.imaging.exif/makernote/name) { get; } | الحصول على اسم الإعداد . |
| [Value](../../aspose.imaging.exif/makernote/value) { get; } | يحصل على قيمة الإعداد . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [ToString](../../aspose.imaging.exif/makernote/tostring)() | تحويل المثيل إلى سلسلة . |

### أمثلة

الوصول إلى ملاحظات صانع الكاميرا في صورة Jpeg.

```csharp
[C#]

using (var image = (JpegImage)Image.Load("Sample.jpg"))
{
    foreach (var makerNote in image.ExifData.MakerNotes)
    {
        Console.WriteLine("Name = {0}, Value = {1}", makerNote.Name, makerNote.Value);
    }
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.Exif](../../aspose.imaging.exif)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->