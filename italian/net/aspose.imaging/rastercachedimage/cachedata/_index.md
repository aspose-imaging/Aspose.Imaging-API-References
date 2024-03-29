---
title: CacheData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostanteDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 80
url: /it/net/aspose.imaging/rastercachedimage/cachedata/
---
## RasterCachedImage.CacheData method

Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../../datastreamsupporter/datastreamcontainer) .

```csharp
public override void CacheData()
```

### Esempi

L'esempio seguente mostra in che modo la memorizzazione nella cache delle immagini raster influisce sulle prestazioni. In generale, la lettura dei dati memorizzati nella cache viene eseguita più velocemente rispetto alla lettura dei dati non memorizzati nella cache.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine da un file PNG.
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Memorizza nella cache tutti i dati dei pixel in modo che non venga eseguito alcun caricamento di dati aggiuntivo dal flusso di dati sottostante
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // La lettura di tutti i pixel è piuttosto veloce.
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

// Carica un'immagine da un file PNG
using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // La lettura di tutti i pixel non è veloce come durante la memorizzazione nella cache
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

// L'output potrebbe essere simile a questo:
// La lettura di tutti i pixel nella cache ha richiesto 1500 ms.
// La lettura di tutti i pixel senza cache preliminare ha richiesto 150000 ms.
```

### Guarda anche

* class [RasterCachedImage](../../rastercachedimage)
* spazio dei nomi [Aspose.Imaging](../../rastercachedimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
