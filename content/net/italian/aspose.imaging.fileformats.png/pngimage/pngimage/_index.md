---
title: PngImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diPngImageaspose.imaging.fileformats.png/pngimage classe.
type: docs
weight: 10
url: /it/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza. |
| height | Int32 | L'altezza. |

### Esempi

Questo esempio mostra come creare un'immagine PNG della dimensione specificata, riempirla con un colore solido e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // Esegui un po' di elaborazione delle immagini, ad esempio riempi l'intera immagine in rosso.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Salva in un file.
    pngImage.Save(dir + "output.png");
}
```

### Guarda anche

* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso per caricare un'immagine. |

### Esempi

Questo esempio mostra come caricare un'immagine PNG da un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine PNG da un file.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Trasforma l'immagine in una rappresentazione in scala di grigi
    pngImage.Grayscale();

    // Salva in un file.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Guarda anche

* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(RasterImage rasterImage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine raster. |

### Esempi

Questo esempio mostra come caricare un'immagine PNG da un'immagine BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine PNG TrueColor da un'immagine BMP.
// Innanzitutto, crea un'immagine BMP temporale che sarà una base per la creazione di un'immagine PNG.
// Puoi anche caricare un'immagine BMP da un file o utilizzare un'immagine di qualsiasi altro formato raster.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Riempi di rosso l'intera immagine BMP.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(string path, PngColorType colorType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso per caricare un'immagine. |
| colorType | PngColorType | Il tipo di colore. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException |  |

### Esempi

Questo esempio mostra come caricare un'immagine PNG da un file con il tipo di colore specificato.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine PNG da un file.
// Nota che l'immagine colorata verrà automaticamente convertita in scala di grigi.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Salva in un file.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Guarda anche

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine raster. |
| colorType | PngColorType | Il tipo di colore. |

### Esempi

Questo esempio mostra come caricare un'immagine PNG da un'immagine BMP con il tipo di colore specificato.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine PNG in scala di grigi da un'immagine BMP colorata.
// Innanzitutto, crea un'immagine BMP temporale che sarà una base per la creazione di un'immagine PNG.
// Puoi anche caricare un'immagine BMP da un file o utilizzare un'immagine di qualsiasi altro formato raster.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Riempi di rosso l'intera immagine BMP.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // I colori dei pixel dell'immagine verranno convertiti nelle loro controparti in scala di grigi.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso per caricare un'immagine. |

### Esempi

Questo esempio mostra come caricare un'immagine PNG da un file o da un flusso di file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine PNG da un flusso di file.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // Trasforma l'immagine in una rappresentazione in scala di grigi
        pngImage.Grayscale();

        // Salva in un file.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### Guarda anche

* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza. |
| height | Int32 | L'altezza. |
| colorType | PngColorType | Il tipo di colore. |

### Esempi

Questo esempio mostra come creare un'immagine PNG della dimensione specificata con il tipo di colore specificato, riempirla con un colore solido e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine PNG in scala di grigi di 100x100 px.
// Tutti i colori verranno automaticamente convertiti nel formato in scala di grigi.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Esegui un po' di elaborazione delle immagini, ad esempio riempi l'intera immagine in rosso.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Salva in un file.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### Guarda anche

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

Inizializza una nuova istanza di[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pngOptions | PngOptions | Le opzioni png. |
| width | Int32 | La larghezza. |
| height | Int32 | L'altezza. |

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

### Guarda anche

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
