---
title: "DjvuImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe documento DjVu supporta il formato file grafico e facilita la gestione senza soluzione di continuità di documenti e libri scansionati, integrando testo, disegni, immagini e foto in un unico formato."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

La classe documento DjVu supporta il formato file grafico e facilita la gestione senza soluzione di continuità di documenti e libri scansionati, integrando testo, disegni, immagini e foto in un unico formato. Supportando operazioni multipagina, è possibile accedere in modo efficiente a identificatori unici dei documenti, contare le pagine, impostare le pagine attive e recuperare pagine specifiche del documento. Con funzionalità per ridimensionamento, rotazione, dithering, ritaglio, trasformazione in scala di grigi, correzioni gamma, regolazioni e applicazione di filtri, questa classe consente una manipolazione precisa e un miglioramento delle immagini DjVu per soddisfare esigenze applicative diverse con facilità e precisione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Inizia a lavorare con le immagini DjVu inizializzando una nuova istanza della classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) utilizzando un parametro Stream. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Inizia a lavorare con le immagini DjVu senza problemi con questo costruttore, che inizializza una nuova istanza della classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) utilizzando i parametri Stream e LoadOptions. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Inizia a lavorare con le immagini DjVu senza problemi con questo costruttore, che inizializza una nuova istanza della classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) utilizzando i parametri Stream e LoadOptions. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Si verifica quando il valore di una proprietà cambia. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Carica il tuo documento DjVu con questo metodo. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Carica il documento. |
| [getIdentifier()](#getIdentifier--) | Ottiene l'identificatore univoco per il documento |
| [getPageCount()](#getPageCount--) | Recupera il numero totale di pagine nella tua collezione di immagini DjVu con questa proprietà. |
| [getPages()](#getPages--) | Accedi alle singole pagine della tua collezione di immagini DjVu con questa proprietà. |
| [getDjvuPages()](#getDjvuPages--) | Recupera rapidamente tutte le pagine contenute nel tuo documento DjVu utilizzando questa proprietà. |
| [getActivePage()](#getActivePage--) | Naviga nel tuo documento DjVu accedendo o impostando la pagina attualmente attiva tramite questa proprietà. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Naviga nel tuo documento DjVu accedendo o impostando la pagina attualmente attiva tramite questa proprietà. |
| [getFirstPage()](#getFirstPage--) | Accedi alla prima pagina del tuo documento DjVu con questa proprietà. |
| [getLastPage()](#getLastPage--) | Recupera l'ultima pagina del tuo documento DjVu utilizzando questa proprietà. |
| [getNextPage()](#getNextPage--) | Naviga nel tuo documento DjVu accedendo alla pagina successiva con questa pratica proprietà. |
| [getPreviousPage()](#getPreviousPage--) | Sposta rapidamente indietro nel tuo documento DjVu durante la visualizzazione o l'elaborazione accedendo alla pagina precedente con questa pratica proprietà. |
| [getFileFormat()](#getFileFormat--) | Ottieni le informazioni sul formato file associate al tuo file immagine DjVu. |
| [hasAlpha()](#hasAlpha--) | Determina rapidamente se il tuo file immagine DjVu contiene un canale alfa. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Ruota l'immagine attorno al suo centro con il metodo Rotate della classe RasterCachedMultipageImage. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine usando il metodo \\`Resize\\`, fornendo un modo semplice ed efficace per regolare le dimensioni delle tue immagini secondo le tue esigenze. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Il metodo \\`ResizeWidthProportionally\\` offre una soluzione pratica per regolare la larghezza della tua immagine mantenendo il suo rapporto d'aspetto. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Il metodo \\`ResizeHeightProportionally\\` ti consente di regolare l'altezza della tua immagine preservando il suo rapporto d'aspetto. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Il metodo \\`RotateFlip\\` offre opzioni di manipolazione versatili per la tua immagine, consentendoti di ruotare, capovolgere o eseguire entrambe le operazioni sul fotogramma attivo in modo indipendente. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | La funzione \"Dither\" applica un effetto di dithering alla tua immagine, migliorandone la qualità visiva riducendo le bande e migliorando le transizioni di colore. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | \"Crop\" ritaglia la tua immagine per concentrarsi su dettagli specifici o rimuovere elementi indesiderati, migliorandone la composizione e l'impatto visivo. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop with shifts ti consente di regolare con precisione la posizione e le dimensioni dell'area ritagliata all'interno di un'immagine. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | La binarizzazione con una soglia predefinita semplifica le immagini complesse in rappresentazioni binarie, dove i pixel sono classificati come neri o bianchi in base alla loro intensità rispetto a un valore di soglia specificato. |
| [binarizeOtsu()](#binarizeOtsu--) | La binarizzazione usando la soglia di Otsu è una tecnica che calcola automaticamente un valore di soglia ottimale basato sull'istogramma dell'immagine. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | La binarizzazione usando l'algoritmo di soglia adattiva di Bradley con soglia di immagine integrale è un metodo che calcola una soglia locale per ogni pixel basandosi su un vicinato locale. |
| [grayscale()](#grayscale--) | La trasformazione in scala di grigi converte un'immagine in una rappresentazione in bianco e nero, dove l'intensità di ogni pixel è rappresentata da un unico valore che varia dal nero al bianco. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | La correzione gamma, specificamente per i canali rosso, verde e blu, comporta la regolazione della luminosità di ciascuna componente colore separatamente. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | La correzione gamma viene applicata a un'immagine con parametri personalizzabili per i canali rosso, verde e blu, consentendo una regolazione precisa del bilanciamento del colore e della luminosità. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la `brightness` di un'immagine usando un parametro specificato, fornendo controllo sui livelli di luminanza per una chiarezza visiva ottimale. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Migliora il contrasto dell'[Immagine](../../com.aspose.imaging/image) per migliorare la chiarezza visiva e evidenziare i dettagli con questo metodo, che regola la differenza di luminosità tra le aree chiare e scure. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Applica filtri a un'area rettangolare specificata all'interno dell'immagine per migliorare o modificare il suo aspetto. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona l'immagine alla larghezza e altezza specificate applicando impostazioni aggiuntive secondo necessità. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati in modo privato per ottimizzare le prestazioni e ridurre la necessità di recuperi ripetuti dei dati da fonti esterne. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Salva ogni pagina come immagine PNG individuale.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Genera un nome file basato sul numero di pagina.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Inizia a lavorare con le immagini DjVu inizializzando una nuova istanza della classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando un parametro Stream. Perfetto per gli sviluppatori che desiderano un'integrazione fluida dell'elaborazione delle immagini DjVu nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Inizia a lavorare con le immagini DjVu in modo fluido con questo costruttore, che inizializza una nuova istanza della classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando i parametri Stream e LoadOptions. Perfetto per gli sviluppatori che desiderano un controllo preciso sulle opzioni di caricamento delle immagini DjVu mantenendo semplicità ed efficienza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da cui caricare. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Inizia a lavorare con le immagini DjVu in modo fluido con questo costruttore, che inizializza una nuova istanza della classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando i parametri Stream e LoadOptions. Perfetto per gli sviluppatori che desiderano un controllo preciso sulle opzioni di caricamento delle immagini DjVu mantenendo semplicità ed efficienza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream | Lo stream da cui caricare. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Si verifica quando il valore di una proprietà cambia.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Carica il tuo documento DjVu con questo metodo. Semplifica il tuo processo accedendo rapidamente e importando i file DjVu nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Carica il documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Ottiene l'identificatore univoco per il documento

**Returns:**
int - L'identificatore.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il numero totale di pagine nella tua collezione di immagini DjVu con questa proprietà. Ideale per valutare rapidamente l'estensione del tuo documento o libro memorizzato in formato DjVu. Migliora l'efficienza del tuo flusso di lavoro con informazioni accurate sul conteggio delle pagine.

**Returns:**
int - Il conteggio delle pagine.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accedi alle singole pagine della tua collezione di immagini DjVu con questa proprietà. Semplifica la navigazione e la manipolazione del tuo documento o libro memorizzato in formato DjVu accedendo direttamente a ogni pagina. Migliora l'efficienza del tuo flusso di lavoro con un facile recupero delle pagine.

**Returns:**
com.aspose.imaging.Image[] - Le pagine.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Salva ogni pagina come immagine PNG individuale.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Genera un nome file basato sul numero di pagina.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Recupera rapidamente tutte le pagine contenute nel tuo documento DjVu usando questa proprietà. Semplifica il flusso di lavoro di elaborazione dei documenti accedendo e gestendo facilmente le singole pagine nei tuoi file DjVu. Migliora l'efficienza e ottimizza le tue attività con un comodo recupero delle pagine.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - Le pagine.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Naviga nel tuo documento DjVu accedendo o impostando la pagina attualmente attiva con questa proprietà. Passa senza soluzione di continuità tra le pagine per concentrarti su contenuti specifici e migliorare l'esperienza di visualizzazione del documento.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//L'output potrebbe apparire così:
//Il numero totale di pagine: 2
//Il numero della pagina attiva:    1
//Il numero della prima pagina:     1
//Il numero dell'ultima pagina:      2
//--------------------------------------------------
//Numero di pagina:     1
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
//--------------------------------------------------
//Numero di pagina:     2
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Naviga nel tuo documento DjVu accedendo o impostando la pagina attualmente attiva con questa proprietà. Passa senza soluzione di continuità tra le pagine per concentrarti su contenuti specifici e migliorare l'esperienza di visualizzazione del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | La pagina attiva. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Accedi alla prima pagina del tuo documento DjVu con questa proprietà. Recupera rapidamente la pagina iniziale per iniziare a visualizzare o elaborare il documento in modo efficiente.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//L'output potrebbe apparire così:
//Il numero totale di pagine: 2
//Il numero della pagina attiva:    1
//Il numero della prima pagina:     1
//Il numero dell'ultima pagina:      2
//--------------------------------------------------
//Numero di pagina:     1
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
//--------------------------------------------------
//Numero di pagina:     2
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Recupera l'ultima pagina del tuo documento DjVu usando questa proprietà. Accedi rapidamente alla pagina finale per scopi di visualizzazione o elaborazione con facilità.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//L'output potrebbe apparire così:
//Il numero totale di pagine: 2
//Il numero della pagina attiva:    1
//Il numero della prima pagina:     1
//Il numero dell'ultima pagina:      2
//--------------------------------------------------
//Numero di pagina:     1
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
//--------------------------------------------------
//Numero di pagina:     2
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Naviga nel tuo documento DjVu accedendo alla pagina successiva con questa pratica proprietà. Avanza rapidamente nella visualizzazione o nell'elaborazione del documento.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Spostati rapidamente all'indietro nella visualizzazione o nell'elaborazione del tuo documento DjVu accedendo alla pagina precedente con questa pratica proprietà. Naviga efficientemente attraverso il documento con facilità.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ottieni le informazioni sul formato file associate al tuo file immagine DjVu. Determina rapidamente il formato del tuo file per un'integrazione fluida nel tuo flusso di lavoro.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determina rapidamente se il tuo file immagine DjVu contiene un canale alfa. Semplifica il tuo flusso di lavoro verificando la presenza di informazioni sulla trasparenza nelle tue immagini.

**Returns:**
boolean - Il canale alfa è presente.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Ruota l'immagine attorno al suo centro con il metodo Rotate della classe RasterCachedMultipageImage. Questa comoda funzionalità consente di regolare facilmente l'orientamento delle immagini mantenendo la loro posizione centrale, migliorando le tue capacità di manipolazione delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | Se impostato su `true` la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ridimensiona l'immagine usando il metodo \\`Resize\\`, fornendo un modo semplice ed efficace per regolare le dimensioni delle tue immagini secondo le tue esigenze. Questa funzionalità versatile ti consente di scalare facilmente le immagini alla dimensione desiderata, migliorandone l'usabilità su varie piattaforme e applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Il metodo \\`ResizeWidthProportionally\\` offre una soluzione pratica per regolare la larghezza della tua immagine mantenendo il rapporto d'aspetto. Ridimensionando proporzionalmente la larghezza, puoi garantire che le tue immagini rimangano visivamente attraenti e coerenti su diversi dispositivi e dimensioni dello schermo, migliorandone la versatilità e l'usabilità in vari contesti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| resizeType | int | Tipo di ridimensionamento. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Questo esempio carica un'immagine DJVU e la ridimensiona proporzionalmente usando vari metodi di ridimensionamento. Viene specificata solo la larghezza, l'altezza viene calcolata automaticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Il metodo \\`ResizeHeightProportionally\\` ti consente di regolare l'altezza della tua immagine preservando il rapporto d'aspetto. Ciò garantisce che l'immagine mantenga le sue proporzioni, evitando distorsioni e preservando la sua integrità visiva. Che tu stia ottimizzando le immagini per pagine web, app mobili o media stampati, questo metodo assicura che le tue immagini abbiano il miglior aspetto su diverse piattaforme e dispositivi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |
| resizeType | int | Tipo di ridimensionamento. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Questo esempio carica un'immagine DJVU e la ridimensiona proporzionalmente usando vari metodi di ridimensionamento. Viene specificata solo l'altezza, la larghezza viene calcolata automaticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Il metodo \\`RotateFlip\\` offre opzioni di manipolazione versatili per la tua immagine, consentendo di ruotare, capovolgere o eseguire entrambe le operazioni sul fotogramma attivo in modo indipendente. Che tu stia modificando foto, creando grafiche o migliorando arte digitale, questo metodo fornisce un controllo preciso sull'orientamento e sulla composizione delle tue immagini, garantendo che soddisfino la tua visione creativa con facilità ed efficienza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e ribaltamento. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

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
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


La funzione "Dither" applica un effetto dithering alla tua immagine, migliorandone la qualità visiva riducendo le bande e migliorando le transizioni di colore. Che tu stia lavorando su arte digitale, fotografia o progetti di design grafico, questa funzionalità aggiunge un tocco professionale alle tue immagini, rendendole più fluide e raffinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Esegui il dithering a soglia usando una palette di colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Esegui il dithering Floyd usando una palette di colori a 1 bit che contiene solo 2 colori - nero e bianco.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


"Crop" ritaglia la tua immagine per concentrarsi su dettagli specifici o rimuovere elementi indesiderati, migliorandone la composizione e l'impatto visivo. Che tu stia adattando foto per i social media, creando banner per siti web o progettando materiali stampati, questo strumento ti aiuta a perfezionare le tue immagini con precisione e chiarezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |


**Example: The following example crops a DJVU image.**
Il seguente esempio ritaglia un'immagine DJVU. L'area di ritaglio viene specificata tramite Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Ritaglia l'immagine. L'area di ritaglio è la zona rettangolare centrale dell'immagine.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Salva l'immagine ritagliata in PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Il ritaglio con spostamenti ti consente di regolare con precisione la posizione e le dimensioni dell'area ritagliata all'interno di un'immagine. Questa funzionalità è inestimabile per perfezionare le composizioni, allineare gli elementi e enfatizzare i punti focali nelle tue visuali. Incorporando gli spostamenti nel processo di ritaglio, puoi ottenere una precisione pixel-perfetta e perfezionare l'inquadratura delle tue immagini con facilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | int | Lo spostamento sinistro. |
| rightShift | int | Lo spostamento destro. |
| topShift | int | Lo spostamento superiore. |
| bottomShift | int | Lo spostamento inferiore. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


La binarizzazione con una soglia predefinita semplifica le immagini complesse in rappresentazioni binarie, dove i pixel sono classificati come neri o bianchi in base alla loro intensità rispetto a un valore di soglia specificato. Questa tecnica è comunemente usata nell'elaborazione delle immagini per migliorare la chiarezza, semplificare l'analisi e preparare le immagini per ulteriori passaggi di elaborazione come il riconoscimento ottico dei caratteri (OCR). Applicando una soglia fissa, è possibile trasformare rapidamente le immagini in scala di grigi in forma binaria, rendendole più facili da interpretare ed estrarre informazioni significative.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato il valore 255, altrimenti 0. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
Il seguente esempio binarizza un'immagine DJVU con la soglia predefinita. Le immagini binarizzate contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarizza l'immagine con un valore di soglia di 127.
    // Se il valore di grigio corrispondente di un pixel è maggiore di 127, gli verrà assegnato un valore di 255, altrimenti 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


La binarizzazione usando la soglia di Otsu è una tecnica che calcola automaticamente un valore di soglia ottimale basato sull'istogramma dell'immagine. Separa l'immagine in primo piano e sfondo minimizzando la varianza intra-classe. Il metodo di Otsu è ampiamente usato per segmentare le immagini in forma binaria, soprattutto quando la distribuzione delle intensità dei pixel è bimodale o multimodale. Questo approccio è utile per compiti come il rilevamento di oggetti, la segmentazione delle immagini e l'estrazione di caratteristiche, dove una delimitazione accurata tra primo piano e sfondo è cruciale.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
Il seguente esempio binarizza un'immagine DJVU con la soglia di Otsu. Le immagini binarizzate contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarizza l'immagine con la sogliatura di Otsu.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


La binarizzazione usando l'algoritmo di soglia adattiva di Bradley con soglia di immagine integrale è un metodo che calcola una soglia locale per ogni pixel basata su un vicinato locale. Si adatta alle variazioni di illuminazione nell'immagine, rendendolo adatto a immagini con condizioni di luce non uniformi. Calcolando la soglia mediante immagini integrali, gestisce efficientemente grandi vicinati, rendendolo applicabile a applicazioni in tempo reale. Questa tecnica è comunemente usata nell'elaborazione di documenti, OCR (Riconoscimento Ottico dei Caratteri) e compiti di segmentazione delle immagini dove una binarizzazione accurata è essenziale per l'analisi successiva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel. |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
Il seguente esempio binarizza un'immagine DJVU con l'algoritmo di soglia adattiva di Bradley con la dimensione della finestra specificata. Le immagini binarizzate contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarizza l'immagine con una differenza di luminosità di 5. La luminosità è la differenza tra un pixel e la media di una finestra 10 x 10 di pixel centrata su quel pixel.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


La trasformazione in scala di grigi converte un'immagine in una rappresentazione in bianco e nero, dove l'intensità di ogni pixel è rappresentata da un unico valore che va dal nero al bianco. Questo processo rimuove le informazioni di colore, risultando in un'immagine monocromatica. Le immagini in scala di grigi sono comunemente usate in applicazioni dove il colore è superfluo o dove è preferita la semplicità, come la scansione di documenti, la stampa e alcuni tipi di analisi delle immagini.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
Il seguente esempio trasforma un'immagine DJVU a colori nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da tonalità di grigio e contengono solo informazioni di intensità.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


La correzione gamma, specificamente per i canali rosso, verde e blu, comporta la regolazione della luminosità di ciascuna componente colore separatamente. Applicando diversi coefficienti gamma ai canali RGB, puoi perfezionare la luminosità e il contrasto complessivi di un'immagine. Questa tecnica garantisce una rappresentazione accurata dei colori e migliora la qualità visiva dell'immagine su diversi dispositivi di visualizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Imposta il coefficiente gamma per i canali rosso, verde e blu.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


La correzione gamma viene applicata a un'immagine con parametri personalizzabili per i canali rosso, verde e blu, consentendo una regolazione precisa del bilanciamento del colore e della luminosità. Questo metodo migliora la qualità dell'immagine perfezionando la rappresentazione dei colori, garantendo una resa ottimale su diversi dispositivi di visualizzazione. Regolare i valori gamma per i singoli canali migliora il bilanciamento del colore e l'appeal visivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Regola la `brightness` di un'immagine usando un parametro specificato, fornendo controllo sui livelli di luminanza per una chiarezza visiva ottimale. Questo metodo aumenta o diminuisce la luminosità complessiva dell'immagine, consentendo regolazioni precise per ottenere gli effetti di illuminazione desiderati. Modulando la luminosità, gli utenti possono ottimizzare la visibilità dell'immagine e migliorare la riproduzione dei dettagli per un'esperienza di visualizzazione migliore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Imposta il valore di luminosità. I valori accettati per la luminosità sono nell'intervallo [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Migliora il contrasto di [Image](../../com.aspose.imaging/image) per aumentare la chiarezza visiva e mettere in evidenza i dettagli con questo metodo, che regola la differenza di luminosità tra le aree chiare e scure. Affinando i livelli di contrasto, gli utenti possono ottenere immagini più vivide e incisive, migliorando la qualità complessiva dell'immagine e massimizzando la visibilità dei dettagli. Questa regolazione aiuta a far emergere le sottili sfumature di colore e texture, risultando in immagini più dinamiche e visivamente attraenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Imposta il valore di contrasto. I valori accettati per il contrasto sono nell'intervallo [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Applica filtri a un'area rettangolare specificata all'interno dell'immagine per migliorare o modificare il suo aspetto. Mirando a regioni specifiche, questo metodo consente regolazioni precise, come sfocatura, nitidezza o l'applicazione di effetti artistici, per ottenere risultati visivi desiderati. Affinare i filtri sulle aree selezionate permette agli utenti di personalizzare l'estetica dell'immagine, migliorare la chiarezza e creare effetti artistici su misura per le loro preferenze.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine alla larghezza e altezza specificate applicando le impostazioni aggiuntive necessarie. Questo metodo consente agli utenti di regolare le dimensioni dell'immagine mantenendo attributi desiderati come il rapporto d'aspetto, la qualità dell'immagine e le impostazioni di compressione. Fornendo flessibilità nelle opzioni di ridimensionamento, gli utenti possono adattare l'immagine a requisiti specifici e ottimizzarne l'aspetto per varie applicazioni e piattaforme.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Riduci di 2 volte usando il ricampionamento adattivo.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Salva in PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Memorizza i dati nella cache in modo privato per ottimizzare le prestazioni e ridurre la necessità di recuperare ripetutamente i dati da fonti esterne. Questo approccio aiuta anche a conservare le risorse, in particolare negli scenari in cui l'accesso ai dati è frequente o le risorse sono limitate.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file DJVU.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Questa chiamata memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento aggiuntivo di dati dal flusso di dati sottostante.
    image.cacheData();

    // Oppure puoi memorizzare nella cache le pagine individualmente.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

