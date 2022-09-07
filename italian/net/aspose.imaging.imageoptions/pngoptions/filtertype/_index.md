---
title: FilterType
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png.
type: docs
weight: 50
url: /it/net/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png.

```csharp
public PngFilterType FilterType { get; set; }
```

### Esempi

Questo esempio mostra come creare un'immagine PNG con le opzioni specificate, riempirla con colori sfumati lineari e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Il numero di bit per canale colore
createOptions.BitDepth = 8;

// Ogni pixel è una tripla (rossa, verde, blu) seguita dalla componente alfa.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Il livello massimo di compressione.
createOptions.CompressionLevel = 9;

// L'uso dei filtri consente di comprimere le immagini tonali continue in modo più efficace.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Usa il caricamento progressivo
createOptions.Progressive = true;

// Crea un'immagine PNG con parametri personalizzati.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Riempi l'immagine con un gradiente semitrasparente.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Salva in un file.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

L'esempio seguente mostra come diversi tipi di filtro influiscono sulla dimensione dell'immagine PNG di output.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Imposta un tipo di filtro
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//L'output potrebbe essere simile a questo:
//Il tipo di filtro è Nessuno, la dimensione dell'immagine di output è 116845 byte.
//Il tipo di filtro è Su, la dimensione dell'immagine di output è 86360 byte.
//Il tipo di filtro è Sub, la dimensione dell'immagine di output è 94907 byte.
//Il tipo di filtro è Paeth, la dimensione dell'immagine di output è 86403 byte.
//Il tipo di filtro è Avg, la dimensione dell'immagine di output è 89956 byte.
//Il tipo di filtro è Adaptive, la dimensione dell'immagine di output è 97248 byte.
```

L'esempio seguente mostra come salvare un'immagine in formato PNG utilizzando varie opzioni.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
// Puoi anche caricare un'immagine di qualsiasi formato supportato da un file o da un flusso.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Riempi l'immagine con il gradiente blu-trasparente.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Caricamento progressivo.
    saveOptions.Progressive = true;

    // Imposta la risoluzione orizzontale e verticale su 96 pixel per pollice.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Ogni pixel è una tripla (rossa, verde, blu) seguita da alfa.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Imposta il livello massimo di compressione.
    saveOptions.CompressionLevel = 9;

    // Questa è la compressione migliore, ma il tempo di esecuzione più lento.
    // Il filtro adattivo significa che il processo di salvataggio sceglierà il filtro più adatto per ogni riga di dati.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // Il numero di bit per canale.
    saveOptions.BitDepth = 8;

    // Salva in un file.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Guarda anche

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../pngoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
