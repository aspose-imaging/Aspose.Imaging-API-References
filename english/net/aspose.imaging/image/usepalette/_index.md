---
title: Image.UsePalette
second_title: Aspose.Imaging for .NET API Reference
description: Image property. Gets a value indicating whether the image palette is used
type: docs
weight: 170
url: /net/aspose.imaging/image/usepalette/
---
## Image.UsePalette property

Gets a value indicating whether the image palette is used.

```csharp
public virtual bool UsePalette { get; }
```

### Property Value

`true` if the palette is used in the image; otherwise, `false`.

## Examples

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

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


