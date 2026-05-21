---
title: "OdgImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola il formato di file immagine vettoriale OpenDocument Graphic ODG con la nostra API, ampiamente utilizzata dalle applicazioni OpenOffice e LibreOffice Draw per memorizzare gli elementi di disegno in formato vettoriale."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

Manipola il formato di file immagine vettoriale OpenDocument Graphic (ODG) con la nostra API, ampiamente utilizzata dalle applicazioni OpenOffice e LibreOffice Draw per memorizzare gli elementi di disegno in formato vettoriale. Analizza i documenti in modo fluido, accedi alle pagine, ridimensiona e ruota le immagini, garantendo un'elaborazione efficiente e una personalizzazione dei file ODG per soddisfare i tuoi requisiti specifici.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Avvia una nuova creazione dell'oggetto della classe [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) con l'inizio di una nuova istanza. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Progettato per un'integrazione senza soluzione di continuità nelle soluzioni software, il costruttore [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) inizializza una nuova istanza sfruttando un contenitore di flusso. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupera facilmente il valore del formato file con questa proprietà intuitiva. |
| [getPages()](#getPages--) | Recuperando la collezione di pagine, questa proprietà consente di accedere all'intero insieme di pagine associate a un'immagine. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Usare Aspose.Imaging.Image.Load è un modo unificato per caricare un'immagine.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // Converti a OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Ottieni tutte le pagine
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Esegui qualche elaborazione dell'immagine
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Avvia una nuova creazione dell'oggetto della classe [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) con l'inizio di una nuova istanza. Sfrutta il potenziale di un contenitore di flusso accoppiato a parametri di opzioni di caricamento, mantenendo un costruttore versatile per caricare le immagini senza soluzione di continuità. Questo costruttore consente una gestione efficiente delle immagini, offrendo configurazioni di caricamento personalizzabili per una maggiore adattabilità e prestazioni in scenari diversi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il flusso. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Progettato per un'integrazione senza soluzione di continuità nelle soluzioni software, il costruttore [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) inizializza una nuova istanza sfruttando un contenitore di flusso. Questo metodo garantisce una gestione efficiente dei dati delle immagini ODG negli ambienti software, ottimizzando l'utilizzo delle risorse e facilitando flussi di lavoro di elaborazione delle immagini senza interruzioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore dello stream. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera facilmente il valore del formato file con questa proprietà intuitiva. Ideale per gli sviluppatori che cercano un accesso rapido alle informazioni sul formato file.

**Returns:**
long - un valore del formato file
### getPages() {#getPages--}
```
public Image[] getPages()
```


Recuperando la collezione di pagine, questa proprietà consente di accedere all'intero insieme di pagine associate a un'immagine. Accedendo a questa proprietà, gli sviluppatori possono iterare tra le pagine individuali, recuperare pagine specifiche in base al loro indice o eseguire operazioni batch sull'intera collezione.

**Returns:**
com.aspose.imaging.Image[] - le pagine.
