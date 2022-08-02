---
title: GetEmbeddedImages
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene las imágenes incrustadas.
type: docs
weight: 60
url: /es/net/aspose.imaging/vectorimage/getembeddedimages/
---
## VectorImage.GetEmbeddedImages method

Obtiene las imágenes incrustadas.

```csharp
public virtual EmbeddedImage[] GetEmbeddedImages()
```

### Valor_devuelto

Matriz de imágenes

### Ejemplos

Admite la extracción de imágenes rasterizadas incrustadas a partir de una imagen vectorial

```csharp
[C#]

var inputFileName = "test.cdr";
using (var image = Aspose.Imaging.Image.Load(inputFileName))        
{
    var vectorImage = ((Aspose.Imaging.VectorImage) image);
    var images = vectorImage.GetEmbeddedImages();
    var i = 0;
    foreach (var im in images)
    {
        var outFileName = string.Format("image{0}.png", i++);
        using (im)
        {
            im.Image.Save(outFileName, new PngOptions());
        }
    }
}
```

### Ver también

* class [EmbeddedImage](../../embeddedimage)
* class [VectorImage](../../vectorimage)
* espacio de nombres [Aspose.Imaging](../../vectorimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->