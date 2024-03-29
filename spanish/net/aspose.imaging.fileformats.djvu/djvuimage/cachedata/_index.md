---
title: CacheData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Guarda en caché los datos privados.
type: docs
weight: 210
url: /es/net/aspose.imaging.fileformats.djvu/djvuimage/cachedata/
---
## DjvuImage.CacheData method

Guarda en caché los datos privados.

```csharp
public override void CacheData()
```

### Ejemplos

El siguiente ejemplo muestra cómo almacenar en caché todas las páginas de una imagen DJVU.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen desde un archivo DJVU.
using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Esta llamada almacena en caché todas las páginas para que no se realice ninguna carga de datos adicional desde el flujo de datos subyacente.
    image.CacheData();

    // O puede almacenar en caché las páginas individualmente.
    foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Ver también

* class [DjvuImage](../../djvuimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
