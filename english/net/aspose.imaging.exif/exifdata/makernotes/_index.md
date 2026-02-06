---
title: ExifData.MakerNotes
second_title: Aspose.Imaging for .NET API Reference
description: ExifData property. Gets the maker notes
type: docs
weight: 820
url: /net/aspose.imaging.exif/exifdata/makernotes/
---
## ExifData.MakerNotes property

Gets the maker notes.

```csharp
public MakerNote[] MakerNotes { get; }
```

### Property Value

The maker notes.

## Examples

Access camera manufacturer maker notes in Jpeg image.

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

### See Also

* class [MakerNote](../../makernote/)
* class [ExifData](../)
* namespace [Aspose.Imaging.Exif](../../exifdata/)
* assembly [Aspose.Imaging](../../../)


