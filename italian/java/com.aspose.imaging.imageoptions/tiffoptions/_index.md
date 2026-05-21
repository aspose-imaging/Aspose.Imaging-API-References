---
title: "TiffOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni del formato file TIFF."
type: docs
weight: 48
url: /it/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

Le opzioni del formato file tiff. Nota che i tag di larghezza e altezza verranno sovrascritti durante la creazione dell'immagine dai parametri width e height, quindi non è necessario specificarli direttamente. Nota che molte opzioni restituiscono un valore predefinito, ma ciò non significa che questa opzione sia impostata esplicitamente come valore di tag. Per verificare la presenza del tag, usa la proprietà Tags o il metodo corrispondente IsTagPresent.

` ATTENZIONE! non modificare mai le opzioni tiff durante il salvataggio poiché ciò può causare effetti collaterali e bug difficili da trovare. La riga seguente è stata lasciata commentata appositamente poiché causava una determinazione errata dell'inizio dei dati. Le opzioni passate non contenevano spp (anche se le opzioni non sono corrette in tal caso, questo scenario provoca comunque errori) e la riga successiva ha aggiunto i tag +spp tag +bpp tag e quando le opzioni sono state scritte dopo che i dati sono stati completamente scritti hanno sovrascritto l'inizio dei dati per il codec non compresso!!! Vedi TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Inizializza una nuova istanza della classe `TiffOptions`. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Inizializza una nuova istanza della classe `TiffOptions`. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Inizializza una nuova istanza della classe `TiffOptions`. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe `TiffOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ottiene il conteggio dei tag validi. |
| [getTagCount()](#getTagCount--) | Ottiene il conteggio dei tag. |
| [getFileStandard()](#getFileStandard--) | Ottiene o imposta lo standard del file TIFF. |
| [setFileStandard(int value)](#setFileStandard-int-) | Ottiene o imposta lo standard del file TIFF. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Ottiene o imposta il limite predefinito di allocazione della memoria. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Ottiene o imposta il limite predefinito di allocazione della memoria. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| [isValid()](#isValid--) | Ottiene un valore che indica se il `TiffOptions` è stato configurato correttamente. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Ottiene o imposta i coefficienti YCbCr. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta i coefficienti YCbCr. |
| [isTiled()](#isTiled--) | Ottiene un valore che indica se l'immagine è suddivisa in tasselli. |
| [getArtist()](#getArtist--) | Ottiene o imposta l'artista. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Ottiene o imposta l'artista. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Determina se il tag è presente nelle opzioni o meno. |
| [getByteOrder()](#getByteOrder--) | Ottiene o imposta un valore che indica l'ordine dei byte TIFF. |
| [setByteOrder(int value)](#setByteOrder-int-) | Ottiene o imposta un valore che indica l'ordine dei byte TIFF. |
| [getIccProfile()](#getIccProfile--) | Ottiene lo stream del profilo ICC. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Imposta lo stream del profilo ICC. |
| [isDisableIccExport()](#isDisableIccExport--) | Ottiene un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC viene applicato ai pixel di origine in anticipo). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | Imposta un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC viene applicato ai pixel di origine in anticipo). |
| [getBitsPerSample()](#getBitsPerSample--) | Ottiene i bit per campione. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Imposta i bit per campione. |
| [getExtraSamples()](#getExtraSamples--) | Ottiene i valori dei campioni extra. |
| [getCompression()](#getCompression--) | Ottiene la compressione. |
| [setCompression(int value)](#setCompression-int-) | Imposta la compressione. |
| [getCompressedQuality()](#getCompressedQuality--) | Ottiene la qualità dell'immagine compressa. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Imposta la qualità dell'immagine compressa. |
| [getCopyright()](#getCopyright--) | Ottiene il copyright. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Imposta il copyright. |
| [getColorMap()](#getColorMap--) | Ottiene o imposta la mappa dei colori. |
| [setColorMap(int[] value)](#setColorMap-int---) | Ottiene o imposta la mappa dei colori. |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [getDateTime()](#getDateTime--) | Ottiene o imposta la data e l'ora. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Ottiene o imposta la data e l'ora. |
| [getDocumentName()](#getDocumentName--) | Ottiene o imposta il nome del documento. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Ottiene o imposta il nome del documento. |
| [getAlphaStorage()](#getAlphaStorage--) | Ottiene o imposta l'opzione di memorizzazione alfa. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Ottiene o imposta l'opzione di memorizzazione alfa. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Ottiene un valore che indica se i campioni extra sono presenti. |
| [getFillOrder()](#getFillOrder--) | Ottiene o imposta l'ordine di riempimento dei bit dei byte. |
| [setFillOrder(int value)](#setFillOrder-int-) | Ottiene o imposta l'ordine di riempimento dei bit dei byte. |
| [getHalfToneHints()](#getHalfToneHints--) | Ottiene o imposta i suggerimenti per mezzitoni. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Ottiene o imposta i suggerimenti per mezzitoni. |
| [getImageDescription()](#getImageDescription--) | Ottiene o imposta la descrizione dell'immagine. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Ottiene o imposta la descrizione dell'immagine. |
| [getInkNames()](#getInkNames--) | Ottiene o imposta i nomi dell'inchiostro. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Ottiene o imposta i nomi dell'inchiostro. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Ottiene o imposta il produttore dello scanner. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Ottiene o imposta il produttore dello scanner. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Ottiene o imposta il valore massimo del campione. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Ottiene o imposta il valore massimo del campione. |
| [getMinSampleValue()](#getMinSampleValue--) | Ottiene o imposta il valore minimo del campione. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Ottiene o imposta il valore minimo del campione. |
| [getScannerModel()](#getScannerModel--) | Ottiene o imposta il modello dello scanner. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Ottiene o imposta il modello dello scanner. |
| [getOrientation()](#getOrientation--) | Ottiene o imposta l'orientamento. |
| [setOrientation(int value)](#setOrientation-int-) | Ottiene o imposta l'orientamento. |
| [getPageName()](#getPageName--) | Ottiene o imposta il nome della pagina. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Ottiene o imposta il nome della pagina. |
| [getPageNumber()](#getPageNumber--) | Ottiene o imposta il tag del numero di pagina. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Ottiene o imposta il tag del numero di pagina. |
| [getPhotometric()](#getPhotometric--) | Ottiene o imposta il valore fotometrico. |
| [setPhotometric(int value)](#setPhotometric-int-) | Ottiene o imposta il valore fotometrico. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Ottiene o imposta la configurazione planare. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Ottiene o imposta la configurazione planare. |
| [getResolutionUnit()](#getResolutionUnit--) | Ottiene o imposta l'unità di risoluzione. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Ottiene o imposta l'unità di risoluzione. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Ottiene o imposta le righe per striscia. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Ottiene o imposta le righe per striscia. |
| [getTileWidth()](#getTileWidth--) | Ottiene o imposta la larghezza della tessera. |
| [setTileWidth(long value)](#setTileWidth-long-) | Ottiene o imposta la larghezza della tessera. |
| [getTileLength()](#getTileLength--) | Ottiene o imposta la lunghezza della tessera. |
| [setTileLength(long value)](#setTileLength-long-) | Ottiene o imposta la lunghezza della tessera. |
| [getSampleFormat()](#getSampleFormat--) | Ottiene o imposta il formato del campione. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Ottiene o imposta il formato del campione. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Ottiene i campioni per pixel. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Ottiene o imposta il valore massimo del campione. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Ottiene o imposta il valore massimo del campione. |
| [getSminSampleValue()](#getSminSampleValue--) | Ottiene o imposta il valore minimo del campione. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Ottiene o imposta il valore minimo del campione. |
| [getSoftwareType()](#getSoftwareType--) | Ottiene o imposta il tipo di software. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Ottiene o imposta il tipo di software. |
| [getStripByteCounts()](#getStripByteCounts--) | Ottiene o imposta il conteggio dei byte della striscia. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Ottiene o imposta il conteggio dei byte della striscia. |
| [getStripOffsets()](#getStripOffsets--) | Ottiene o imposta gli offset della striscia. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Ottiene o imposta gli offset della striscia. |
| [getTileByteCounts()](#getTileByteCounts--) | Ottiene o imposta i conteggi dei byte delle tile. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Ottiene o imposta i conteggi dei byte delle tile. |
| [getTileOffsets()](#getTileOffsets--) | Ottiene o imposta gli offset delle tile. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Ottiene o imposta gli offset delle tile. |
| [getSubFileType()](#getSubFileType--) | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile. |
| [setSubFileType(long value)](#setSubFileType-long-) | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile. |
| [getTargetPrinter()](#getTargetPrinter--) | Ottiene o imposta la stampante di destinazione. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Ottiene o imposta la stampante di destinazione. |
| [getThreshholding()](#getThreshholding--) | Ottiene o imposta la soglia. |
| [setThreshholding(int value)](#setThreshholding-int-) | Ottiene o imposta la soglia. |
| [getTotalPages()](#getTotalPages--) | Ottiene il numero totale di pagine. |
| [getXposition()](#getXposition--) | Ottiene o imposta la posizione x. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la posizione x. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [getXresolution()](#getXresolution--) | Ottiene o imposta la risoluzione x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione x. |
| [getYposition()](#getYposition--) | Ottiene o imposta la posizione y. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la posizione y. |
| [getYresolution()](#getYresolution--) | Ottiene o imposta la risoluzione y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione y. |
| [getFaxT4Options()](#getFaxT4Options--) | Ottiene o imposta le opzioni fax t4. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Ottiene o imposta le opzioni fax t4. |
| [getPredictor()](#getPredictor--) | Ottiene o imposta il predittore per la compressione LZW. |
| [setPredictor(int value)](#setPredictor-int-) | Ottiene o imposta il predittore per la compressione LZW. |
| [getImageLength()](#getImageLength--) | Ottiene o imposta la lunghezza dell'immagine. |
| [setImageLength(long value)](#setImageLength-long-) | Ottiene o imposta la lunghezza dell'immagine. |
| [getImageWidth()](#getImageWidth--) | Ottiene o imposta la larghezza dell'immagine. |
| [setImageWidth(long value)](#setImageWidth-long-) | Ottiene o imposta la larghezza dell'immagine. |
| [getExifIfd()](#getExifIfd--) | Ottiene o imposta il puntatore all'EXIF IFD. |
| [getTags()](#getTags--) | Ottiene o imposta i tag. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag. |
| [getValidTagCount()](#getValidTagCount--) | Ottiene il conteggio dei tag validi. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ottiene i bit per pixel. |
| [getXPTitle()](#getXPTitle--) | Ottiene informazioni sull'immagine, utilizzate da Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Imposta informazioni sull'immagine, utilizzate da Windows Explorer. |
| [getXPComment()](#getXPComment--) | Ottiene il commento sull'immagine, utilizzato da Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Imposta il commento sull'immagine, utilizzato da Windows Explorer. |
| [getXPAuthor()](#getXPAuthor--) | Ottiene l'autore dell'immagine, utilizzato da Windows Explorer. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Imposta l'autore dell'immagine, utilizzato da Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Ottiene il soggetto dell'immagine, utilizzato da Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Imposta l'immagine soggetto, utilizzata da Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Ottiene informazioni sull'immagine, utilizzate da Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Imposta informazioni sull'immagine, utilizzate da Windows Explorer. |
| [getExifData()](#getExifData--) | Ottiene i dati Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Imposta i dati Exif. |
| [removeTag(int tag)](#removeTag-int-) | Rimuove il tag. |
| [removeTags(int[] tags)](#removeTags-int...-) | Rimuove i tag. |
| [validate()](#validate--) | Convalida se le opzioni hanno una combinazione valida di tag |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Aggiunge i tag. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Aggiunge un nuovo tag. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Ottiene l'istanza del tag per tipo. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Questo esempio dimostra l'uso di diverse classi dal namespace SaveOptions per scopi di esportazione. Un'immagine di tipo Gif viene caricata in un'istanza di Image e poi esportata in diversi formati.
``` java
String dir = "c:\\temp\\";

//Carica un'immagine esistente (di tipo Gif) in un'istanza della classe Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Esporta nel formato file BMP utilizzando le opzioni predefinite
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Esporta nel formato file JPEG utilizzando le opzioni predefinite
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Esporta nel formato file PNG utilizzando le opzioni predefinite
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Esporta nel formato file TIFF utilizzando le opzioni predefinite
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. Queste pagine saranno presentate come fotogrammi nel TIFF di output.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
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

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Inizializza una nuova istanza della classe `TiffOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | int | Il formato di file TIFF previsto. |
| byteOrder | int | L'ordine dei byte del formato di file TIFF. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Inizializza una nuova istanza della classe `TiffOptions`. Per impostazione predefinita, viene utilizzata la convenzione little endian.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | int | Il formato di file TIFF previsto. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Inizializza una nuova istanza della classe `TiffOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Le opzioni da copiare. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Inizializza una nuova istanza della classe `TiffOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag con cui inizializzare le opzioni. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Ottiene il conteggio dei tag validi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag da convalidare. |

**Returns:**
int - Il conteggio dei tag validi.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Ottiene il conteggio dei tag.

**Returns:**
int - il conteggio dei tag.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Ottiene o imposta lo standard del file TIFF.

**Returns:**
int - Lo standard del file TIFF.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Ottiene o imposta lo standard del file TIFF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Lo standard del file TIFF. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Ottiene o imposta il limite predefinito di allocazione della memoria.

**Returns:**
int - Il limite predefinito di allocazione della memoria.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Ottiene o imposta il limite predefinito di allocazione della memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il limite predefinito di allocazione della memoria. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati.

**Returns:**
boolean - `true` se i componenti devono essere premoltiplicati; altrimenti, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se i componenti devono essere premoltiplicati; altrimenti, `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Ottiene un valore che indica se `TiffOptions` è stato configurato correttamente. Usa il metodo Validate per trovare il motivo del fallimento.

**Returns:**
boolean - `true` se TiffOptions è configurato correttamente; altrimenti, `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr.

**Returns:**
int[] - I fattori di sottocampionamento per la fotometria YCbCr.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | I fattori di sottocampionamento per la fotometria YCbCr. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Imposta 8 bit per ogni componente colore.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Imposta l'ordine dei byte Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Imposta la compressione LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Consente di ridurre le dimensioni delle immagini a tono continuo.
// Attualmente questo campo è usato solo con la codifica LZW perché LZW è probabilmente l'unico schema di codifica TIFF.
// che beneficia notevolmente da un passaggio predittore.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Imposta il modello di colore RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Per YCbCr, è possibile utilizzare una delle seguenti scelte:
// Campo YCbCrSubSampling   fattori di campionamento JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valore predefinito)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tutti i componenti colore saranno memorizzati in un unico piano.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un frame TIFF di 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Riempie l'intera immagine con il gradiente blu-giallo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Ottiene o imposta i coefficienti YCbCr.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - I coefficienti YCbCr.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Ottiene o imposta i coefficienti YCbCr.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | I coefficienti YCbCr. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Ottiene un valore che indica se l'immagine è suddivisa in tasselli.

**Returns:**
boolean - `true` se l'immagine è suddivisa a tasselli; altrimenti, `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Ottiene o imposta l'artista.

**Returns:**
java.lang.String - L'artista.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Ottiene o imposta l'artista.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | L\u2019artista. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Determina se il tag è presente nelle opzioni o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tag | int | L'ID del tag da verificare. |

**Returns:**
boolean - `true` se il tag è presente; altrimenti, `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Ottiene o imposta un valore che indica l'ordine dei byte TIFF.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Ottiene o imposta un valore che indica l'ordine dei byte TIFF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Imposta 8 bit per ogni componente colore.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Imposta l'ordine dei byte Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Imposta la compressione LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Consente di ridurre le dimensioni delle immagini a tono continuo.
// Attualmente questo campo è usato solo con la codifica LZW perché LZW è probabilmente l'unico schema di codifica TIFF.
// che beneficia notevolmente da un passaggio predittore.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Imposta il modello di colore RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Per YCbCr, è possibile utilizzare una delle seguenti scelte:
// Campo YCbCrSubSampling   fattori di campionamento JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valore predefinito)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tutti i componenti colore saranno memorizzati in un unico piano.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un frame TIFF di 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Riempie l'intera immagine con il gradiente blu-giallo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Ottiene lo stream del profilo ICC.

**Returns:**
byte[] - Il profilo icc.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Imposta lo stream del profilo ICC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] | Il profilo icc. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


Ottiene un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC viene applicato ai pixel di origine in anticipo).

**Returns:**
boolean - un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC è applicato ai pixel di origine in anticipo).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


Imposta un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC viene applicato ai pixel di origine in anticipo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC è applicato ai pixel di origine in anticipo). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Ottiene i bit per campione.

**Returns:**
int[] - Il valore dei bit per campione.

Quando si imposta questo valore, tenere presente che imposterà anche il valore SamplesPerPixel alla lunghezza dell'array. Queste 2 proprietà sono strettamente collegate, quindi possono essere impostate solo insieme.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Imposta i bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | Il valore dei bit per campione. |

Quando si imposta questo valore, tenere presente che imposterà anche il valore SamplesPerPixel alla lunghezza dell'array. Queste 2 proprietà sono strettamente collegate, quindi possono essere impostate solo insieme. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Crea una sorgente file permanente, non temporanea.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il gradiente lineare dall'angolo in alto a sinistra a quello in basso a destra dell'immagine.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Riempie il fotogramma attivo con un pennello a gradiente lineare.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Opzioni in scala di grigi
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Crea una copia in scala di grigi del fotogramma attivo.
    // I dati dei pixel sono preservati ma convertiti nel formato desiderato.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Aggiungi il fotogramma appena creato all'immagine TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


Ottiene i valori dei campioni extra.

Valore: Il valore dei campioni extra.

**Returns:**
int[] - i valori dei campioni extra.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Ottiene la compressione.

**Returns:**
int - La compressione.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Imposta la compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La compressione. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// Opzioni per il primo fotogramma
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Imposta 8 bit per ogni componente colore.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Imposta l'ordine dei byte Big Endian (Motorola)
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Imposta la compressione LZW.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Imposta il modello di colore RGB.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Tutti i componenti colore saranno memorizzati in un unico piano.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea il primo fotogramma TIFF di 100x100 px.
// Nota che non è necessario rilasciare i fotogrammi esplicitamente se sono inclusi in TiffImage.
// Quando il contenitore viene eliminato, tutti i frame verranno eliminati automaticamente.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// Riempire il primo fotogramma con la sfumatura blu-giallo.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// Opzioni per il primo fotogramma
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Imposta 1 bit per pixel per un'immagine B/N.
createOptions2.setBitsPerSample(new int[]{1});

// Imposta l'ordine dei byte Little Endian (Intel)
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// Imposta la compressione CCITT Group 3 Fax.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// Imposta il modello di colore B/N dove 0 è nero, 1 è bianco.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// Crea il secondo fotogramma TIFF di 200x200px.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// Riempire il secondo fotogramma con la sfumatura blu-giallo.
// Verrà convertito automaticamente al formato B/N a causa delle impostazioni corrispondenti del fotogramma.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Crea un'immagine TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Ottiene la qualità dell'immagine compressa. Usato con la compressione Jpeg.

**Returns:**
int - qualità dell'immagine compressa.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Imposta la qualità dell'immagine compressa. Usato con la compressione Jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | qualità dell'immagine compressa. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // Imposta il modello di colore RGB.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Imposta la compressione Jpeg.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Imposta 8 bit per ogni componente colore.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Ottiene il copyright.

**Returns:**
java.lang.String - Il copyright.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Imposta il copyright.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il copyright. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Ottiene o imposta la mappa dei colori.

**Returns:**
int[] - La mappa dei colori.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Ottiene o imposta la mappa dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | La mappa dei colori. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ottiene o imposta la tavolozza dei colori.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ottiene o imposta la tavolozza dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Ottiene o imposta la data e l'ora.

**Returns:**
java.lang.String - La data e l'ora.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Ottiene o imposta la data e l'ora.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La data e l'ora. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Ottiene o imposta il nome del documento.

**Returns:**
java.lang.String - Il nome del documento.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Ottiene o imposta il nome del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il nome del documento. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Ottiene o imposta l'opzione di memorizzazione alfa. Opzioni diverse da `TiffAlphaStorage.Unspecified` sono utilizzate quando sono definiti più di 3 `SamplesPerPixel`.

**Returns:**
int - L'opzione di archiviazione alfa.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Ottiene o imposta l'opzione di memorizzazione alfa. Opzioni diverse da `TiffAlphaStorage.Unspecified` sono utilizzate quando sono definiti più di 3 `SamplesPerPixel`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'opzione di archiviazione alfa. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Ottiene un valore che indica se i campioni extra sono presenti.

**Returns:**
boolean - `true` se il campione extra è presente; altrimenti, `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Ottiene o imposta l'ordine di riempimento dei bit dei byte.

**Returns:**
int - L'ordine di riempimento dei bit del byte.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Ottiene o imposta l'ordine di riempimento dei bit dei byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'ordine di riempimento dei bit del byte. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Ottiene o imposta i suggerimenti per mezzitoni.

**Returns:**
int[] - I suggerimenti di mezzitoni.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Ottiene o imposta i suggerimenti per mezzitoni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | I suggerimenti di mezzitoni. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Ottiene o imposta la descrizione dell'immagine.

**Returns:**
java.lang.String - La descrizione dell'immagine.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Ottiene o imposta la descrizione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La descrizione dell'immagine. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Ottiene o imposta i nomi dell'inchiostro.

**Returns:**
java.lang.String - I nomi dell'inchiostro.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Ottiene o imposta i nomi dell'inchiostro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | I nomi dell'inchiostro. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Ottiene o imposta il produttore dello scanner.

**Returns:**
java.lang.String - Il produttore dello scanner.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Ottiene o imposta il produttore dello scanner.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il produttore dello scanner. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Ottiene o imposta il valore massimo del campione.

**Returns:**
int[] - Il valore massimo del campione.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Ottiene o imposta il valore massimo del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il valore massimo del campione. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Ottiene o imposta il valore minimo del campione.

**Returns:**
int[] - Il valore minimo del campione.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Ottiene o imposta il valore minimo del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il valore minimo del campione. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Ottiene o imposta il modello dello scanner.

**Returns:**
java.lang.String - Il modello dello scanner.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Ottiene o imposta il modello dello scanner.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il modello dello scanner. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Ottiene o imposta l'orientamento.

**Returns:**
int - L'orientamento [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Ottiene o imposta l'orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | L'orientamento [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Ottiene o imposta il nome della pagina.

**Returns:**
java.lang.String - Il nome della pagina.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Ottiene o imposta il nome della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il nome della pagina. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Ottiene o imposta il tag del numero di pagina.

**Returns:**
int[] - Il tag del numero di pagina.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Ottiene o imposta il tag del numero di pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il tag del numero di pagina. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Ottiene o imposta il valore fotometrico.

**Returns:**
int - Il fotometrico.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Ottiene o imposta il valore fotometrico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il fotometrico. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Crea una sorgente file permanente, non temporanea.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il gradiente lineare dall'angolo in alto a sinistra a quello in basso a destra dell'immagine.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Riempie il fotogramma attivo con un pennello a gradiente lineare.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Opzioni in scala di grigi
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Crea una copia in scala di grigi del fotogramma attivo.
    // I dati dei pixel sono preservati ma convertiti nel formato desiderato.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Aggiungi il fotogramma appena creato all'immagine TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Ottiene o imposta la configurazione planare.

**Returns:**
int - La configurazione planare.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Ottiene o imposta la configurazione planare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La configurazione planare. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Imposta 8 bit per ogni componente colore.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Imposta l'ordine dei byte Big Endian (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Imposta la compressione LZW.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Imposta il modello di colore RGB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Tutti i componenti colore saranno memorizzati in un unico piano.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un frame TIFF di 100x100 px.
// Nota che non è necessario eliminare esplicitamente un frame se è incluso in TiffImage.
// Quando il contenitore viene eliminato, tutti i frame verranno eliminati automaticamente.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Riempie l'intero frame con il gradiente blu-giallo.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Crea un'immagine TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Ottiene o imposta l'unità di risoluzione.

**Returns:**
int - L'unità di risoluzione.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Ottiene o imposta l'unità di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'unità di risoluzione. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Ottiene o imposta le righe per striscia.

**Returns:**
long - Le righe per striscia.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Ottiene o imposta le righe per striscia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Le righe per striscia. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Ottiene o imposta la larghezza della tessera.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Ottiene o imposta la larghezza della tessera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Ottiene o imposta la lunghezza della tessera.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Ottiene o imposta la lunghezza della tessera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Ottiene o imposta il formato del campione.

**Returns:**
int[] - Il formato del campione.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Ottiene o imposta il formato del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il formato del campione. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Ottiene i campioni per pixel. Per modificare il valore di questa proprietà usa il setter della proprietà `BitsPerSample`.

**Returns:**
int - I campioni per pixel.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Ottiene o imposta il valore massimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Returns:**
long[] - Il valore massimo del campione.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Ottiene o imposta il valore massimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Il valore massimo del campione. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Ottiene o imposta il valore minimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Returns:**
long[] - Il valore minimo del campione.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Ottiene o imposta il valore minimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Il valore minimo del campione. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Ottiene o imposta il tipo di software.

**Returns:**
java.lang.String - Il tipo di software.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Ottiene o imposta il tipo di software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il tipo di software. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Ottiene o imposta il conteggio dei byte della striscia.

**Returns:**
long[] - Il conteggio dei byte della striscia.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Ottiene o imposta il conteggio dei byte della striscia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Il conteggio dei byte della striscia. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Ottiene o imposta gli offset della striscia.

**Returns:**
long[] - Gli offset della striscia.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Ottiene o imposta gli offset della striscia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Gli offset della striscia. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Ottiene o imposta i conteggi dei byte delle tile.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Ottiene o imposta i conteggi dei byte delle tile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Ottiene o imposta gli offset delle tile.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Ottiene o imposta gli offset delle tile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile.

**Returns:**
long - L'indicazione generale del tipo di dati contenuti in questo sottofile.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | L'indicazione generale del tipo di dati contenuti in questo sottofile. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Ottiene o imposta la stampante di destinazione.

**Returns:**
java.lang.String - La stampante di destinazione.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Ottiene o imposta la stampante di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La stampante di destinazione. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Ottiene o imposta la soglia.

**Returns:**
int - La soglia.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Ottiene o imposta la soglia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La soglia. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Ottiene il numero totale di pagine.

**Returns:**
int - Il totale delle pagine.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Ottiene o imposta la posizione x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Ottiene o imposta la posizione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La posizione x. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ottiene o imposta le impostazioni di risoluzione.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ottiene o imposta le impostazioni di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Ottiene o imposta la risoluzione x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Ottiene o imposta la risoluzione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La risoluzione x. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Ottiene o imposta la posizione y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Ottiene o imposta la posizione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La posizione y. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Ottiene o imposta la risoluzione y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Ottiene o imposta la risoluzione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | La risoluzione y. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Ottiene o imposta le opzioni fax t4.

**Returns:**
long - Le opzioni fax t4.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Ottiene o imposta le opzioni fax t4.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Le opzioni fax t4. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Ottiene o imposta il predittore per la compressione LZW.

**Returns:**
int - Il tipo di predittore.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Ottiene o imposta il predittore per la compressione LZW.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il tipo di predittore. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Imposta 8 bit per ogni componente colore.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Imposta l'ordine dei byte Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Imposta la compressione LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Consente di ridurre le dimensioni delle immagini a tono continuo.
// Attualmente questo campo è usato solo con la codifica LZW perché LZW è probabilmente l'unico schema di codifica TIFF.
// che beneficia notevolmente da un passaggio predittore.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Imposta il modello di colore RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Per YCbCr, è possibile utilizzare una delle seguenti scelte:
// Campo YCbCrSubSampling   fattori di campionamento JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(valore predefinito)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tutti i componenti colore saranno memorizzati in un unico piano.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un frame TIFF di 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Riempie l'intera immagine con il gradiente blu-giallo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Ottiene o imposta la lunghezza dell'immagine.

**Returns:**
long - La lunghezza dell'immagine.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Ottiene o imposta la lunghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | La lunghezza dell'immagine. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Ottiene o imposta la larghezza dell'immagine.

**Returns:**
long - La larghezza dell'immagine.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Ottiene o imposta la larghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | La larghezza dell'immagine. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Ottiene o imposta il puntatore all'EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Ottiene o imposta i tag.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - I tag.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Ottiene o imposta i tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Restituisce il conteggio dei tag validi. Questo non è il conteggio totale dei tag ma il numero di tag che possono essere conservati.

**Returns:**
int - Il conteggio dei tag validi.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ottiene i bit per pixel.

**Returns:**
int - I bit per pixel.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Ottiene informazioni sull'immagine, utilizzate da Windows Explorer.

Valore: Informazioni sull'immagine, utilizzate da Windows Explorer. Il `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) è ignorato da Windows Explorer se il tag `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) esiste.

**Returns:**
java.lang.String - informazioni sull'immagine, utilizzate da Windows Explorer.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Imposta informazioni sull'immagine, utilizzate da Windows Explorer.

Valore: Informazioni sull'immagine, utilizzate da Windows Explorer. Il `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) è ignorato da Windows Explorer se il tag `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) esiste.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | informazioni sull'immagine, utilizzate da Windows Explorer. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Ottiene il commento sull'immagine, utilizzato da Windows Explorer.

Valore: Commento sull'immagine, utilizzato da Windows Explorer.

**Returns:**
java.lang.String - commento sull'immagine, utilizzato da Windows Explorer.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Imposta il commento sull'immagine, utilizzato da Windows Explorer.

Valore: Commento sull'immagine, utilizzato da Windows Explorer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | commento sull'immagine, utilizzato da Windows Explorer. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Ottiene l'autore dell'immagine, utilizzato da Windows Explorer.

Valore: Autore immagine, utilizzato da Windows Explorer. Il `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) è ignorato da Windows Explorer se il tag `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) esiste.

**Returns:**
java.lang.String - autore immagine, utilizzato da Windows Explorer.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Imposta l'autore dell'immagine, utilizzato da Windows Explorer.

Valore: Autore immagine, utilizzato da Windows Explorer. Il `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) è ignorato da Windows Explorer se il tag `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) esiste.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | autore immagine, utilizzato da Windows Explorer. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Ottiene il soggetto dell'immagine, utilizzato da Windows Explorer.

Valore: Immagine soggetto, utilizzata da Windows Explorer.

**Returns:**
java.lang.String - immagine soggetto, utilizzata da Windows Explorer.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Imposta l'immagine soggetto, utilizzata da Windows Explorer.

Valore: Immagine soggetto, utilizzata da Windows Explorer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | immagine soggetto, utilizzata da Windows Explorer. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Ottiene informazioni sull'immagine, utilizzate da Windows Explorer.

Valore: Informazioni sull'immagine, utilizzate da Windows Explorer.

**Returns:**
java.lang.String - informazioni sull'immagine, utilizzate da Windows Explorer.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Imposta informazioni sull'immagine, utilizzate da Windows Explorer.

Valore: Informazioni sull'immagine, utilizzate da Windows Explorer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | informazioni sull'immagine, utilizzate da Windows Explorer. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Ottiene i dati Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Imposta i dati Exif.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Dati Exif. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Rimuove il tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tag | int | Il tag da rimuovere. |

**Returns:**
boolean - true se rimosso con successo
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Rimuove i tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tag | int[] | I tag da rimuovere. |

**Returns:**
boolean - `` se la dimensione della collezione di tag è cambiata.
### validate() {#validate--}
```
public void validate()
```


Convalida se le opzioni hanno una combinazione valida di tag

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Aggiunge i tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag da aggiungere. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Aggiunge un nuovo tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Il tag da aggiungere. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Ottiene l'istanza del tag per tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagKey | int | La chiave del tag. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
