---
title: "ImageOptionsBase"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni base dell'immagine."
type: docs
weight: 62
url: /it/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Le opzioni base dell'immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | Un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| [getXmpData()](#getXmpData--) | Ottiene il contenitore dei metadati XMP. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Imposta il contenitore dei metadati XMP. |
| [getExifData()](#getExifData--) | Restituisce i dati Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Imposta i dati Exif. |
| [getSource()](#getSource--) | Ottiene la sorgente in cui creare l'immagine. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getPalette()](#getPalette--) | Restituisce la tavolozza dei colori. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Imposta la tavolozza dei colori. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene le impostazioni di risoluzione. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Imposta le impostazioni di risoluzione. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene le opzioni di rasterizzazione vettoriale. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Imposta le opzioni di rasterizzazione vettoriale. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Restituisce il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Cerca di impostare un'istanza `metadata`, se questa istanza [Image](../../com.aspose.imaging/image) supporta e implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione.

**Returns:**
boolean - un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


Un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ottiene il contenitore dei metadati XMP.

Valore: Il contenitore dei dati XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Imposta il contenitore dei metadati XMP.

Valore: Il contenitore dei dati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | il contenitore dei metadati XMP. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Restituisce i dati Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Imposta i dati Exif.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | i dati Exif. |

### getSource() {#getSource--}
```
public Source getSource()
```


Ottiene la sorgente in cui creare l'immagine.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


Ottiene o imposta la sorgente in cui creare l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | La sorgente in cui creare l'immagine. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Restituisce la tavolozza dei colori.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Imposta la tavolozza dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Crea un'immagine BMP 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Il gradiente lineare dall'angolo in alto a sinistra a quello in basso a destra dell'immagine.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Riempie l'intera immagine con il pennello a gradiente lineare.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Ottieni la palette di colori a 8 bit più vicina che copra il maggior numero possibile di pixel, in modo che un'immagine paletteizzata
    // sia quasi indistinguibile visivamente da una non paletteizzata.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // La palette a 8 bit contiene al massimo 256 colori.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// L'output appare così:
// La dimensione dell'immagine a palette è 11078 byte.
// La dimensione dell'immagine non a palette è 40054 byte.
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ottiene le impostazioni di risoluzione.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Imposta le impostazioni di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Esegui qualche elaborazione dell'immagine.

    // Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Il numero di bit per canale è 8.
    // Quando viene utilizzata una palette, l'indice di colore è memorizzato nei dati dell'immagine invece del colore stesso.
    saveOptions.setBitsPerChannel((byte) 8);

    // Imposta il tipo di compressione progressiva.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
    saveOptions.setQuality(100);

    // Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Se l'immagine di origine è a colori, verrà convertita in scala di grigi.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilizza una palette per ridurre la dimensione dell'output.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


Ottiene le opzioni di rasterizzazione vettoriale.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Imposta le opzioni di rasterizzazione vettoriale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Le opzioni di rasterizzazione vettoriale. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Restituisce il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni.

Valore: L'indicazione della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int - l'indicazione della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Imposta il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni.

Valore: L'indicazione della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | l'indicazione della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni. |

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


Le opzioni multipagina

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


Le opzioni multipagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Ottiene un valore che indica se [full frame].

Valore: `true` se [full frame]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [full frame].
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Imposta un valore che indica se [full frame].

Valore: `true` se [full frame]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [full frame]. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Imposta il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | il gestore dell'evento di avanzamento. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Esempio di utilizzo di gestori di eventi di avanzamento dell'operazione separati per le operazioni di caricamento/esportazione
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// Il registro STDOUT può apparire così:
//        Evento di caricamento Inizializzazione : 1/4
//        Evento di caricamento Preelaborazione : 2/4
//        Evento di caricamento Elaborazione : 3/4
//        Evento di caricamento Finalizzazione : 4/4
//        Evento di esportazione Inizializzazione : 1/4
//        Evento di esportazione Preelaborazione : 2/4
//        Evento di esportazione Elaborazione : 3/4
//        Evento di esportazione ProgressoRelativo : 1/1
//        Evento di caricamento ProgressoRelativo : 1/1
//        Evento di esportazione Finalizzazione : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona questa istanza.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


Cerca di impostare un'istanza `metadata`, se questa istanza [Image](../../com.aspose.imaging/image) supporta e implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | I metadati. |

**Returns:**
boolean - True, se l'istanza [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) supporta e/o implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); altrimenti, false.
