---
title: StreamSource
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diStreamSourceaspose.imaging.sources/streamsource classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Inizializza una nuova istanza di[`StreamSource`](../../streamsource) classe.

```csharp
public StreamSource(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da aprire. |

### Esempi

Questo esempio mostra come caricare le informazioni sui pixel in una matrice di tipo colore, manipolare la matrice e reimpostarla sull'immagine. Per eseguire queste operazioni, questo esempio crea un nuovo file immagine (in formato GIF) utilizzando l'oggetto MemoryStream.

```csharp
[C#]

//Crea un'istanza di MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea un'istanza di GifOptions e imposta le sue varie proprietà inclusa la proprietà Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crea un'istanza di Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Ottieni i pixel dell'immagine specificando l'area come limite dell'immagine
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Cicla sull'array e imposta il colore del pixel indicizzato alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Imposta il colore del pixel indicizzato su giallo
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Imposta il colore del pixel indicizzato su blu
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Applica le modifiche ai pixel all'immagine
        image.SavePixels(image.Bounds, pixels);

        // salva tutte le modifiche.
        image.Save();
    }

    // Scrivi MemoryStream su file
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Guarda anche

* class [StreamSource](../../streamsource)
* spazio dei nomi [Aspose.Imaging.Sources](../../streamsource)
* assemblea [Aspose.Imaging](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Inizializza una nuova istanza di[`StreamSource`](../../streamsource) classe.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da aprire. |
| disposeStream | Boolean | se impostato su`VERO` il flusso sarà smaltito. |

### Esempi

Questo esempio mostra l'uso di System.IO.Stream per creare un nuovo file immagine (un tipo JPEG)

```csharp
[C#]

//Crea un'istanza di JpegOptions e ne imposta le varie proprietà
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Crea un'istanza di System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Definisce la proprietà di origine per l'istanza di JpegOptions
//Il secondo parametro booleano determina se lo Stream viene eliminato una volta uscito dall'ambito
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//Crea un'istanza di Image e chiama il metodo Create con JpegOptions come parametro per inizializzare l'oggetto Image   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //eseguo un po' di elaborazione delle immagini
}
```

### Guarda anche

* class [StreamSource](../../streamsource)
* spazio dei nomi [Aspose.Imaging.Sources](../../streamsource)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
