---
title: Image.IsIndexed
second_title: Aspose.Imaging for .NET API Reference
description: Image property. Gets a value indicating whether the image has indexed pixel type and uses a color palette
type: docs
weight: 140
url: /net/aspose.imaging/image/isindexed/
---
## Image.IsIndexed property

Gets a value indicating whether the image has indexed pixel type and uses a color palette.

```csharp
public virtual bool IsIndexed { get; }
```

## Examples

Determine if the palette is used by the image.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.IsIndexed)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


