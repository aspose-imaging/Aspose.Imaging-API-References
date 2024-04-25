---
title: DicomOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Opzioni di creazione del formato file DICOM.
type: docs
weight: 9940
url: /it/aspose.imaging.imageoptions/dicomoptions/
---
## DicomOptions class

Opzioni di creazione del formato file DICOM.

```csharp
public class DicomOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DicomOptions](dicomoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ColorType](../../aspose.imaging.imageoptions/dicomoptions/colortype) { get; set; } | Ottiene o imposta il tipo del colore. |
| [Compression](../../aspose.imaging.imageoptions/dicomoptions/compression) { get; set; } | Ottiene o imposta la compressione. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| override [XmpData](../../aspose.imaging.imageoptions/dicomoptions/xmpdata) { get; set; } | Ottiene o imposta i dati Xmp. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Cambia il tipo di colore nella compressione DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Usa la compressione RLE nell'immagine DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

Utilizzare la compressione JPEG 2000 nell'immagine DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

Usa la compressione JPEG nell'immagine DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

L'esempio seguente mostra l'esportazione in formato file DICOM (pagina singola e multipagina).

```csharp
[C#]

string fileName = "sample.jpg";
string inputFileNameSingle = fileName;
string inputFileNameMultipage = "multipage.tif";
string outputFileNameSingleDcm = "output.dcm";
string outputFileNameMultipageDcm = "outputMultipage.dcm";

// L'esempio di codice successivo converte l'immagine JPEG nel formato di file DICOM
using (var image = Aspose.Imaging.Image.Load(inputFileNameSingle))
{
    image.Save(outputFileNameSingleDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}

// Il formato DICOM supporta immagini multipagina. È possibile convertire le immagini GIF o TIFF in DICOM allo stesso modo delle immagini JPEG
using (var imageMultiple = Aspose.Imaging.Image.Load(inputFileNameMultipage))
{
    imageMultiple.Save(outputFileNameMultipageDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}
```

Crea un'immagine Dicom multipagina.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // Disegna qualcosa usando la grafica vettoriale
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Salva i pixel dell'immagine disegnata. Ora sono sulla prima pagina dell'immagine Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // Aggiungi alcune pagine dopo, rendendole più scure
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // Aggiungi alcune pagine davanti alla pagina principale, rendendole più luminose
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // Salva l'immagine multipagina creata nel file di output
    image.Save("MultiPage.dcm");
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
