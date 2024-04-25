---
title: TiffFrame
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diTiffFrameaspose.imaging.fileformats.tiff/tiffframe classe.
type: docs
weight: 10
url: /it/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

Inizializza una nuova istanza di[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |

### Guarda anche

* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

Inizializza una nuova istanza di[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |
| options | TiffOptions | Le opzioni da utilizzare per la cornice appena creata. |

### Guarda anche

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

Inizializza una nuova istanza di[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |

### Guarda anche

* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

Inizializza una nuova istanza di[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(string path, TiffOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare un'immagine e con cui inizializzare i pixel del frame e i dati della tavolozza. |
| options | TiffOptions | Le opzioni da utilizzare per la cornice appena creata. |

### Guarda anche

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

Inizializza una nuova istanza di[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(RasterImage image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine con cui inizializzare i pixel del frame e i dati della tavolozza. |

### Esempi

L'esempio seguente mostra come comporre un TIFF multipagina da singole immagini raster.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Questo è Font e Brush per disegnare il testo su singole cornici.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // Crea 5 frame
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Crea un'immagine PNG e disegna il numero di pagine su di essa.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Crea una cornice basata sull'immagine PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Aggiunge la cornice all'immagine TIFF.
        tiffImage.AddFrame(frame);
    }

    // L'immagine è stata creata con un unico frame predefinito. Rimuoviamolo.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // Non dimenticare di eliminare il frame se non lo vuoi aggiungere a qualche altro TiffImage
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

Inizializza una nuova istanza di[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine con cui inizializzare i pixel del frame e i dati della tavolozza. |
| options | TiffOptions | Le opzioni da utilizzare per la cornice appena creata. |

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

Inizializza una nuova istanza di[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | TiffOptions | Le opzioni della cornice. |
| width | Int32 | La larghezza. |
| height | Int32 | L'altezza. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Il parametro Opzioni è nullo. |

### Esempi

Questo esempio mostra come creare un'immagine TIFF da zero e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Imposta 8 bit per ogni componente di colore.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Imposta l'ordine dei byte Big Endian (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Imposta la compressione LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Imposta il modello di colore RGB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tutti i componenti del colore verranno archiviati su un unico piano.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crea una cornice TIFF di 100x100 px.
// Nota che non devi eliminare un frame in modo esplicito se è incluso in TiffImage.
// Quando il contenitore viene eliminato, tutti i frame verranno eliminati automaticamente.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Riempi l'intero fotogramma con il gradiente blu-giallo.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Crea un'immagine TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

Questo esempio mostra come creare un'immagine TIFF con 2 fotogrammi e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Opzioni per il primo fotogramma
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Imposta 8 bit per ogni componente di colore.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Imposta l'ordine dei byte Big Endian (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Imposta la compressione LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Imposta il modello di colore RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tutti i componenti del colore verranno archiviati su un unico piano.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crea la prima cornice TIFF di 100x100 px.
// Nota che non devi eliminare i frame in modo esplicito se sono inclusi in TiffImage.
// Quando il contenitore viene eliminato, tutti i frame verranno eliminati automaticamente.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Riempi il primo fotogramma con il gradiente blu-giallo.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Opzioni per il primo fotogramma
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Imposta 1 bit per pixel per un'immagine in bianco e nero.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Imposta l'ordine dei byte di Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Imposta la compressione del fax CCITT Gruppo 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Imposta il modello di colore B/N dove 0 è nero, 1 è bianco.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Crea il secondo frame TIFF di 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Riempi il secondo fotogramma con il gradiente blu-giallo.
// Verrà automaticamente convertito nel formato B/N a causa delle impostazioni corrispondenti della cornice.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Crea un'immagine TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Guarda anche

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
