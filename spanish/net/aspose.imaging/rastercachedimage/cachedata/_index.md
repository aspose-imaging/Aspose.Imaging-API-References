---
title: CacheData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.DataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 80
url: /es/net/aspose.imaging/rastercachedimage/cachedata/
---
## RasterCachedImage.CacheData method

Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../../datastreamsupporter/datastreamcontainer) .

```csharp
public override void CacheData()
```

### Ejemplos

El siguiente ejemplo muestra cómo el almacenamiento en caché de imágenes ráster afecta el rendimiento. En el caso general, la lectura de datos almacenados en caché se realiza más rápido que la lectura de datos no almacenados en caché.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen desde un archivo PNG.
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Almacenar en caché todos los datos de píxeles para que no se realice ninguna carga de datos adicional desde el flujo de datos subyacente
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Leer todos los píxeles es bastante rápido.
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = image.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Cargar una imagen desde un archivo PNG
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Leer todos los píxeles no es tan rápido como cuando se almacena en caché
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = image.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// La salida puede verse así:
// La lectura de todos los píxeles almacenados en caché tomó 1500 ms.
// La lectura de todos los píxeles sin almacenamiento en caché preliminar tomó 150000 ms.
```

### Ver también

* class [RasterCachedImage](../../rastercachedimage)
* espacio de nombres [Aspose.Imaging](../../rastercachedimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->