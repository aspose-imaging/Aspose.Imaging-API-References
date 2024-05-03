---
title: Class MakerNote
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Exif.MakerNote class. Represents a single Maker Note record
type: docs
weight: 1100
url: /net/aspose.imaging.exif/makernote/
---
## MakerNote class

Represents a single Maker Note record.

```csharp
public class MakerNote
```

## Properties

| Name | Description |
| --- | --- |
| [Name](../../aspose.imaging.exif/makernote/name/) { get; } | Gets the setting name. |
| [Value](../../aspose.imaging.exif/makernote/value/) { get; } | Gets the setting value. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.imaging.exif/makernote/tostring/)() | Converts the instance to string. |

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

* namespace [Aspose.Imaging.Exif](../../aspose.imaging.exif/)
* assembly [Aspose.Imaging](../../)


