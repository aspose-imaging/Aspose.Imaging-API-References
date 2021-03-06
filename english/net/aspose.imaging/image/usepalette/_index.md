---
title: UsePalette
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 150
url: /net/aspose.imaging/image/usepalette/
---
## Image.UsePalette property

Gets a value indicating whether the image palette is used.

```csharp
public virtual bool UsePalette { get; }
```

### Property Value

`true` if the palette is used in the image; otherwise, `false`.

### Examples

Determine if the palette is used by the image.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

### See Also

* class [Image](../../image)
* namespace [Aspose.Imaging](../../image)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
