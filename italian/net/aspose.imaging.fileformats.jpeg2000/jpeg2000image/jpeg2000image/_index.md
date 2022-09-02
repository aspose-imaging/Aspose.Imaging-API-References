---
title: Jpeg2000Image
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza. |

### Esempi

Questo esempio mostra come caricare un'immagine JPEG2000 da un file e salvarla in PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine JPEG2000.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // Salva in PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza |
| bitsPerPixel | Int32 | I bit per pixel. |

### Guarda anche

* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza. |

### Esempi

Questo esempio mostra come caricare un'immagine JPEG2000 da un flusso di file e salvarla in PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine JPEG2000 dallo stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // Salva in PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza. |
| bitsPerPixel | Int32 | I bit per pixel. |

### Guarda anche

* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine |
| height | Int32 | L'altezza dell'immagine |

### Esempi

Questo esempio mostra come creare un'immagine JPEG2000 e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine JPEG2000 di 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Riempi di rosso l'intera immagine.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Salva in un file
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### Guarda anche

* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine |
| height | Int32 | L'altezza dell'immagine |
| options | Jpeg2000Options | Le opzioni. |

### Esempi

Questo esempio mostra come creare un'immagine PNG e salvarla in JPEG2000 con le opzioni desiderate.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Riempi di rosso l'intera immagine.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // Usa la trasformazione Wavelet discreta 9-7
    saveOptions.Irreversible = true;

    // JP2 è il formato "contenitore" per i codestream JPEG 2000.
    // J2K sono dati compressi grezzi, senza un wrapper.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // Salva in un file
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

Questo esempio mostra come creare un'immagine JPEG2000 con le opzioni desiderate e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// Usa la trasformazione Wavelet discreta 9-7
createOptions.Irreversible = true;

// JP2 è il formato "contenitore" per i codestream JPEG 2000.
// J2K sono dati compressi grezzi, senza un wrapper.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// Crea un'immagine JPEG2000 di 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Riempi di rosso l'intera immagine.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Salva in un file
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### Guarda anche

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine |
| height | Int32 | L'altezza dell'immagine |
| bitsCount | Int32 | I bit contano. |

### Guarda anche

* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine. |

### Esempi

Questo esempio mostra come creare un'immagine JPEG2000 da un'altra immagine raster.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Riempi di rosso l'intera immagine.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Crea un'immagine JPEG2000 basata sull'immagine PNG.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // Salva in un file
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Inizializza una nuova istanza di[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine con cui inizializzare i dati di pixel e tavolozza. |
| bitsPerPixel | Int32 | I bit per pixel. |

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* spazio dei nomi [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
