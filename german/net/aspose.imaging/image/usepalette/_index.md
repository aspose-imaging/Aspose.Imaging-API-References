---
title: UsePalette
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft einen Wert ab der angibt ob die Bildpalette verwendet wird.
type: docs
weight: 150
url: /de/net/aspose.imaging/image/usepalette/
---
## Image.UsePalette property

Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird.

```csharp
public virtual bool UsePalette { get; }
```

### Eigentumswert

`Stimmt` wenn die Palette im Bild verwendet wird; Andernfalls,`FALSCH` .

### Beispiele

Stellen Sie fest, ob die Palette vom Bild verwendet wird.

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

### Siehe auch

* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
