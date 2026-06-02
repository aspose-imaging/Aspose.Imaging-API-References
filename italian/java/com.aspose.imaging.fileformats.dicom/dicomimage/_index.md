---
title: "DicomImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Questa classe implementa il supporto al formato immagine raster DICOM (Digital Imaging and Communications in Medicine) e offre una soluzione completa per l'elaborazione delle immagini DICOM con precisione e flessibilità."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Questa classe implementa il supporto al formato immagine raster DICOM (Digital Imaging and Communications in Medicine) e offre una soluzione completa per l'elaborazione delle immagini DICOM con precisione e flessibilità. È possibile manipolare senza soluzione di continuità le pagine delle immagini, comprese le operazioni per ottenere, aggiungere o rimuovere pagine, e controllare le pagine predefinite e attive. Con capacità di gestire canali alfa, incorporare metadati XMP, ridimensionare, ruotare, ritagliare, binarizzare, regolare, applicare filtri e convertire in altri formati raster. Questa API consente agli sviluppatori di gestire efficacemente le immagini DICOM soddisfacendo le diverse esigenze applicative nei contesti di imaging medico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | Inizializza facilmente una nuova istanza della classe DicomImage con questo costruttore, utilizzando i parametri dicomOptions. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Inizializza una nuova istanza della classe DicomImage in modo fluido utilizzando i parametri stream e loadOptions in questo costruttore. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | Crea una nuova istanza della classe DicomImage utilizzando un parametro stream in questo costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageCount()](#getPageCount--) | Recupera il conteggio totale delle pagine dell'immagine con questa proprietà intuitiva. |
| [getPages()](#getPages--) | Accedi alle pagine dell'immagine con questa proprietà intuitiva. |
| [getFileInfo()](#getFileInfo--) | Recupera facilmente informazioni preziose dell'intestazione dal file DICOM con questa proprietà intuitiva. |
| [getDicomPages()](#getDicomPages--) | Accedi alle pagine dell'immagine con questa proprietà intuitiva. |
| [getActivePage()](#getActivePage--) | Accedi alla pagina attiva dell'immagine con questa proprietà intuitiva. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | Gestisci la pagina attiva dell'immagine con questa proprietà intuitiva. |
| [getActivePageIndex()](#getActivePageIndex--) | Recupera facilmente l'indice della pagina attiva con questa proprietà intuitiva. |
| [getFileFormat()](#getFileFormat--) | Recupera facilmente il valore del formato file con questa proprietà intuitiva. |
| [hasAlpha()](#hasAlpha--) | Recupera facilmente se l'immagine ha un canale alfa con questa proprietà intuitiva. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Espandi la tua collezione di immagini aggiungendo una nuova pagina con questo metodo intuitivo. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Conserva i dati dell'oggetto salvandoli nella posizione del file designato (indice + nome file) insieme al formato file e alle opzioni specificati. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Regola la risoluzione di questo [RasterImage](../../com.aspose.imaging/rasterimage) con precisione usando questo metodo diretto. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Ridimensiona l'immagine mantenendo le proporzioni con questo metodo conveniente. |
| [addPage()](#addPage--) | Aggiungi una nuova pagina alla fine dell'elenco delle pagine dell'immagine con questo metodo diretto. |
| [insertPage(int pageIndex)](#insertPage-int-) | Inserisci una nuova pagina nell'elenco delle pagine dell'immagine a un indice specificato con questo metodo intuitivo. |
| [removePage(int pageIndex)](#removePage-int-) | Elimina la pagina all'indice specificato dall'elenco delle pagine con questo metodo conveniente. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Ruota l'immagine attorno al suo centro con questo metodo conveniente. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Regola le dimensioni dell'immagine con questo metodo diretto. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Regola la larghezza dell'immagine mantenendo le proporzioni con questo metodo conveniente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Regola l'altezza dell'immagine mantenendo le proporzioni con questo metodo intuitivo. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Manipola facilmente il fotogramma attivo ruotando, capovolgendo o eseguendo entrambe le azioni simultaneamente con questo metodo diretto. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Migliora l'immagine corrente applicando effetti di dithering con questo metodo diretto. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia l'immagine per rimuovere aree indesiderate e concentrarti sul contenuto essenziale con questo metodo semplice. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Regola l'area di ritaglio dell'immagine applicando spostamenti con questo metodo versatile. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Converti facilmente l'immagine in un formato binario usando una soglia predefinita con questo metodo diretto. |
| [binarizeOtsu()](#binarizeOtsu--) | Applica la sogliatura Otsu per binarizzare l'immagine, determinando automaticamente il valore di soglia ottimale basato sull'istogramma dell'immagine. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarizza le immagini con l'algoritmo di sogliatura adattiva di Bradley, sfruttando la sogliatura dell'immagine integrale per migliorare le prestazioni. |
| [grayscale()](#grayscale--) | Trasforma facilmente le immagini nella loro rappresentazione in scala di grigi, semplificando le attività di analisi visiva e di elaborazione. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Migliora la qualità dell'immagine e regola la stessa con la correzione gamma, una tecnica potente per affinare l'aspetto visivo. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Ottieni regolazioni di colore precise applicando la correzione gamma in modo indipendente ai componenti rosso, verde e blu di un'immagine. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Migliora la luminanza dell'immagine con la regolazione di `brightness`, un metodo parametrizzato che consente agli sviluppatori di affinare finemente la luminosità delle immagini. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Migliora il contrasto di [Image](../../com.aspose.imaging/image) con questo metodo intuitivo, che regola la differenza tra le aree chiare e scure. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Migliora senza sforzo aree specifiche della tua immagine applicando filtri a rettangoli designati. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Regola le dimensioni della tua immagine con questo semplice metodo di ridimensionamento. |
| [cacheData()](#cacheData--) | Questo metodo memorizza nella cache i dati in modo efficiente, ottimizzando le prestazioni e garantendo un accesso rapido quando necessario. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// Carica un'immagine
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Disegna qualcosa usando la grafica vettoriale.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Salva i pixel dell'immagine disegnata. Ora si trovano nella prima pagina dell'immagine Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Aggiungi alcune pagine dopo, rendendole più scure.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Aggiungi alcune pagine davanti alla pagina principale, rendendole più luminose.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Salva l'immagine multipagina creata nel file di output.
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


Inizializza senza sforzo una nuova istanza della classe DicomImage con questo costruttore, utilizzando i parametri dicomOptions. Perfetto per gli sviluppatori che desiderano immergersi rapidamente ed efficientemente negli oggetti [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | Le opzioni dicom (ignorate per ora). |
| width | int | La larghezza. |
| height | int | L'altezza. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


Inizia una nuova istanza della classe DicomImage in modo fluido impiegando un flusso e i parametri loadOptions in questo costruttore. Ideale per gli sviluppatori desiderosi di iniziare a lavorare con gli oggetti [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) rapidamente ed efficacemente nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


Crea una nuova istanza della classe DicomImage utilizzando un parametro stream in questo costruttore. Perfetto per gli sviluppatori che cercano un modo semplificato per inizializzare gli oggetti [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) da flussi di dati esistenti nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il conteggio totale delle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano un accesso rapido al numero di pagine all'interno di un'immagine, garantendo una navigazione e una gestione efficienti.

**Returns:**
int - il conteggio delle pagine.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accedi alle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano interagire con le singole pagine all'interno dell'immagine, garantendo una navigazione e una manipolazione fluide.

**Returns:**
com.aspose.imaging.Image[] - le pagine.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


Recupera senza sforzo informazioni preziose dall'intestazione del file DICOM con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano un accesso rapido ai dettagli essenziali contenuti nel file DICOM, garantendo un'estrazione e un'analisi dei dati efficienti.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


Accedi alle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano interagire con le singole pagine all'interno dell'immagine, garantendo una navigazione e una manipolazione fluide.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] - le pagine.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


Accedi alla pagina attiva dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano passare dinamicamente tra le pagine di immagini multipagina, garantendo una navigazione e un'elaborazione efficienti.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


Gestisci la pagina attiva dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano passare dinamicamente tra le pagine di immagini multipagina, garantendo una navigazione e un'elaborazione efficienti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | la pagina attiva. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


Recupera senza sforzo l'indice della pagina attiva con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano un accesso rapido all'indice della pagina corrente nelle immagini multipagina, garantendo una navigazione e un'elaborazione efficienti.

**Returns:**
int - l'indice della pagina attiva.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera senza sforzo il valore del formato file con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano un accesso rapido al formato del file immagine, garantendo una gestione e un'elaborazione efficienti in base al tipo di file.

**Returns:**
long - un valore del formato file [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Recupera facilmente se l'immagine ha un canale alfa con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano determinare se l'immagine contiene informazioni sulla trasparenza, garantendo una gestione precisa dei dati del canale alfa nelle attività di elaborazione delle immagini.

**Returns:**
boolean - true se l'immagine ha il canale alfa.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Espandi la tua collezione di immagini aggiungendo una nuova pagina con questo metodo intuitivo. Ideale per gli sviluppatori che desiderano aggiungere dinamicamente pagine a immagini multipagina, garantendo un'espansione fluida e un'organizzazione del contenuto dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La pagina da aggiungere. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


Conserva i dati dell'oggetto salvandoli nella posizione del file designato (indice + nome file) insieme al formato file e alle opzioni specificate. Ideale per gli sviluppatori che desiderano archiviare in modo sicuro i dati in vari formati mantenendo flessibilità e controllo sui parametri di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Le opzioni. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Regola la risoluzione di questo [RasterImage](../../com.aspose.imaging/rasterimage) con precisione usando questo metodo semplice. Ideale per gli sviluppatori che desiderano adattare la risoluzione dell'immagine a requisiti specifici, garantendo una qualità di visualizzazione ottimale e una gestione delle dimensioni del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpiX | double | La risoluzione orizzontale, in punti per pollice, del [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La risoluzione verticale, in punti per pollice, del [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Ridimensiona l'immagine mantenendo le proporzioni con questo metodo comodo. Ideale per gli sviluppatori che desiderano regolare le dimensioni dell'immagine proporzionalmente, garantendo coerenza e preservando le proporzioni del contenuto originale. Il ridimensionamento proporzionale ridimensionerà ogni fotogramma secondo il rapporto di `newWidth`/width e `newHeight`/height.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


Aggiungi una nuova pagina alla fine dell'elenco delle pagine dell'immagine con questo metodo semplice. Ideale per gli sviluppatori che desiderano espandere dinamicamente immagini multipagina, garantendo un'integrazione fluida e un'organizzazione del contenuto dell'immagine.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


Inserisci una nuova pagina nell'elenco delle pagine dell'immagine a un indice specificato con questo metodo intuitivo. Ideale per gli sviluppatori che desiderano un controllo preciso sulla disposizione delle pagine in immagini multipagina, garantendo un'organizzazione fluida e una personalizzazione del contenuto dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageIndex | int | Indice della pagina. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Disegna qualcosa usando la grafica vettoriale.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Salva i pixel dell'immagine disegnata. Ora si trovano nella prima pagina dell'immagine Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Aggiungi alcune pagine dopo, rendendole più scure.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Aggiungi alcune pagine davanti alla pagina principale, rendendole più luminose.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Salva l'immagine multipagina creata nel file di output.
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


Elimina la pagina all'indice specificato dall'elenco delle pagine con questo metodo comodo. Ideale per gli sviluppatori che desiderano un controllo preciso sulla gestione delle immagini multipagina, garantendo un'organizzazione fluida e una personalizzazione del contenuto dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageIndex | int | Indice della pagina. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Ruota l'immagine attorno al suo centro con questo metodo comodo. Ideale per gli sviluppatori che desiderano regolare l'orientamento dell'immagine dinamicamente, garantendo una presentazione ottimale e un allineamento all'interno delle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | Se impostato su `true` la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DICOM da un flusso di file.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // Ruota l'immagine attorno al centro di 60 gradi in senso orario.
        // Usa il grigio come colore di sfondo.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Nota che se l'immagine è a colori, verrà automaticamente convertita al formato in scala di grigi secondo le opzioni seguenti.
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // Crea un array di fotogrammi TIFF.
        // Il numero dei fotogrammi è uguale al numero delle pagine DJVU.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // Salva ogni pagina come un singolo fotogramma TIFF.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // Crea un fotogramma TIFF basato sulla pagina DICOM.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // Componi un'immagine TIFF dai fotogrammi.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // Salva su un file.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Regola le dimensioni dell'immagine con questo metodo semplice. Ideale per gli sviluppatori che desiderano ridimensionare dinamicamente le immagini, garantendo che si adattino perfettamente a vari contesti e layout all'interno delle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Riduci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Regola la larghezza dell'immagine mantenendo le proporzioni con questo metodo comodo. Ideale per gli sviluppatori che desiderano ridimensionare le immagini proporzionalmente, garantendo risultati coerenti e visivamente gradevoli in diversi ambienti di visualizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| resizeType | int | Tipo di ridimensionamento. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Questo esempio carica un'immagine DICOM e la ridimensiona proporzionalmente usando vari metodi di ridimensionamento. Viene specificata solo la larghezza, l'altezza viene calcolata automaticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Riduci di 2 volte usando il ricampionamento Bilineare.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Regola l'altezza dell'immagine mantenendo il suo rapporto d'aspetto con questo metodo intuitivo. Perfetto per gli sviluppatori che desiderano ridimensionare dinamicamente le immagini preservando le loro proporzioni, garantendo una visualizzazione ottimale e usabilità nelle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |
| resizeType | int | Tipo di ridimensionamento. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Questo esempio carica un'immagine DICOM e la ridimensiona proporzionalmente usando vari metodi di ridimensionamento. Viene specificata solo l'altezza, la larghezza viene calcolata automaticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Riduci di 2 volte usando il ricampionamento Bilineare.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Manipola facilmente il fotogramma attivo ruotandolo, capovolgendolo o eseguendo entrambe le azioni simultaneamente con questo metodo semplice. Ideale per gli sviluppatori che devono regolare dinamicamente l'orientamento di fotogrammi specifici all'interno delle sequenze di immagini, garantendo una presentazione e un allineamento ottimali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Ruota, capovolgi e salva nel file di output.
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Migliora l'immagine corrente applicando effetti di dithering con questo metodo semplice. Perfetto per gli sviluppatori che vogliono aggiungere texture e profondità alle immagini, migliorandone la qualità visiva e l'appeal complessivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Esegui il dithering a soglia usando una palette di colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Esegui il dithering Floyd usando una palette di colori a 1 bit che contiene solo 2 colori - nero e bianco.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia l'immagine per rimuovere aree indesiderate e focalizzarti sul contenuto essenziale con questo metodo semplice. Ideale per gli sviluppatori che desiderano personalizzare la composizione visiva delle immagini, assicurando che trasmettano il messaggio desiderato in modo efficace.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |


**Example: The following example crops a DICOM image.**
Il seguente esempio ritaglia un'immagine DICOM. L'area di ritaglio è specificata tramite Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Ritaglia l'immagine. L'area di ritaglio è la zona rettangolare centrale dell'immagine.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // Salva l'immagine ritagliata in PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Regola l'area di ritaglio dell'immagine applicando spostamenti con questo metodo versatile. Perfetto per gli sviluppatori che necessitano di un controllo preciso sul processo di ritaglio, garantendo che i dettagli importanti siano conservati eliminando gli elementi superflui.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | int | Lo spostamento sinistro. |
| rightShift | int | Lo spostamento destro. |
| topShift | int | Lo spostamento superiore. |
| bottomShift | int | Lo spostamento inferiore. |


**Example: The following example crops a DICOM image.**
Il seguente esempio ritaglia un'immagine DICOM. L'area di ritaglio è specificata tramite i margini Sinistra, Alto, Destra, Basso.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Ritaglia di nuovo. Imposta un margine del 10% della dimensione dell'immagine.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Salva l'immagine ritagliata in PNG.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Converti facilmente l'immagine in formato binario usando una soglia predefinita con questo metodo semplice. Ideale per gli sviluppatori che desiderano semplificare le operazioni di elaborazione delle immagini segmentando l'immagine in componenti di primo piano e sfondo basate su livelli di intensità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato il valore 255, altrimenti 0. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
Il seguente esempio binarizza un'immagine DICOM con la soglia predefinita. Le immagini binarizzate contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarizza l'immagine con un valore di soglia di 127.
    // Se il valore di grigio corrispondente di un pixel è maggiore di 127, gli verrà assegnato un valore di 255, altrimenti 0.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Applica la soglia di Otsu per binarizzare l'immagine, determinando automaticamente il valore di soglia ottimale basato sull'istogramma dell'immagine. Perfetto per gli sviluppatori che cercano un metodo affidabile per segmentare le immagini in regioni di primo piano e sfondo con minima interferenza manuale.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
Il seguente esempio binarizza un'immagine DICOM con la soglia di Otsu. Le immagini binarizzate contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarizza l'immagine con la sogliatura di Otsu.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarizza le immagini con l'algoritmo di soglia adattiva di Bradley, sfruttando la soglia dell'immagine integrale per migliorare le prestazioni. Ideale per gli sviluppatori che desiderano segmentare automaticamente le immagini basandosi su variazioni locali di luminosità, garantendo un rilevamento e un'estrazione accurati degli oggetti in condizioni di illuminazione variabili.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel. |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
Il seguente esempio binarizza un'immagine DICOM con l'algoritmo di soglia adattiva di Bradley con la dimensione della finestra specificata. Le immagini binarizzate contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarizza l'immagine con una differenza di luminosità di 5. La luminosità è la differenza tra un pixel e la media di una finestra 10 x 10 di pixel centrata su quel pixel.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Trasforma facilmente le immagini nella loro rappresentazione in scala di grigi, semplificando l'analisi visiva e le attività di elaborazione. Perfetto per gli sviluppatori che desiderano migliorare la chiarezza delle immagini, ridurre la complessità e facilitare algoritmi efficienti basati sulla scala di grigi per diverse applicazioni.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
Il seguente esempio trasforma un'immagine DICOM a colori nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da tonalità di grigio e contengono solo informazioni di intensità.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Migliora la qualità dell'immagine e regola la gamma con la correzione gamma, una tecnica potente per perfezionare l'aspetto visivo. Perfetto per gli sviluppatori che mirano a ottimizzare la presentazione dell'immagine, regolare il bilanciamento del colore e garantire una resa coerente su diversi dispositivi e ambienti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Imposta il coefficiente gamma per i canali rosso, verde e blu.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Ottieni regolazioni di colore precise applicando la correzione gamma indipendentemente ai componenti rosso, verde e blu di un'immagine. Questo metodo garantisce un bilanciamento cromatico accurato e un output visivo ottimale, soddisfacendo gli sviluppatori che cercano un controllo granulare sul rendering e sulla precisione del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Migliora la luminanza dell'immagine con la regolazione di `brightness`, un metodo parametrizzato che consente agli sviluppatori di sintonizzare finemente la luminosità delle immagini. Questa funzione intuitiva permette agli sviluppatori di manipolare senza sforzo la luminosità dell'immagine, offrendo flessibilità e controllo sull'estetica visiva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Imposta il valore di luminosità. I valori accettati per la luminosità sono nell'intervallo [-255, 255].
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Migliora il contrasto dell'[Image](../../com.aspose.imaging/image) con questo metodo intuitivo, che regola la disparità tra le aree chiare e scure. Migliora la chiarezza e la definizione visiva senza sforzo, fornendo agli sviluppatori un controllo intuitivo sul contrasto dell'immagine per una resa ottimale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Imposta il valore di contrasto. I valori accettati per il contrasto sono nell'intervallo [-100f, 100f].
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Migliora senza sforzo aree specifiche della tua immagine applicando filtri a rettangoli designati. Questo metodo fornisce agli sviluppatori un controllo preciso sulla manipolazione dell'immagine, consentendo regolazioni mirate per ottenere gli effetti visivi desiderati con facilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Regola le dimensioni della tua immagine con questo semplice metodo di ridimensionamento. Che tu debba ridurre o ingrandire l'immagine, questa funzione garantisce che le tue esigenze di ridimensionamento siano soddisfatte in modo efficiente e accurato, rendendola perfetta per gli sviluppatori che cercano regolazioni rapide e facili delle dimensioni dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// L'algoritmo adattivo basato su funzione razionale ponderata e mescolata e interpolazione lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Il piccolo filtro rettangolare
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Il numero di colori nella tavolozza.
resizeSettings.setEntriesCount(256);

// La quantizzazione del colore non è utilizzata
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Il metodo euclideo
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Riduci di 2 volte usando il ricampionamento adattivo.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Salva in PNG
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Questo metodo memorizza nella cache i dati in modo efficiente, ottimizzando le prestazioni e garantendo un accesso rapido quando necessario. Ideale per gli sviluppatori che desiderano migliorare la velocità e l'efficienza delle loro applicazioni gestendo in modo intelligente le risorse di dati.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file DICOM.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Questa chiamata memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento aggiuntivo di dati dal flusso di dati sottostante.
    image.cacheData();

    // Oppure puoi memorizzare nella cache le pagine individualmente.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

