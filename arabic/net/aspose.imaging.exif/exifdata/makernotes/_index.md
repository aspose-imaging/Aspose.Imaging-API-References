---
title: "ExifData.MakerNotes"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية ExifData. يحصل على ملاحظات الصانع"
type: docs
weight: 820
url: /ar/net/aspose.imaging.exif/exifdata/makernotes/
---
## ExifData.MakerNotes property

يحصل على ملاحظات الصانع.

```csharp
public MakerNote[] MakerNotes { get; }
```

### Property Value

ملاحظات الصانع.

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

* class [MakerNote](../../makernote/)
* class [ExifData](../)
* namespace [Aspose.Imaging.Exif](../../exifdata/)
* assembly [Aspose.Imaging](../../../)


