---
title: CacheData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostanteDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 120
url: /it/net/aspose.imaging.fileformats.cmx/cmximage/cachedata/
---
## CmxImage.CacheData method

Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer) .

```csharp
public override void CacheData()
```

### Esempi

L'esempio seguente mostra come memorizzare nella cache tutte le pagine di un'immagine CMX.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine da un file CMX.
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // Questa chiamata memorizza nella cache solo la pagina predefinita.
    image.CacheData();

    // Memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento di dati aggiuntivo dal flusso di dati sottostante.
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Guarda anche

* class [CmxImage](../../cmximage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Cmx](../../cmximage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
