---
title: TiffImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diTiffImageaspose.imaging.fileformats.tiff/tiffimage classe.
type: docs
weight: 10
url: /it/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

Inizializza una nuova istanza di[`TiffImage`](../../tiffimage) classe.

```csharp
public TiffImage(TiffFrame frame)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frame | TiffFrame | Il frame tiff con cui inizializzare l'immagine. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Il frame Tiff non può essere vuoto.;frame |

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

### Guarda anche

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assemblea [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

Inizializza una nuova istanza di[`TiffImage`](../../tiffimage) classe.

```csharp
public TiffImage(TiffFrame[] frames)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frames | TiffFrame[] | Le cornici. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | cornici |

### Esempi

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

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
