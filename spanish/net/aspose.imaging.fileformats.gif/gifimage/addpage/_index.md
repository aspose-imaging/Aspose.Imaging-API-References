---
title: AddPage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Agrega página a la imagen.
type: docs
weight: 220
url: /es/net/aspose.imaging.fileformats.gif/gifimage/addpage/
---
## GifImage.AddPage method

Agrega página a la imagen.

```csharp
public void AddPage(RasterImage page)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | RasterImage | La página para agregar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *page* es nulo. |

### Ejemplos

Cree una imagen GIF de varias páginas usando imágenes rasterizadas de una sola página.

```csharp
[C#]

static void Main(string[] args)
{
    // Cargar fotogramas
    var frames = LoadFrames("Animation frames").ToArray();

    // Crea una imagen GIF usando el primer cuadro
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Agrega marcos a la imagen GIF usando el método AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Guardar imagen GIF
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifImage](../../gifimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
