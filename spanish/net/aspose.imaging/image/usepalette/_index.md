---
title: UsePalette
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene un valor que indica si se utiliza la paleta de imágenes.
type: docs
weight: 150
url: /es/net/aspose.imaging/image/usepalette/
---
## Image.UsePalette property

Obtiene un valor que indica si se utiliza la paleta de imágenes.

```csharp
public virtual bool UsePalette { get; }
```

### El valor de la propiedad

`verdadero` si la paleta se usa en la imagen; de lo contrario,`falso` .

### Ejemplos

Determine si la paleta es utilizada por la imagen.

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

### Ver también

* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->