---
title: Image.CanSave
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Determines whether image can be saved to the specified file format represented by the passed save options
type: docs
weight: 200
url: /net/aspose.imaging/image/cansave/
---
## Image.CanSave method

Determines whether image can be saved to the specified file format represented by the passed save options.

```csharp
public bool CanSave(ImageOptionsBase options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ImageOptionsBase | The save options to use. |

### Return Value

`true` if image can be saved to the specified file format represented by the passed save options; otherwise, `false`.

## Examples

This example shows how to determine whether image can be saved to the specified file format represented by the passed save options.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
    saveOptions.Quality = 50;

    // Determine whether the image can be saved to Jpeg
    bool canSave = image.CanSave(saveOptions);
}
```

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


