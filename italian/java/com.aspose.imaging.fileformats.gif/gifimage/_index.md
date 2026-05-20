---
title: "GifImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per il file immagine Graphical Interchange Format GIF fornisce agli sviluppatori strumenti versatili per l'elaborazione di immagini raster compresse e GIF animate."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

L'API per il file immagine Graphical Interchange Format (GIF) fornisce agli sviluppatori strumenti versatili per l'elaborazione di immagini raster compresse e GIF animate. Offre funzionalità come la gestione dei metadati XMP, l'impostazione della tavolozza dei colori, il controllo del colore di sfondo e trasparente, le impostazioni di opacità, il ridimensionamento, il ritaglio, l'applicazione di filtri, le correzioni gamma, la regolazione del contrasto, la trasformazione in scala di grigi e la conversione in altri formati. Questa API consente una manipolazione e un miglioramento senza soluzione di continuità delle immagini GIF per una vasta gamma di applicazioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | Inizializza un nuovo oggetto [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) con i parametri specificati per il primo fotogramma e la tavolozza globale. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Creare immagini GIF diventa semplice con il costruttore [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | Inizia senza sforzo con il costruttore [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupera il formato file senza sforzo con questa proprietà. |
| [hasTrailer()](#hasTrailer--) | Gestisci la presenza di un trailer nei tuoi file GIF con questa proprietà. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Gestisci la presenza di un trailer nei tuoi file GIF con questa proprietà. |
| [isPaletteSorted()](#isPaletteSorted--) | Controlla l'ordinamento della palette nelle tue immagini GIF utilizzando questa proprietà. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Controlla l'ordinamento della palette nelle tue immagini GIF utilizzando questa proprietà. |
| [getLoopsCount()](#getLoopsCount--) | Recupera il conteggio dei loop senza sforzo con questa proprietà. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Recupera il conteggio dei loop senza sforzo con questa proprietà. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Gestisci la risoluzione dei colori della palette delle tue immagini GIF con questa proprietà. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Gestisci la risoluzione dei colori della palette delle tue immagini GIF con questa proprietà. |
| [getPageCount()](#getPageCount--) | Recupera il numero totale di pagine contenute nell'immagine con questa proprietà semplice. |
| [getPages()](#getPages--) | Accedi alle pagine all'interno dell'immagine tramite questa proprietà comoda, consentendo una navigazione fluida e la manipolazione delle singole pagine secondo necessità. |
| [getBlocks()](#getBlocks--) | Accedi ai blocchi GIF senza problemi con questa proprietà, facilitando il recupero e la manipolazione delle strutture dati sottostanti dell'immagine. |
| [isInterlaced()](#isInterlaced--) | Determina se l'immagine è interlacciata, influenzando la sua visualizzazione durante il caricamento. |
| [getOriginalOptions()](#getOriginalOptions--) | Recupera le opzioni basate sulle impostazioni originali del file, fondamentali per mantenere fedeltà e coerenza nell'elaborazione e manipolazione delle immagini. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Incorpora una nuova pagina senza problemi nell'immagine esistente, migliorandone il contenuto ed espandendone la portata. |
| [getActiveFrame()](#getActiveFrame--) | Gestisci e manipola i fotogrammi con questa proprietà, consentendo una navigazione fluida e la modifica del fotogramma attivo all'interno dell'immagine GIF. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Gestisci e manipola i fotogrammi con questa proprietà, consentendo una navigazione fluida e la modifica del fotogramma attivo all'interno dell'immagine GIF. |
| [getBackgroundColor()](#getBackgroundColor--) | Gestisci il colore di sfondo dell'immagine GIF con questa proprietà. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Gestisci il colore di sfondo dell'immagine GIF con questa proprietà. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Controlla l'indice del colore di sfondo dell'immagine GIF utilizzando questa proprietà. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Controlla l'indice del colore di sfondo dell'immagine GIF utilizzando questa proprietà. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Gestisci il rapporto d'aspetto dei pixel dell'immagine GIF con questa proprietà. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Gestisci il rapporto d'aspetto dei pixel dell'immagine GIF con questa proprietà. |
| [hasTransparentColor()](#hasTransparentColor--) | Determina se il fotogramma attivo dell'immagine GIF include un colore trasparente. |
| [getTransparentColor()](#getTransparentColor--) | Recupera il colore trasparente del fotogramma attivo nell'immagine GIF. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Determina se il fotogramma attivo dell'immagine GIF include un colore trasparente. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Questa proprietà determina se l'immagine GIF contiene un colore di sfondo. |
| [getImageOpacity()](#getImageOpacity--) | Recupera l'opacità del fotogramma attivo all'interno dell'immagine, fornendo un'indicazione del suo livello di trasparenza. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona questa istanza di [Image](../../com.aspose.imaging/image). |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona questa istanza di [Image](../../com.aspose.imaging/image). |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | Ridimensionamento dell'immagine tenendo conto di tutti i fotogrammi per ogni pagina in un GIF, prevenendo così l'apparizione di potenziali artefatti. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Esegui rotazione, capovolgimento o entrambi sul fotogramma attivo esclusivamente. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Applica il dithering all'immagine corrente. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia l'immagine utilizzando un'area rettangolare specificata. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Migliora la qualità dell'immagine applicando la correzione gamma. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Applica un filtro specifico all'area designata dell'immagine, migliorandone la qualità visiva o modificandone l'aspetto secondo le necessità. |
| [setFrameTime(int time)](#setFrameTime-int-) | Regola la durata di ogni fotogramma in millisecondi, garantendo una temporizzazione coerente lungo l'intera sequenza di immagini. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la luminosità dell'immagine in base al parametro `brightness` specificato. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Regola il contrasto dell'immagine, aumentando o riducendo la differenza di luminosità tra i pixel. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | La correzione gamma di un'immagine applica una regolazione non lineare ai valori dei pixel, aumentando o riducendo la luminosità in base ai coefficienti specificati per i canali rosso, verde e blu. |
| [grayscale()](#grayscale--) | La trasformazione di un'immagine nella sua rappresentazione in scala di grigi converte l'immagine a colori in una versione in scala di grigi rimuovendo le informazioni di colore mantenendo la luminanza. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | La binarizzazione di un'immagine con una soglia predefinita converte un'immagine in scala di grigi o a colori in un'immagine binaria, dove ogni pixel è classificato come nero o bianco in base al fatto che il suo valore di intensità superi una soglia specificata. |
| [binarizeOtsu()](#binarizeOtsu--) | La binarizzazione di un'immagine con sogliatura Otsu è un metodo utilizzato per determinare automaticamente il valore di soglia ottimale per convertire un'immagine in scala di grigi in un'immagine binaria. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | La binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con sogliatura a immagine integrale è un metodo per convertire un'immagine in scala di grigi in un'immagine binaria. |
| [orderBlocks()](#orderBlocks--) | L'ordinamento dei blocchi GIF secondo la specifica GIF garantisce una corretta disposizione dei GIF e la conformità allo standard. |
| [clearBlocks()](#clearBlocks--) | La cancellazione di tutti i blocchi GIF rimuove tutti i dati esistenti memorizzati nell'immagine. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | L'inserimento di un nuovo blocco GIF consente di aggiungere dati personalizzati in una posizione specifica all'interno dell'immagine. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | L'aggiunta di un nuovo blocco GIF permette di includere dati aggiuntivi nell'immagine. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | La rimozione di un blocco GIF elimina dati specifici dall'immagine, offrendo la possibilità di pulire o modificare la struttura dell'immagine. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Il ridimensionamento proporzionale mantiene le proporzioni dell'immagine durante la modifica delle sue dimensioni, garantendo che l'immagine non appaia allungata o distorta. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Questo metodo ruota l'immagine attorno al suo punto centrale. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// Crea un blocco GIF Frame di 100x100 px.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Riempire l'intero blocco di rosso.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Carica i fotogrammi
    RasterImage[] frames = loadFrames("Animation frames");

    // Crea un'immagine GIF usando il primo fotogramma
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Aggiungi fotogrammi all'immagine GIF usando il metodo AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Salva l'immagine GIF
        image.save("Multipage.gif");
    }

    // rilascia le risorse
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


Inizializza un nuovo oggetto [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) con i parametri specificati per il primo fotogramma e la palette globale. Inizia a gestire le immagini GIF rapidamente, garantendo una rappresentazione accurata con impostazioni personalizzabili per risultati ottimali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Il primo fotogramma con cui inizializzare l'immagine GIF. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette globale da utilizzare. Nota che se sia `firstFrame` sia `globalPalette` sono null, allora viene usata la palette globale predefinita. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


Creare immagini GIF diventa facile con il costruttore [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). Con il solo parametro firstFrame, si accede a un mondo di comunicazione visiva dinamica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Il primo fotogramma con cui inizializzare l'immagine GIF. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Inizia senza sforzo con il costruttore [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). Con questo metodo semplice, puoi immergerti nella creazione di GIF animate con facilità. Basta fornire firstFrame, globalPalette, paletteColorResolution, aspectRatio e altri parametri, e sarai pronto a dare vita ai tuoi contenuti visivi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Il primo fotogramma con cui inizializzare l'immagine GIF. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette globale da utilizzare. Nota che se sia `firstFrame` sia `globalPalette` sono null, allora viene usata la palette globale predefinita. |
| isPaletteSorted | boolean | Se impostato su `true` la palette è ordinata. Nota che il parametro viene usato quando `globalPalette` non è nullo. |
| paletteColorResolution | byte | La risoluzione di colore della palette. Nota che il parametro viene usato quando `globalPalette` non è nullo. |
| paletteBackgroundColorIndex | byte | L'indice del colore di sfondo della palette. |
| aspectRatio | byte | Il rapporto d'aspetto. |
| hasTrailer | boolean | Se impostato su `true` l'immagine GIF ha un trailer, altrimenti non viene scritto alcun trailer alla fine dello stream. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera il formato del file senza sforzo con questa proprietà. È la tua fonte di riferimento per identificare il formato dei tuoi file. Integrata perfettamente nel tuo flusso di lavoro, fornisce informazioni vitali senza alcun problema.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Gestisci la presenza di un trailer nei tuoi file GIF con questa proprietà. Che tu debba verificare se un trailer esiste o impostarne la presenza, questa proprietà semplifica il processo. Mantieni i tuoi file GIF strutturati e conformi con questa funzionalità intuitiva.

**Returns:**
boolean - `true` se il GIF ha trailer; altrimenti, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Gestisci la presenza di un trailer nei tuoi file GIF con questa proprietà. Che tu debba verificare se un trailer esiste o impostarne la presenza, questa proprietà semplifica il processo. Mantieni i tuoi file GIF strutturati e conformi con questa funzionalità intuitiva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se il GIF ha trailer; altrimenti, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Controlla l'ordinamento della palette nelle tue immagini GIF usando questa proprietà. Che tu debba verificare se la palette è ordinata o impostare il comportamento di ordinamento, questa proprietà offre un modo semplice per gestire l'organizzazione della palette nei tuoi file GIF.

**Returns:**
boolean - `true` se la palette è ordinata; altrimenti, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Controlla l'ordinamento della palette nelle tue immagini GIF usando questa proprietà. Che tu debba verificare se la palette è ordinata o impostare il comportamento di ordinamento, questa proprietà offre un modo semplice per gestire l'organizzazione della palette nei tuoi file GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se la palette è ordinata; altrimenti, `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Recupera il conteggio dei loop senza sforzo con questa proprietà. Se la tua immagine GIF include informazioni sul loop, questa proprietà ti fornisce un accesso rapido al conteggio dei loop, consentendoti di gestire senza problemi il comportamento di ripetizione nei tuoi file GIF.

**Returns:**
int - Il conteggio dei loop o 1 (valore predefinito)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Recupera il conteggio dei loop senza sforzo con questa proprietà. Se la tua immagine GIF include informazioni sul loop, questa proprietà ti fornisce un accesso rapido al conteggio dei loop, consentendoti di gestire senza problemi il comportamento di ripetizione nei tuoi file GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il conteggio dei loop o 1 (valore predefinito) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Gestisci la risoluzione di colore della palette delle tue immagini GIF con questa proprietà. Regola il numero di bit usati per rappresentare i colori nella palette, fornendo un controllo preciso sulla profondità di colore e sulla qualità dell'immagine.

**Returns:**
byte - I bit della risoluzione di colore della palette.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Gestisci la risoluzione di colore della palette delle tue immagini GIF con questa proprietà. Regola il numero di bit usati per rappresentare i colori nella palette, fornendo un controllo preciso sulla profondità di colore e sulla qualità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | I bit della risoluzione di colore della palette. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il numero totale di pagine contenute nell'immagine con questa proprietà semplice. Ideale per valutare rapidamente l'estensione del contenuto dell'immagine.

**Returns:**
int - il conteggio delle pagine.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accedi alle pagine all'interno dell'immagine tramite questa proprietà comoda, consentendo una navigazione fluida e la manipolazione delle singole pagine secondo necessità.

**Returns:**
com.aspose.imaging.Image[] - le pagine.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Accedi ai blocchi GIF senza problemi con questa proprietà, facilitando il recupero e la manipolazione delle strutture dati sottostanti dell'immagine.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - i blocchi GIF.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Determina se l'immagine è interlacciata, influenzando la sua visualizzazione durante il caricamento. Questa proprietà offre una visione del comportamento di rendering dell'immagine, essenziale per ottimizzare le strategie di caricamento e migliorare l'esperienza di visualizzazione complessiva.

**Returns:**
boolean - `true` se questa istanza di immagine è interlacciata; altrimenti, `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupera le opzioni basate sulle impostazioni originali del file, fondamentali per mantenere fedeltà e coerenza nell'elaborazione e manipolazione delle immagini. Questo metodo consente un'integrazione fluida dei parametri specifici del file nelle operazioni successive, garantendo una resa accurata e il rispetto delle caratteristiche intrinseche dell'immagine. Può essere utile per mantenere inalterata la profondità di colore e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco‑nero a 1 bit per pixel e poi la salviamo usando il metodo [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), verrà prodotta un'immagine PNG in output a 8 bit per pixel. Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorpora una nuova pagina senza soluzione di continuità nell'immagine esistente, migliorandone il contenuto e ampliandone la portata. Questo metodo arricchisce le collezioni di immagini con contenuti aggiuntivi, favorendo creatività e flessibilità nella gestione e composizione delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La pagina da aggiungere. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Carica i fotogrammi
    RasterImage[] frames = loadFrames("Animation frames");

    // Crea un'immagine GIF usando il primo fotogramma
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Aggiungi fotogrammi all'immagine GIF usando il metodo AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Salva l'immagine GIF
        image.save("Multipage.gif");
    }

    // rilascia le risorse
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Gestisci e manipola i fotogrammi con questa proprietà, consentendo una navigazione fluida e la modifica del fotogramma attivo all'interno dell'immagine GIF.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// L'output appare così:
// Dimensione del fotogramma attivo: { Width = 100, Height = 100}
// Cancella tutti i blocchi
// Il fotogramma attivo non è impostato
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Gestisci e manipola i fotogrammi con questa proprietà, consentendo una navigazione fluida e la modifica del fotogramma attivo all'interno dell'immagine GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | il fotogramma attivo. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gestisci il colore di sfondo dell'immagine GIF con questa proprietà. Puoi impostare o recuperare il colore di sfondo per garantire coerenza e migliorare l'appeal visivo.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Gestisci il colore di sfondo dell'immagine GIF con questa proprietà. Puoi impostare o recuperare il colore di sfondo per garantire coerenza e migliorare l'appeal visivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | il colore di sfondo. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Controlla l'indice del colore di sfondo dell'immagine GIF usando questa proprietà. Imposta o recupera l'indice per mantenere la coerenza o ottenere gli effetti visivi desiderati.

**Returns:**
byte - l'indice del colore di sfondo.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Controlla l'indice del colore di sfondo dell'immagine GIF usando questa proprietà. Imposta o recupera l'indice per mantenere la coerenza o ottenere gli effetti visivi desiderati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | l'indice del colore di sfondo. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Gestisci il rapporto d'aspetto dei pixel dell'immagine GIF con questa proprietà. Imposta o recupera il rapporto d'aspetto per garantire una resa accurata e mantenere la fedeltà visiva.

**Returns:**
byte - il rapporto d'aspetto dei pixel.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Gestisci il rapporto d'aspetto dei pixel dell'immagine GIF con questa proprietà. Imposta o recupera il rapporto d'aspetto per garantire una resa accurata e mantenere la fedeltà visiva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | il rapporto d'aspetto dei pixel. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Determina se il fotogramma attivo dell'immagine GIF include un colore trasparente. Questa proprietà offre un modo comodo per verificare la trasparenza all'interno dell'immagine.

**Returns:**
boolean - un valore che indica se il fotogramma attivo ha un colore trasparente.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Recupera il colore trasparente del fotogramma attivo nell'immagine GIF. Questa proprietà consente di accedere al colore specifico designato come trasparente nel fotogramma attualmente attivo.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Determina se il fotogramma attivo dell'immagine GIF include un colore trasparente. Questa proprietà offre un modo comodo per verificare la trasparenza all'interno dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se il fotogramma attivo ha un colore trasparente. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Questa proprietà determina se l'immagine GIF contiene un colore di sfondo. Se vero, indica che l'immagine include un colore di sfondo.

**Returns:**
boolean - un valore che indica se l'immagine ha un colore di sfondo.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Recupera l'opacità del fotogramma attivo all'interno dell'immagine, fornendo informazioni sul suo livello di trasparenza. Questa proprietà è particolarmente utile per comprendere il grado di trasparenza o opacità del fotogramma attivo nell'immagine.

Il valore di opacità compreso tra 0.0 (completamente trasparente) e 1.0 (completamente opaco).

**Returns:**
float - opacità di questa immagine (fotogramma attivo).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ridimensiona questa istanza di [Image](../../com.aspose.imaging/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Riduci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona questa istanza di [Image](../../com.aspose.imaging/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

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

// Il metodo Euclideo
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Riduci di 2 volte usando il ricampionamento adattivo.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Salva in PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


Ridimensionamento dell'immagine tenendo conto di tutti i fotogrammi per ogni pagina in una GIF, evitando così la comparsa di potenziali artefatti. Questo metodo è essenziale per mantenere l'integrità e la qualità dell'immagine, soprattutto quando si lavora con GIF animate o sequenze di fotogrammi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Esegui rotazione, capovolgimento o entrambi sul fotogramma attivo in esclusiva. Questa operazione applica trasformazioni solo al fotogramma attualmente attivo dell'immagine, preservando l'integrità degli altri fotogrammi nella sequenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// La classe helper utilizzata nell'esempio principale di seguito.
class Utils {
    // Il metodo helper per ottenere una rappresentazione stringa del formato file.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// Ecco l'esempio principale
Utils utils = new Utils();

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
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Applica il dithering all'immagine corrente. Questo processo migliora la qualità dell'immagine riducendo le bande di colore e migliorando le transizioni cromatiche, risultando in un aspetto più uniforme.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Esegui il dithering a soglia usando una palette di colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Esegui il dithering Floyd usando una palette di colori a 1 bit che contiene solo 2 colori - nero e bianco.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia l'immagine usando un'area rettangolare specificata. Questa operazione rimuove la parte esterna dell'immagine, lasciando solo la regione selezionata definita dal rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |


**Example: The following example crops a GIF image.**
Il seguente esempio ritaglia un'immagine GIF. L'area di ritaglio viene specificata tramite Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Ritaglia l'immagine. L'area di ritaglio è la zona rettangolare centrale dell'immagine.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Salva l'immagine ritagliata in PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Migliora la qualità dell'immagine applicando la correzione gamma. Questo metodo regola il gamma colore dell'immagine per ottenere una chiarezza visiva ottimale. Modifica il valore gamma di ogni pixel, risultando in una resa cromatica migliorata e un aspetto complessivo dell'immagine più nitido.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Imposta il coefficiente gamma per i canali rosso, verde e blu.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Applica un filtro specifico all'area designata dell'immagine, migliorandone la qualità visiva o alterandone l'aspetto secondo le necessità. Questo metodo elabora selettivamente i pixel all'interno del rettangolo definito, consentendo regolazioni mirate mantenendo l'integrità dei dati dell'immagine circostante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Regola la durata di ogni fotogramma in millisecondi, garantendo una temporizzazione coerente lungo tutta la sequenza di immagini. Questo metodo imposta uniformemente il tempo di visualizzazione per ogni fotogramma, consentendo un controllo preciso sulla velocità dell'animazione. Modificando questo valore si resetterà il ritardo per tutti i fotogrammi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tempo | int | Il tempo di durata del fotogramma in millisecondi. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Regola la luminosità dell'immagine in base al parametro `brightness` specificato. Questo metodo modifica uniformemente la luminosità dell'intera immagine, aumentando o riducendo la luminanza complessiva per ottenere l'effetto desiderato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Imposta il valore di luminosità. I valori accettati per la luminosità sono nell'intervallo [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Regola il contrasto dell'immagine, aumentando o riducendo la differenza di luminosità tra i pixel. Questo metodo modifica l'intera gamma tonale dell'immagine, rendendo le aree più scure più scure e le aree più luminose più luminose per migliorare la chiarezza visiva e i dettagli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Imposta il valore di contrasto. I valori accettati per il contrasto sono nell'intervallo [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


La correzione gamma di un'immagine applica una regolazione non lineare ai valori dei pixel, aumentando o riducendo la luminosità in base ai coefficienti specificati per i canali rosso, verde e blu. Questo metodo aiuta a perfezionare il bilanciamento dei colori e la luminanza dell'immagine, migliorandone l'aspetto complessivo e la qualità visiva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


La trasformazione di un'immagine nella sua rappresentazione in scala di grigi converte l'immagine a colori in una versione in scala di grigi rimuovendo le informazioni di colore mantenendo la luminanza. Questo processo semplifica l'immagine in tonalità di grigio, rendendola adatta a varie applicazioni come la stampa, l'elaborazione di documenti e l'analisi in scala di grigi.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
Il seguente esempio trasforma un'immagine GIF a colori nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da tonalità di grigio e contengono solo informazioni di intensità.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


La binarizzazione di un'immagine con una soglia predefinita converte un'immagine in scala di grigi o a colori in un'immagine binaria, dove ogni pixel è classificato come nero o bianco in base al fatto che il suo valore di intensità superi una soglia specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato il valore 255, altrimenti 0. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
Il seguente esempio binarizza un'immagine GIF con la soglia predefinita. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

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


La binarizzazione di un'immagine con sogliatura Otsu è un metodo utilizzato per determinare automaticamente il valore di soglia ottimale per convertire un'immagine in scala di grigi in un'immagine binaria. L'algoritmo di sogliatura Otsu calcola la soglia che minimizza la varianza intra-classe delle intensità dei pixel nelle due classi risultanti (sfondo e primo piano). Questa tecnica è particolarmente utile quando il valore di soglia ottimale è sconosciuto e deve essere determinato in modo adattivo in base all'istogramma dell'immagine.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
Il seguente esempio binarizza un'immagine GIF con sogliatura Otsu. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarizza l'immagine con la sogliatura di Otsu.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


La binarizzazione di un'immagine utilizzando l'algoritmo di sogliatura adattiva di Bradley con sogliatura a immagine integrale è un metodo per convertire un'immagine in scala di grigi in un'immagine binaria. Questo algoritmo calcola una soglia locale per ogni pixel basata sull'intensità media dei pixel circostanti all'interno di una finestra specificata. Regolando adattivamente la soglia in base alle intensità locali dei pixel, il metodo di Bradley è efficace nel gestire le variazioni di illuminazione e contrasto nell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


L'ordinamento dei blocchi GIF secondo la specifica GIF garantisce una corretta disposizione dei GIF e la conformità allo standard. Questo processo prevede la disposizione dei blocchi nella sequenza corretta come definita dalla specifica. Inoltre, può comportare la rimozione di alcune istanze di [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) non necessarie per il layout finale. Attenendosi alla specifica GIF, l'immagine risultante sarà strutturata correttamente e compatibile con le applicazioni di visualizzazione GIF.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


La cancellazione di tutti i blocchi GIF rimuove tutti i dati esistenti memorizzati nell'immagine. Questa operazione resetta efficacemente l'immagine a uno stato vuoto, rimuovendo tutti i blocchi precedentemente aggiunti. Usa questo metodo quando è necessario ricominciare da zero con una base pulita per creare o modificare un'immagine GIF.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// L'output appare così:
// Dimensione del fotogramma attivo: { Width = 100, Height = 100}
// Cancella tutti i blocchi
// Il fotogramma attivo non è impostato
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


L'inserimento di un nuovo blocco GIF consente di aggiungere dati personalizzati in una posizione specifica all'interno dell'immagine. Questo metodo permette di posizionare blocchi personalizzati nella posizione desiderata nell'immagine GIF, offrendo flessibilità nell'organizzazione e nella strutturazione dei dati dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'elemento indicizzato da zero, in cui il blocco sarà inserito. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Il blocco GIF da aggiungere. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


L'aggiunta di un nuovo blocco GIF consente di includere dati aggiuntivi all'interno dell'immagine. Questo metodo permette di aggiungere blocchi personalizzati all'immagine GIF, che possono contenere vari tipi di informazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Il blocco GIF da aggiungere. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine GIF 100 x 100 px.
// Il primo blocco è completamente nero per impostazione predefinita.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // Il primo cerchio è rosso
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Il secondo cerchio è nero
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Aumenta gradualmente l'angolo della forma ad arco rossa.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


La rimozione di un blocco GIF elimina dati specifici dall'immagine, offrendo la possibilità di pulire o modificare la struttura dell'immagine. Questo metodo consente di rimuovere blocchi indesiderati o non necessari, ottimizzando l'immagine GIF per una memorizzazione efficiente. Utilizza questa funzionalità per eliminare informazioni obsolete dall'immagine preservandone l'integrità e la qualità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Il blocco da rimuovere. |

--------------------

Nota: non dimenticare di Dispose il blocco se non lo aggiungerai a un'altra GifImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Il ridimensionamento proporzionale mantiene il rapporto d'aspetto dell'immagine mentre ne regola le dimensioni, garantendo che l'immagine non appaia allungata o distorta. Questo metodo ridimensiona l'immagine proporzionalmente, scalando sia la larghezza sia l'altezza con lo stesso fattore. Il ridimensionamento proporzionale ridimensionerà ogni fotogramma secondo il rapporto di `newWidth`/width e `newHeight`/height.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Questo metodo ruota l'immagine attorno al suo punto centrale. Specificando l'angolo di rotazione, è possibile ruotare l'immagine in senso orario o antiorario per ottenere l'orientamento desiderato. Questa rotazione aiuta a regolare la presentazione o l'allineamento dell'immagine senza distorcerne il contenuto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | Se impostato su `true` la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

