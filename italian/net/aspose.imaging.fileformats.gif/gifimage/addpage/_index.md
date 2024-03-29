---
title: AddPage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Aggiunge la pagina allimmagine.
type: docs
weight: 220
url: /it/net/aspose.imaging.fileformats.gif/gifimage/addpage/
---
## GifImage.AddPage method

Aggiunge la pagina all'immagine.

```csharp
public void AddPage(RasterImage page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | RasterImage | La pagina da aggiungere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *page* è zero. |

### Esempi

Crea immagini GIF multipagina utilizzando immagini raster a pagina singola.

```csharp
[C#]

static void Main(string[] args)
{
    // Carica fotogrammi
    var frames = LoadFrames("Animation frames").ToArray();

    // Crea un'immagine GIF usando il primo fotogramma
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Aggiungi cornici all'immagine GIF usando il metodo AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Salva l'immagine GIF
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

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifImage](../../gifimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
