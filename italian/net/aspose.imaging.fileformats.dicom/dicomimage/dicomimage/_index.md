---
title: DicomImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diDicomImageaspose.imaging.fileformats.dicom/dicomimage classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.dicom/dicomimage/dicomimage/
---
## DicomImage(DicomOptions, int, int) {#constructor}

Inizializza una nuova istanza di[`DicomImage`](../../dicomimage) classe.

```csharp
public DicomImage(DicomOptions dicomOptions, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dicomOptions | DicomOptions | Le opzioni dicom. |
| width | Int32 | La larghezza. |
| height | Int32 | L'altezza. |

### Guarda anche

* class [DicomOptions](../../../aspose.imaging.imageoptions/dicomoptions)
* class [DicomImage](../../dicomimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* assemblea [Aspose.Imaging](../../../)

---

## DicomImage(Stream, LoadOptions) {#constructor_2}

Inizializza una nuova istanza di[`DicomImage`](../../dicomimage) classe.

```csharp
public DicomImage(Stream stream, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Esempi

Questo esempio mostra come caricare un'immagine DICOM da un flusso di file per rimanere entro il limite di memoria specificato.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine DICOM da un flusso di file.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    // La dimensione massima consentita per tutti i buffer interni è 256 KB.
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 256 * 1024;

    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream, loadOptions))
    {
        // Salva ogni pagina come una singola immagine PNG.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Genera un nome file basato sull'indice della pagina.
            string fileName = string.Format("multiframe.{0}.png", dicomPage.Index);

            // Una pagina DICOM è un'immagine raster, quindi tutte le operazioni consentite con un'immagine raster sono applicabili a una pagina DICOM.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Guarda anche

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [DicomImage](../../dicomimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* assemblea [Aspose.Imaging](../../../)

---

## DicomImage(Stream) {#constructor_1}

Inizializza una nuova istanza di[`DicomImage`](../../dicomimage) classe.

```csharp
public DicomImage(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |

### Esempi

Questo esempio mostra come caricare un'immagine DICOM da un flusso di file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine DICOM da un flusso di file.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Salva ogni pagina come una singola immagine PNG.                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Genera un nome file basato sull'indice della pagina.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // Una pagina DICOM è un'immagine raster, quindi tutte le operazioni consentite con un'immagine raster sono applicabili a una pagina DICOM.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Guarda anche

* class [DicomImage](../../dicomimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
