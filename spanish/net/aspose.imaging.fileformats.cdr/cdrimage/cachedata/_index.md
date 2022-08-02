---
title: CacheData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el subyacente DataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 110
url: /es/net/aspose.imaging.fileformats.cdr/cdrimage/cachedata/
---
## CdrImage.CacheData method

Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el subyacente [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer) .

```csharp
public override void CacheData()
```

### Ejemplos

El siguiente ejemplo muestra cómo almacenar en caché todas las páginas de una imagen CDR.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen desde un archivo CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // Esta llamada almacena en caché solo la página predeterminada.
    image.CacheData();

    // Almacenar en caché todas las páginas para que no se realice ninguna carga de datos adicional desde el flujo de datos subyacente.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Ver también

* class [CdrImage](../../cdrimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Cdr](../../cdrimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->