---
title: DjvuImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diDjvuImageaspose.imaging.fileformats.djvu/djvuimage classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.djvu/djvuimage/djvuimage/
---
## DjvuImage(Stream) {#constructor}

Inizializza una nuova istanza di[`DjvuImage`](../../djvuimage) classe.

```csharp
public DjvuImage(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception) | Il flusso è vuoto |

### Esempi

Questo esempio mostra come caricare un'immagine DJVU da un flusso di file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso di file.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // Salva ogni pagina come una singola immagine PNG.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Genera un nome file in base al numero di pagina.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Guarda anche

* class [DjvuImage](../../djvuimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* assemblea [Aspose.Imaging](../../../)

---

## DjvuImage(Stream, LoadOptions) {#constructor_1}

Inizializza una nuova istanza di[`DjvuImage`](../../djvuimage) classe.

```csharp
public DjvuImage(Stream stream, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare. |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception) | Il flusso è vuoto |

### Esempi

Questo esempio mostra come caricare un'immagine DJVU da un flusso di file per rimanere entro il limite di memoria specificato.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso di file.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    // La dimensione massima consentita per tutti i buffer interni è 1 MB.
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 1 * 1024 * 1024;

    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream, loadOptions))
    {
        // Salva ogni pagina come una singola immagine PNG.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Genera un nome file in base al numero di pagina.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Guarda anche

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [DjvuImage](../../djvuimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
