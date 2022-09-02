---
title: WebPImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diWebPImageaspose.imaging.fileformats.webp/webpimage classe dallo stream.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe dallo stream.

```csharp
public WebPImage(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | L'immagine WebP del flusso. |

### Esempi

Questo esempio mostra come caricare un'immagine WebP da un flusso di file e salvarla in PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine WebP da un flusso di file.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // Salva in PNG
    // Nota che solo il frame attivo verrà archiviato in PNG, poiché PNG non è un formato multipagina.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe dallo stream.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | L'immagine WebP del flusso. |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Guarda anche

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe dal file.

```csharp
public WebPImage(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso del file Immagine WebP |

### Esempi

Questo esempio mostra come caricare un'immagine WebP da un file e salvarla in PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine WebP da un file.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Salva in PNG
    // Nota che solo il frame attivo verrà archiviato in PNG, poiché PNG non è un formato multipagina.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe dal file.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso del file Immagine WebP |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Guarda anche

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe da immagine raster.

```csharp
public WebPImage(RasterImage rasterImage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine raster. |

### Esempi

Questo esempio mostra come creare un'immagine WebP da un'altra immagine raster.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine PNG di 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Riempi di rosso l'intera immagine.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Crea un'immagine WebP basata sull'immagine PNG.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Salva in un file WebP con le opzioni predefinite
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe da immagine raster.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine raster. |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe con immagine vuota.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine |
| height | Int32 | L'altezza dell'immagine. |
| options | WebPOptions | Le opzioni. |

### Esempi

Questo esempio mostra come creare da zero un'immagine WebP con le opzioni specificate.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// Crea un'immagine WebP di 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Riempi di rosso l'intera immagine.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // Salva in un file WebP
    webPImage.Save(dir + "output.webp");
}
```

Questo esempio mostra come creare un'immagine WebP animata a più fotogrammi con le opzioni specificate.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Il frame predefinito più 36 + 36 frame aggiuntivi.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Crea un'immagine WebP di 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Il primo cerchio è rosso
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Il secondo cerchio è nero
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente l'angolo della forma dell'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Salva in un file WebP
    webPImage.Save(dir + "output.webp");
}
```

### Guarda anche

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Inizializza una nuova istanza di[`WebPImage`](../../webpimage) classe con immagine vuota.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine |
| height | Int32 | L'altezza dell'immagine. |
| options | WebPOptions | Le opzioni. |
| loadOptions | LoadOptions | Le opzioni di carico. |

### Guarda anche

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
