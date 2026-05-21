---
title: "EpsImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per il supporto del formato di file immagine Encapsulated PostScript EPS offre robuste capacità per manipolare composizioni composte da testo, grafica e immagini."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

L'API per il supporto del formato di file immagine Encapsulated PostScript (EPS) offre robuste capacità per manipolare composizioni composte da testo, grafica e immagini. Con funzionalità come la gestione delle immagini di anteprima bitmap, il ribaltamento dell'orientamento, il recupero del riquadro di delimitazione per i limiti dell'illustrazione, il ridimensionamento, la rotazione delle immagini e l'aggiunta di immagini di anteprima. Questa API garantisce un'elaborazione fluida e l'integrazione dei file EPS in varie applicazioni con precisione e versatilità.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Accedi al numero di immagini di anteprima disponibili con facilità. |
| [getPreviewImages()](#getPreviewImages--) | Recupera le immagini di anteprima associate al tuo file. |
| [getFileFormat()](#getFileFormat--) | Accedi al formato del file della tua immagine con questa proprietà. |
| [getEpsType()](#getEpsType--) | Accedi e interpreta il valore del sottotipo della tua immagine EPS, semplificando il tuo flusso di lavoro e migliorando la compatibilità tra piattaforme. |
| [hasRasterPreview()](#hasRasterPreview--) | Scopri la presenza di un'anteprima raster senza sforzo con questa proprietà. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Accedi alla precisa profondità di bit dell'immagine senza sforzo con questa proprietà. |
| [getWidthF()](#getWidthF--) | Recupera la larghezza dell'immagine con questa comoda proprietà. |
| [getHeightF()](#getHeightF--) | Accedi all'altezza dell'immagine usando questa proprietà. |
| [isCached()](#isCached--) | Questa proprietà fornisce un modo comodo per verificare se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di ulteriori letture dei dati. |
| [getPsStream()](#getPsStream--) | Ottiene lo stream contenente il PostScript da eseguire. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Questa proprietà recupera la versione del PostScript associata all'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getTitle()](#getTitle--) | Questa proprietà recupera il titolo estratto dai commenti EPS Document Structuring Conventions (DSC) incorporati nel file EPS. |
| [getCreator()](#getCreator--) | Questa proprietà offre l'accesso alle informazioni sul creatore provenienti dai commenti EPS Document Structuring Conventions (DSC) presenti nel file EPS. |
| [getCreationDate()](#getCreationDate--) | Recuperando la data di creazione dai commenti EPS Document Structuring Conventions (DSC), questa proprietà fornisce metadati essenziali che indicano l'inizio del file EPS. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Recuperando la data di creazione dai commenti EPS Document Structuring Conventions (DSC), questa proprietà fornisce metadati essenziali che indicano l'inizio del file EPS. |
| [getBoundingBox()](#getBoundingBox--) | Accedendo al riquadro di delimitazione originale in punti indipendenti dal dispositivo, questa proprietà fornisce informazioni geometriche cruciali sulle dimensioni del [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Questa proprietà restituisce il riquadro di delimitazione originale dell'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) in pixel, fornendo dati geometrici essenziali per un rendering e una manipolazione accurati. |
| [cacheData()](#cacheData--) | Questa proprietà restituisce il riquadro di delimitazione originale dell'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) in pixel, fornendo dati geometrici essenziali per un rendering e una manipolazione accurati. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Accede alle immagini di anteprima collegate all'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), consentendo un recupero fluido per l'ispezione o l'utilizzo nelle applicazioni. |
| [getPreviewImage()](#getPreviewImage--) | Recupera l'immagine di anteprima esistente nel `format` specificato o restituisce `` se non ne viene trovata alcuna. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Recupera l'immagine di anteprima esistente nel `format` specificato o restituisce `` se non ne viene trovata alcuna. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personalizza le palette di immagini per ottenere combinazioni di colori uniche e migliorare l'appeal visivo. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// Carica immagine EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Ridimensiona l'immagine usando il metodo di interpolazione cubica Mitchell
    image.resize(400, 400, ResizeType.Mitchell);

    // Esporta l'immagine in formato PNG
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// Carica immagine EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Imposta la modalità di interpolazione
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Imposta il tipo di filtro
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Imposta il metodo di confronto dei colori
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Imposta il metodo di quantizzazione dei colori
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Ridimensiona l'immagine usando impostazioni avanzate di ridimensionamento
    image.resize(400, 400, resizeSettings);

    // Esporta l'immagine in formato PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Accedi al numero di immagini di anteprima disponibili con facilità. Questa proprietà ti consente di recuperare senza sforzo il conteggio delle immagini di anteprima associate al tuo file, permettendo una gestione efficiente e una navigazione delle anteprime delle tue immagini. Ideale per ottimizzare il tuo flusso di lavoro e organizzare efficacemente le risorse delle tue immagini.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Recupera le immagini di anteprima associate al tuo file. Questa proprietà fornisce un accesso fluido alla collezione di immagini di anteprima, consentendoti di sfogliare e gestirle in modo efficiente secondo le necessità. Ideale per visualizzare rapidamente e selezionare l'immagine giusta per il tuo progetto.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accedi al formato del file della tua immagine con questa proprietà. Recupera informazioni essenziali sul formato del tuo file immagine, facilitando la compatibilità e l'elaborazione efficiente. Ideale per identificare il formato dei tuoi file immagine per un'integrazione fluida nei tuoi progetti.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Accedi e interpreta il valore del sottotipo della tua immagine EPS, semplificando il tuo flusso di lavoro e migliorando la compatibilità tra le piattaforme. Ideale per ottimizzare il recupero del sottotipo EPS nei tuoi progetti con precisione ed efficienza.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Scopri facilmente la presenza di un'anteprima raster con questa proprietà. Accedi al valore booleano che indica se l'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) include un'anteprima raster, potenziando le tue attività di elaborazione delle immagini con chiarezza ed efficienza. Ideale per semplificare le decisioni del flusso di lavoro basate sulla presenza o assenza di anteprime raster nelle immagini EPS.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Accedi facilmente alla precisione della profondità di bit dell'immagine con questa proprietà. Recupera il conteggio dei bit per pixel, fornendo informazioni cruciali sulla profondità di colore dell'immagine e aiutando a ottimizzare le attività di elaborazione. Ideale per applicazioni che richiedono un controllo dettagliato sulla manipolazione e l'analisi delle immagini.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Recupera la larghezza dell'immagine con questa pratica proprietà. Ottieni la larghezza dell'immagine senza sforzo, facilitando calcoli di layout precisi, operazioni di ridimensionamento e compiti legati alle dimensioni all'interno della tua applicazione. Ideale per garantire una resa e una visualizzazione accurate delle immagini su varie piattaforme e dispositivi.

**Returns:**
float - La larghezza dell'immagine in pixel.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Accedi all'altezza dell'immagine usando questa proprietà. Ottieni l'altezza dell'immagine con facilità, consentendo regolazioni di layout fluide, calcoli del rapporto d'aspetto e una resa precisa su diverse risoluzioni dello schermo e ambienti di visualizzazione.

**Returns:**
float - L'altezza dell'immagine in pixel.
### isCached() {#isCached--}
```
public boolean isCached()
```


Questa proprietà offre un modo pratico per verificare se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di ulteriori letture di dati. Fornisce un metodo rapido ed efficiente per determinare se le informazioni richieste sono disponibili immediatamente, ottimizzando le prestazioni e riducendo il sovraccarico di risorse nelle operazioni ad alta intensità di dati.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Ottiene lo stream contenente il PostScript da eseguire.

**Returns:**
java.io.InputStream - lo stream contenente il PostScript da eseguire.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Questa proprietà recupera la versione PostScript associata all'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Fornisce informazioni sulla specifica versione del linguaggio PostScript utilizzata nel file EPS, aiutando nella valutazione della compatibilità e facilitando l'integrazione fluida con ambienti compatibili con PostScript.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


Questa proprietà recupera il titolo estratto dai commenti delle EPS Document Structuring Conventions (DSC) incorporati nel file EPS. Fornisce metadati preziosi sul contenuto del file EPS, facilitando l'organizzazione dei documenti e l'identificazione all'interno di applicazioni software compatibili.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Questa proprietà offre l'accesso alle informazioni sul creatore provenienti dai commenti delle EPS Document Structuring Conventions (DSC) presenti nel file EPS. Comprendere i dettagli del creatore fornisce indicazioni sul software o strumento utilizzato per generare il file EPS, facilitando la valutazione della compatibilità su varie piattaforme e applicazioni.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Recuperando la data di creazione dai commenti delle EPS Document Structuring Conventions (DSC), questa proprietà fornisce metadati essenziali che indicano l'origine del file EPS. Accedendo a queste informazioni, gli utenti ottengono indicazioni sull'origine e sulla cronologia del file, migliorando la gestione e l'organizzazione dei file.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Recuperando la data di creazione dai commenti delle EPS Document Structuring Conventions (DSC), questa proprietà fornisce metadati essenziali che indicano l'origine del file EPS. Accedendo a queste informazioni, gli utenti ottengono indicazioni sull'origine e sulla cronologia del file, migliorando la gestione e l'organizzazione dei file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Accedendo al riquadro di delimitazione originale in punti indipendenti dal dispositivo, questa proprietà fornisce informazioni geometriche cruciali sulle dimensioni del [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Recuperando questi dati, gli utenti possono valutare con precisione le dimensioni e il rapporto d'aspetto dell'immagine, facilitando layout e posizionamento precisi in varie applicazioni.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Questa proprietà restituisce il riquadro di delimitazione originale dell'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) in pixel, fornendo dati geometrici essenziali per una resa e una manipolazione accurate. Con queste informazioni, gli utenti possono garantire un posizionamento e una dimensione precisi delle immagini EPS nei loro progetti, migliorando la presentazione visiva complessiva e la qualità.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


Questa proprietà restituisce il riquadro di delimitazione originale dell'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) in pixel, fornendo dati geometrici essenziali per una resa e una manipolazione accurate. Con queste informazioni, gli utenti possono garantire un posizionamento e una dimensione precisi delle immagini EPS nei loro progetti, migliorando la presentazione visiva complessiva e la qualità.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Accede alle immagini di anteprima collegate all'istanza [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), consentendo un recupero fluido per l'ispezione o l'utilizzo nelle applicazioni. Questo metodo fornisce un accesso pratico alle immagini di anteprima, migliorando l'interazione dell'utente con i dati dell'immagine.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - Le immagini di anteprima.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Recupera l'immagine di anteprima esistente nel `format` specificato o restituisce `` se non ne viene trovata alcuna. Questo metodo offre flessibilità nell'accesso alle immagini di anteprima adattate a formati specifici, ottimizzando la compatibilità e la gestione delle risorse nelle applicazioni.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Recupera l'immagine di anteprima esistente nel `format` specificato o restituisce `` se non ne viene trovata alcuna. Questo metodo offre flessibilità nell'accesso alle immagini di anteprima adattate a formati specifici, ottimizzando la compatibilità e la gestione delle risorse nelle applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | long | Il formato dell'immagine di anteprima EPS. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Personalizza le palette di immagini per ottenere combinazioni di colori uniche e migliorare l'appeal visivo. Adatta i colori per effetti specifici e ottimizza la qualità dell'immagine su diverse piattaforme e dispositivi con facilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

