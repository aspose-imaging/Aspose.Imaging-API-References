---
title: "BigTiffOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per la creazione del formato immagine raster BigTIFF è specificamente progettata per soddisfare i requisiti unici delle applicazioni che utilizzano dati di imaging su larga scala provenienti da scanner."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

L'API per la creazione del formato immagine raster BigTIFF è specificamente progettata per soddisfare i requisiti unici delle applicazioni che utilizzano dati di imaging su larga scala provenienti da scanner. Questa API facilita la generazione fluida del formato BigTIFF, che combina più immagini TIFF in un'unica immagine completa. Garantisce un'elaborazione efficiente di grandi quantità di dati immagine, offrendo agli sviluppatori uno strumento potente per creare e manipolare formati ad alta risoluzione e multi-immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Clona questa istanza. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). Per impostazione predefinita viene utilizzata la convenzione little endian.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | int | Il formato file Tiff previsto. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | La sorgente delle opzioni. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag per l'inizializzazione delle opzioni. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Inizializza una nuova istanza della classe [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | int | Il formato file Tiff previsto. |
| byteOrder | int | L'ordine dei byte del formato file tiff da utilizzare. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona questa istanza.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
