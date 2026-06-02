---
title: "الفئة MakerNote"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Exif.MakerNote. تمثل سجل Maker Note واحد"
type: docs
weight: 1130
url: /ar/net/aspose.imaging.exif/makernote/
---
## MakerNote class

تمثل سجل ملاحظة صانع واحد.

```csharp
public class MakerNote
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Name](../../aspose.imaging.exif/makernote/name/) { get; } | يحصل على اسم الإعداد. |
| [Value](../../aspose.imaging.exif/makernote/value/) { get; } | يحصل على قيمة الإعداد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ToString](../../aspose.imaging.exif/makernote/tostring/)() | يحوّل الكائن إلى سلسلة. |

## أمثلة

الوصول إلى ملاحظات الصانع للكاميرا في صورة JPEG.

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

### انظر أيضًا

* namespace [Aspose.Imaging.Exif](../../aspose.imaging.exif/)
* assembly [Aspose.Imaging](../../)


