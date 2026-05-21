---
title: "SvgImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola i file immagine SVG (Scalar Vector Graphics) con la nostra API sfruttando la potenza del formato di testo basato su XML per una personalizzazione e scalabilità senza soluzione di continuità."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

Manipola i file immagine Scalar Vector Graphics (SVG) con la nostra API, sfruttando la potenza del formato di testo basato su XML per una personalizzazione e scalabilità senza soluzione di continuità. Carica facilmente le immagini SVG, rasterizza gli elementi vettoriali e convertili in altri formati, controllando i livelli di compressione per ottimizzare le dimensioni del file e la qualità per i tuoi progetti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Istanzia un nuovo oggetto della classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), utilizzando il percorso specificato per individuare e caricare l'immagine. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Crea una nuova istanza della classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), caricando l'immagine dallo stream fornito. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Istanzia un nuovo oggetto [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con la larghezza e l'altezza specificate. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Crea una nuova istanza della classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con le opzioni SVG specificate, la larghezza dell'immagine e i parametri di altezza. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isCached()](#isCached--) | Recupera un valore booleano che indica se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di ulteriori operazioni di lettura dei dati. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera il conteggio dei bit per pixel dell'immagine. |
| [getFileFormat()](#getFileFormat--) | Recupera il formato file dell'immagine, fornendo metadati essenziali per l'elaborazione e i controlli di compatibilità. |
| [cacheData()](#cacheData--) | Metti nella cache i dati e garantisci che non verrà effettuato ulteriore caricamento dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine per adattarla alle dimensioni specificate mantenendo il rapporto d'aspetto. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia il rettangolo specificato. |
| [rotate(float angle)](#rotate-float-) | Ruota l'immagine attorno al centro. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Applica una palette specificata all'immagine, consentendo la personalizzazione degli schemi di colore per scopi estetici o funzionali. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine SVG da uno stream di file.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // Per rasterizzare SVG è necessario specificare le opzioni di rasterizzazione.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
Il seguente esempio mostra come convertire immagini compresse (*.emz,*.wmz, *.svgz) in formato raster
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Istanzia un nuovo oggetto della classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), utilizzando il percorso specificato per individuare e caricare l'immagine. Questo costruttore facilita la creazione di istanze di immagini SVG da file esterni, consentendo un'integrazione senza soluzione di continuità nei sistemi software e nei flussi di lavoro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Crea una nuova istanza della classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), caricando l'immagine dallo stream fornito. Questo costruttore consente il caricamento diretto di immagini SVG da stream, migliorando la flessibilità e l'efficienza nella gestione delle risorse immagine all'interno delle applicazioni software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Istanzia un nuovo oggetto [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con la larghezza e l'altezza specificate. Questo costruttore consente agli sviluppatori di creare immagini SVG con dimensioni predefinite, facilitando un controllo preciso delle dimensioni dell'immagine durante l'inizializzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Crea una nuova istanza della classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) con le opzioni SVG specificate, la larghezza dell'immagine e i parametri di altezza. Questo costruttore consente agli sviluppatori di inizializzare immagini SVG con opzioni e dimensioni personalizzate, offrendo flessibilità nella gestione del contenuto e del layout SVG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | Le opzioni SVG. |
| width | int | Larghezza immagine. |
| height | int | Altezza immagine. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Restituisce un valore booleano che indica se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di ulteriori operazioni di lettura dei dati. Questa proprietà fornisce informazioni sullo stato corrente della cache, ottimizzando il recupero e l'elaborazione dei dati per migliorare le prestazioni e l'efficienza.

**Returns:**
boolean - `true` se i dati dell'oggetto sono nella cache; altrimenti, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine. È importante notare che questo parametro non è applicabile alle immagini vettoriali, poiché non sono misurate in pixel. Questa proprietà fornisce informazioni cruciali sulla profondità di colore dell'immagine, facilitando le attività di elaborazione e manipolazione.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Restituisce il formato file dell'immagine, fornendo metadati essenziali per l'elaborazione e i controlli di compatibilità. Questa proprietà è fondamentale per determinare le strategie di decodifica e codifica appropriate per gestire i dati dell'immagine in modo efficace su diversi sistemi e applicazioni.

**Returns:**
long - formato file
### cacheData() {#cacheData--}
```
public void cacheData()
```


Metti nella cache i dati e garantisci che non verrà effettuato alcun ulteriore caricamento dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Questa ottimizzazione migliora le prestazioni eliminando operazioni di recupero dati ridondanti, risultando particolarmente vantaggiosa in scenari che richiedono accessi frequenti ai dati dell'immagine.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ridimensiona l'immagine per adattarla alle dimensioni specificate mantenendo il rapporto d'aspetto. Questo metodo offre un modo pratico per regolare le dimensioni dell'immagine senza distorcere le proporzioni, garantendo una visualizzazione o un archivio ottimale secondo le dimensioni desiderate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Ruota l'immagine attorno al centro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Applica una tavolozza specificata all'immagine, consentendo la personalizzazione degli schemi di colore per scopi estetici o funzionali. Questo metodo offre flessibilità nella gestione delle tavolozze di colore per soddisfare varie esigenze di progettazione o di applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

