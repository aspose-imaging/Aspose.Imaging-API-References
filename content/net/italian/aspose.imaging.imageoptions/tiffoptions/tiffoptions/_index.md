---
title: TiffOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diTiffOptionsaspose.imaging.imageoptions/tiffoptions classe.
type: docs
weight: 10
url: /it/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

Inizializza una nuova istanza di[`TiffOptions`](../../tiffoptions) classe.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Il formato di file tiff previsto. |
| byteOrder | TiffByteOrder | L'ordine dei byte del formato del file tiff da utilizzare. |

### Guarda anche

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../tiffoptions)
* assemblea [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

Inizializza una nuova istanza di[`TiffOptions`](../../tiffoptions)classe. Per impostazione predefinita viene utilizzata la convenzione little endian.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Il formato di file tiff previsto. |

### Esempi

L'esempio seguente mostra come creare una copia in scala di grigi di una cornice esistente e aggiungerla a un'immagine TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Crea un'origine file permanente, non temporanea.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Il gradiente lineare dall'angolo in alto a sinistra all'angolo in basso a destra dell'immagine.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Riempi il fotogramma attivo con un pennello sfumato lineare.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Opzioni in scala di grigi
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Crea una copia in scala di grigi del fotogramma attivo.
    // I dati dei pixel vengono conservati ma convertiti nel formato desiderato.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Aggiunge la cornice appena creata all'immagine TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

Questo esempio mostra come salvare un'immagine raster nel formato TIFF utilizzando varie opzioni.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Imposta 8 bit per ogni componente di colore.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Imposta l'ordine dei byte Big Endian (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Imposta la compressione LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Consentono di ridurre le dimensioni delle immagini a tono continuo.
// Attualmente questo campo è utilizzato solo con la codifica LZW perché LZW è probabilmente l'unico schema di codifica TIFF
// che beneficia in modo significativo di un passaggio predittore.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// Imposta il modello di colore RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Per YCbCr, puoi usare una delle seguenti scelte:
// Campo YCbCrSubSampling Fattori di campionamento JPEG
// ----------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(valore predefinito) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tutti i componenti del colore verranno archiviati all'interno di un piano singolo.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crea una cornice TIFF di 100x100 px.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Riempi l'intera immagine con il gradiente blu-giallo.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

### Guarda anche

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../tiffoptions)
* assemblea [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

Inizializza una nuova istanza di[`TiffOptions`](../../tiffoptions) classe.

```csharp
public TiffOptions(TiffOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | TiffOptions | Le opzioni da cui copiare. |

### Guarda anche

* class [TiffOptions](../../tiffoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../tiffoptions)
* assemblea [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

Inizializza una nuova istanza di[`TiffOptions`](../../tiffoptions) classe.

```csharp
public TiffOptions(TiffDataType[] tags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tags | TiffDataType[] | I tag con cui inizializzare le opzioni. |

### Guarda anche

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../tiffoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
