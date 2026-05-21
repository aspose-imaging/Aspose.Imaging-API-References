---
title: "PsdOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea immagini PSD di Photoshop Document con la nostra API che offre opzioni versatili con diverse versioni di formato, metodi di compressione, modalità colore e conteggi di bit per canale colore."
type: docs
weight: 40
url: /it/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Crea immagini Photoshop Document (PSD) con la nostra API, offrendo opzioni versatili con diverse versioni di formato, metodi di compressione, modalità colore e conteggi di bit per canale colore. Gestisci senza problemi i contenitori di metadati XMP, garantendo una elaborazione completa delle immagini grazie alle funzionalità del formato PSD come livelli immagine, maschere di livello e informazioni sul file per personalizzazione e creatività nei tuoi progetti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Inizializza una nuova istanza della classe `PsdOptions`. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Inizializza una nuova istanza della classe `PsdOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Ottieni o imposta il contenitore dati XMP |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione del file PSD. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta la versione del file PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | Ottiene o imposta il metodo di compressione PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Ottiene o imposta il metodo di compressione PSD. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione del formato file. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Imposta la versione del formato file. |
| [getColorMode()](#getColorMode--) | Ottiene o imposta la modalità colore PSD. |
| [setColorMode(short value)](#setColorMode-short-) | Ottiene o imposta la modalità colore PSD. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Ottiene o imposta il conteggio dei bit per canale colore. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Ottiene o imposta il conteggio dei bit per canale colore. |
| [getChannelsCount()](#getChannelsCount--) | Ottiene il conteggio dei canali colore. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Imposta il conteggio dei canali colore. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Ottiene un valore che indica se - Rimuovere la risorsa del motore di testo globale - Utilizzato per alcuni file PSD con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per problemi relativi a livelli di testo con font mancanti). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Imposta un valore che indica se - Rimuovere la risorsa del motore di testo globale - Utilizzato per alcuni file PSD con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per problemi relativi a livelli di testo con font mancanti). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Ottiene un valore che indica se [refresh image preview data] - opzione utilizzata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Imposta un valore che indica se [refresh image preview data] - opzione utilizzata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. |
| [getVectorizationOptions()](#getVectorizationOptions--) | Ottiene le opzioni di vettorizzazione PSD. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | Imposta le opzioni di vettorizzazione PSD. |

## Example: This example demonstrates the use of Aspose.
Questo esempio dimostra l'uso dell'API Aspose.Imaging per Java per convertire le Immagini in formato PSD. Per raggiungere questo obiettivo, l'esempio carica un'immagine esistente e poi la salva nuovamente in formato PSD.
``` java

// Crea un'istanza della classe image e inizializzala con un file esistente tramite il percorso del File.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Crea un'istanza della classe PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Imposta il CompressionMethod su RLE.
    // Nota: Un altro CompressionMethod supportato è CompressionMethod.RAW [Nessuna compressione]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Imposta il ColorMode su GrayScale.
    // Nota: Altri ColorModes supportati sono ColorModes.Bitmap e ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Salva l'immagine su disco con le impostazioni PsdOptions fornite.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. Queste pagine saranno presentate come livelli nel PSD di output.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Inizializza una nuova istanza della classe `PsdOptions`.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Inizializza una nuova istanza della classe `PsdOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | Le opzioni. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ottieni o imposta il contenitore dati XMP

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta la versione del file PSD.

Valore: La versione del file PSD.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta la versione del file PSD.

Valore: La versione del file PSD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definisci un gradiente lineare blu-trasparente.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempie l'immagine PNG con il gradiente lineare blu-trasparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Le seguenti opzioni saranno utilizzate per salvare l'immagine PNG in formato PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Il numero di bit per canale
    saveOptions.setChannelBitsCount((byte) 8);

    // Il numero di canali. Un canale per ogni componente colore R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // La modalità colore
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Nessuna compressione
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La versione predefinita è 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compressione RLE consente di ridurre le dimensioni dell'immagine di output.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // L'output potrebbe apparire così:
    // La dimensione dell'immagine PSD con compressione RAW: 40090
    // La dimensione dell'immagine PSD con compressione RLE: 16185
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


Ottiene o imposta il metodo di compressione PSD.

Valore: Il metodo di compressione.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


Ottiene o imposta il metodo di compressione PSD.

Valore: Il metodo di compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |


**Example: This example demonstrates the use of Aspose.**
Questo esempio dimostra l'uso dell'API Aspose.Imaging per Java per convertire le Immagini in formato PSD. Per raggiungere questo obiettivo, l'esempio carica un'immagine esistente e poi la salva nuovamente in formato PSD.
``` java

// Crea un'istanza della classe image e inizializzala con un file esistente tramite il percorso del File.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Crea un'istanza della classe PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Imposta il CompressionMethod su RLE.
    // Nota: Un altro CompressionMethod supportato è CompressionMethod.RAW [Nessuna compressione]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Imposta il ColorMode su GrayScale.
    // Nota: Altri ColorModes supportati sono ColorModes.Bitmap e ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Salva l'immagine su disco con le impostazioni PsdOptions fornite.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Ottiene la versione del formato file. Può essere PSD o PSB.

Valore: La versione del formato file.

**Returns:**
byte - la versione del formato file.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Imposta la versione del formato file. Può essere PSD o PSB.

Valore: La versione del formato file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | la versione del formato file. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


Ottiene o imposta la modalità colore PSD.

Valore: La modalità colore.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


Ottiene o imposta la modalità colore PSD.

Valore: La modalità colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |


**Example: This example demonstrates the use of Aspose.**
Questo esempio dimostra l'uso dell'API Aspose.Imaging per Java per convertire le Immagini in formato PSD. Per raggiungere questo obiettivo, l'esempio carica un'immagine esistente e poi la salva nuovamente in formato PSD.
``` java

// Crea un'istanza della classe image e inizializzala con un file esistente tramite il percorso del File.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Crea un'istanza della classe PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Imposta il CompressionMethod su RLE.
    // Nota: Un altro CompressionMethod supportato è CompressionMethod.RAW [Nessuna compressione]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Imposta il ColorMode su GrayScale.
    // Nota: Altri ColorModes supportati sono ColorModes.Bitmap e ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Salva l'immagine su disco con le impostazioni PsdOptions fornite.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Ottiene o imposta il conteggio dei bit per canale colore.

Valore: il conteggio dei bit per canale colore.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Ottiene o imposta il conteggio dei bit per canale colore.

Valore: il conteggio dei bit per canale colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definisci un gradiente lineare blu-trasparente.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempie l'immagine PNG con il gradiente lineare blu-trasparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Le seguenti opzioni saranno utilizzate per salvare l'immagine PNG in formato PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Il numero di bit per canale
    saveOptions.setChannelBitsCount((byte) 8);

    // Il numero di canali. Un canale per ogni componente colore R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // La modalità colore
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Nessuna compressione
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La versione predefinita è 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compressione RLE consente di ridurre le dimensioni dell'immagine di output.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // L'output potrebbe apparire così:
    // La dimensione dell'immagine PSD con compressione RAW: 40090
    // La dimensione dell'immagine PSD con compressione RLE: 16185
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Ottiene il conteggio dei canali colore.

**Returns:**
short - il conteggio dei canali colore.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Imposta il conteggio dei canali colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | Il conteggio dei canali colore. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definisci un gradiente lineare blu-trasparente.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempie l'immagine PNG con il gradiente lineare blu-trasparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Le seguenti opzioni saranno utilizzate per salvare l'immagine PNG in formato PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Il numero di bit per canale
    saveOptions.setChannelBitsCount((byte) 8);

    // Il numero di canali. Un canale per ogni componente colore R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // La modalità colore
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Nessuna compressione
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La versione predefinita è 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compressione RLE consente di ridurre le dimensioni dell'immagine di output.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // L'output potrebbe apparire così:
    // La dimensione dell'immagine PSD con compressione RAW: 40090
    // La dimensione dell'immagine PSD con compressione RLE: 16185
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Ottiene un valore che indica se - Rimuovere la risorsa del motore di testo globale - Utilizzato per alcuni file PSD con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti). Dopo aver usato questa opzione, l'utente deve eseguire quanto segue nel file aperto in Photoshop: Menu "Text" -> "Process absent fonts". Dopo quell'operazione tutto il testo riapparirà. Si noti che questa operazione può causare alcune modifiche finali al layout.

**Returns:**
boolean - `true` se [remove global text engine resource]; altrimenti, `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Imposta un valore che indica se - Rimuovere la risorsa del motore di testo globale - Utilizzato per alcuni file PSD con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti). Dopo aver usato questa opzione, l'utente deve eseguire quanto segue nel file aperto in Photoshop: Menu "Text" -> "Process absent fonts". Dopo quell'operazione tutto il testo riapparirà. Si noti che questa operazione può causare alcune modifiche finali al layout.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se [remove global text engine resource]; altrimenti, `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Ottiene un valore che indica se [refresh image preview data] - opzione utilizzata per massimizzare la compatibilità con altri visualizzatori di immagini PSD.

**Returns:**
boolean - `true` se [refresh image preview data]; altrimenti, `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Imposta un valore che indica se [refresh image preview data] - opzione utilizzata per massimizzare la compatibilità con altri visualizzatori di immagini PSD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se [refresh image preview data]; altrimenti, `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


Ottiene le opzioni di vettorizzazione PSD.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


Imposta le opzioni di vettorizzazione PSD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | le opzioni di vettorizzazione PSD. |

