---
title: BmpImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diBmpImageaspose.imaging.fileformats.bmp/bmpimage classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | l'immagine raster è nulla; immagine raster |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come caricare un BmpImage da un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
// I pixel di origine verranno convertiti nel formato a 32 bpp, se necessario.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Esegui un po' di elaborazione delle immagini.
    // Salva in un altro file BMP.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### Guarda anche

* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza. |
| bitsPerPixel | UInt16 | I bit per pixel. |
| compression | BitmapCompression | La compressione da usare. |
| horizontalResolution | Double | La risoluzione orizzontale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |
| verticalResolution | Double | La risoluzione verticale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'immagine raster non può essere null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come caricare un BmpImage da un file con la profondità di bit e la risoluzione specificate.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
// I pixel di origine verranno convertiti nel formato a 24 bpp, se necessario.
// La risoluzione sarà impostata su 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Esegui un po' di elaborazione delle immagini.
    // Salva in un altro file BMP.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### Guarda anche

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'immagine raster non può essere null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come caricare un BmpImage da un flusso di file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine BMP da un flusso di file.
// I pixel di origine verranno convertiti nel formato a 32 bpp, se necessario.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Esegui un po' di elaborazione delle immagini.
        // Salva in un altro file BMP.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### Guarda anche

* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare l'immagine e con cui inizializzare i dati di pixel e tavolozza. |
| bitsPerPixel | UInt16 | I bit per pixel. |
| compression | BitmapCompression | La compressione da usare. |
| horizontalResolution | Double | La risoluzione orizzontale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |
| verticalResolution | Double | La risoluzione verticale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'immagine raster non può essere null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come caricare un BmpImage da un flusso di file con la profondità di bit e la risoluzione specificate.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine BMP da un flusso di file.
// I pixel di origine verranno convertiti nel formato a 24 bpp, se necessario.
// La risoluzione sarà impostata su 96 dpi.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Esegui un po' di elaborazione delle immagini.
        // Salva in un altro file BMP.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### Guarda anche

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine con cui inizializzare i dati di pixel e tavolozza. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'immagine raster non può essere null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come caricare un BmpImage da un'altra istanza di RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una nuova immagine PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Riempi di rosso l'intera immagine PNG.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Crea un'immagine BMP basata sull'immagine PNG.
    // I pixel di origine verranno convertiti nel formato a 32 bpp, se necessario.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // Salva in un file BMP
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine con cui inizializzare i dati di pixel e tavolozza. |
| bitsPerPixel | UInt16 | I bit per pixel. |
| compression | BitmapCompression | La compressione da usare. |
| horizontalResolution | Double | La risoluzione orizzontale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |
| verticalResolution | Double | La risoluzione verticale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'immagine raster non può essere null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come caricare un BmpImage da un'altra istanza di RasterImage con la profondità di bit e la compressione specificate.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una nuova immagine PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Riempi di rosso l'intera immagine PNG.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Crea un'immagine BMP basata sull'immagine PNG.
    // I pixel di origine verranno convertiti nel formato a 24 bpp, se necessario.
    // La risoluzione sarà impostata su 96 dpi.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Salva in un file BMP
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine. |
| height | Int32 | L'altezza dell'immagine. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come creare un BmpImage della dimensione specificata.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine BMP a 32 bpp di 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Riempi di rosso l'intera immagine.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Salva in un file BMP
    bmpImage.Save(dir + "output.bmp");
}
```

L'esempio seguente mostra come pallettizzare un'immagine BMP per ridurne le dimensioni di output.

```csharp
[C#]

// Crea un'immagine BMP 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Il gradiente lineare dall'angolo in alto a sinistra all'angolo in basso a destra dell'immagine.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Riempi l'intera immagine con il pennello gradiente lineare.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Ottieni la tavolozza dei colori a 8 bit più vicina che copre il maggior numero di pixel possibile, in modo che un'immagine palettizzata
    // è quasi visivamente indistinguibile da uno non pallettizzato.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // La tavolozza a 8 bit contiene al massimo 256 colori.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// L'output è simile a questo:
// La dimensione dell'immagine pallettizzata è 11078 byte.
// La dimensione dell'immagine non palettizzata è 40054 byte.
```

### Guarda anche

* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine. |
| height | Int32 | L'altezza dell'immagine. |
| bitsPerPixel | UInt16 | I bit per pixel. |
| palette | IColorPalette | La tavolozza dei colori. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come creare un BmpImage della dimensione specificata con la tavolozza specificata.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Crea una tavolozza monocromatica che contenga solo i colori rosso e verde.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Crea un'immagine BMP monocromatica a 1 bpp di 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Riempi di rosso la metà superiore dell'immagine.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Riempi di verde la metà inferiore dell'immagine.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Salva su BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### Guarda anche

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

Inizializza una nuova istanza di[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine. |
| height | Int32 | L'altezza dell'immagine. |
| bitsPerPixel | UInt16 | I bit per pixel. |
| palette | IColorPalette | La tavolozza dei colori. |
| compression | BitmapCompression | La compressione da usare. |
| horizontalResolution | Double | La risoluzione orizzontale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |
| verticalResolution | Double | La risoluzione verticale. Nota a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella passata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | L'altezza dovrebbe essere positiva. |
| ArgumentException | La tavolozza deve essere specificata per le immagini con 8 bit per pixel o meno.; tavolozza |

### Esempi

L'esempio mostra come creare una BmpImage utilizzando varie opzioni.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Crea una tavolozza monocromatica che contenga solo i colori rosso e verde.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Crea un'immagine BMP monocromatica a 1 bpp di 100 x 100 px.
// La risoluzione orizzontale e verticale sarà impostata su 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Riempi di rosso la metà superiore dell'immagine.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Riempi di verde la metà inferiore dell'immagine.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Salva in un file BMP
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### Guarda anche

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
