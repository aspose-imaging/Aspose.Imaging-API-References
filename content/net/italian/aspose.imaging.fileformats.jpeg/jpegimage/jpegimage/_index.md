---
title: JpegImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diJpegImageaspose.imaging.fileformats.jpeg/jpegimage classe.
type: docs
weight: 10
url: /it/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

Inizializza una nuova istanza di[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare l'immagine e inizializzare i dati di pixel e tavolozza con. |

### Esempi

L'esempio mostra come caricare un JpegImage da un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine JPEG da un file.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Esegui un po' di elaborazione delle immagini.
    // Salva in un altro file JPEG.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Guarda anche

* class [JpegImage](../../jpegimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assemblea [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

Inizializza una nuova istanza di[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare l'immagine e inizializzare i dati di pixel e tavolozza con. |

### Esempi

L'esempio mostra come caricare un JpegImage da un flusso di file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine JPEG da un flusso di file.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // Esegui un po' di elaborazione delle immagini.
        // Salva in un altro file JPEG.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### Guarda anche

* class [JpegImage](../../jpegimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assemblea [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

Inizializza una nuova istanza di[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(RasterImage rasterImage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine con cui inizializzare i dati di pixel e tavolozza. |

### Esempi

L'esempio mostra come caricare una JpegImage da un'altra RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine JPEG da un'altra immagine raster.
// Innanzitutto, crea un'immagine PNG temporale che sarà una base per la creazione di un'immagine JPEG.
// Puoi anche caricare un'immagine PNG da un file o utilizzare un'immagine di qualsiasi altro formato raster.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Riempi di rosso l'intera immagine PNG.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // Crea un'immagine JPEG basata sull'immagine PNG.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // Salva in un file JPEG
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assemblea [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

Inizializza una nuova istanza di[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine. |
| height | Int32 | L'altezza dell'immagine. |

### Esempi

L'esempio seguente mostra come creare un'immagine JPEG della dimensione specificata.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // Esegui un po' di elaborazione delle immagini.
    // Salva in un file.
    jpegImage.Save(dir + "output.jpg");
}
```

L'esempio seguente carica un'immagine BMP e la salva in JPEG utilizzando varie opzioni di salvataggio.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Esegui un po' di elaborazione delle immagini.

    // Usa opzioni aggiuntive per specificare i parametri dell'immagine desiderati.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Il numero di bit per canale è 8.
    // Quando si utilizza una tavolozza, l'indice del colore viene memorizzato nei dati dell'immagine invece del colore stesso.
    saveOptions.BitsPerChannel = 8;

    // Imposta il tipo progressivo di compressione.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
    saveOptions.Quality = 100;

    // Imposta la risoluzione orizzontale/verticale su 96 punti per pollice.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Se l'immagine di origine è colorata, verrà convertita in scala di grigi.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Usa una tavolozza per ridurre le dimensioni dell'output.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

### Guarda anche

* class [JpegImage](../../jpegimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assemblea [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

Inizializza una nuova istanza di[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| jpegOptions | JpegOptions | Le opzioni jpeg. |
| width | Int32 | Larghezza immagine. |
| height | Int32 | Altezza immagine. |

### Esempi

L'esempio seguente carica un'immagine BMP e la salva in JPEG utilizzando varie opzioni di salvataggio.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Esegui un po' di elaborazione delle immagini.

    // Usa opzioni aggiuntive per specificare i parametri dell'immagine desiderati.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Il numero di bit per canale è 8.
    // Quando si utilizza una tavolozza, l'indice del colore viene memorizzato nei dati dell'immagine invece del colore stesso.
    saveOptions.BitsPerChannel = 8;

    // Imposta il tipo progressivo di compressione.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
    saveOptions.Quality = 100;

    // Imposta la risoluzione orizzontale/verticale su 96 punti per pollice.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Se l'immagine di origine è colorata, verrà convertita in scala di grigi.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Usa una tavolozza per ridurre le dimensioni dell'output.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

L'esempio seguente mostra come creare un'immagine JPEG della dimensione specificata con i parametri specificati.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
// Usa opzioni aggiuntive per specificare i parametri dell'immagine desiderati.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Il numero di bit per canale è 8, 8, 8 per i componenti Y, Cr, Cb di conseguenza.
createOptions.BitsPerChannel = 8;

// Imposta il tipo progressivo di compressione.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
createOptions.Quality = 100;

// Imposta la risoluzione orizzontale/verticale su 96 punti per pollice.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Questa è un'opzione standard per le immagini JPEG.
// Due componenti di crominanza (Cb e Cr) possono essere ridotti, sottocampionati e compressi.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Riempi l'immagine con una sfumatura in scala di grigi
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Salva in un file.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Guarda anche

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
