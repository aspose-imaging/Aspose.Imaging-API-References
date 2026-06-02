---
title: "TgaImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola i file immagine raster TGA con la nostra API, adattata al formato TARGA Truevision Advanced Raster Adapter, consentendo un caricamento e una personalizzazione senza interruzioni."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

Manipola i file immagine raster TGA con la nostra API, adattata al formato TARGA (Truevision Advanced Raster Adapter), consentendo un caricamento e una personalizzazione senza interruzioni. Aggiorna facilmente le proprietà pubbliche come autore, data/ora, ID immagine e versione del software, utilizzando varie impostazioni di bit per pixel, canale alfa e trasparenza del colore. Inoltre, puoi esportare le immagini TGA in altri formati raster popolari, garantendo la compatibilità per i tuoi progetti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Inizializza un nuovo oggetto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) utilizzando il percorso file fornito per caricare il contenuto dell'immagine. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Crea una nuova istanza della classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) fornendo un oggetto immagine raster. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Inizializza una nuova istanza della classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) utilizzando uno stream per caricare l'immagine. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera il valore dei bit per pixel, fornendo informazioni essenziali sulla profondità di colore dell'immagine. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Ottieni il valore dei byte per pixel, che indica la quantità di memoria occupata da ciascun pixel nell'immagine. |
| [hasAlpha()](#hasAlpha--) | Recupera un valore booleano che indica se il [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) include un canale alfa, facilitando gli effetti di trasparenza. |
| [isGrayScale()](#isGrayScale--) | Ottieni un valore booleano che indica se il [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) rappresenta un'immagine in scala di grigi. |
| [getWidth()](#getWidth--) | Recupera la larghezza dell'immagine rappresentata da questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getHeight()](#getHeight--) | Ottieni l'altezza dell'immagine incapsulata da questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getFileFormat()](#getFileFormat--) | Ottieni informazioni fondamentali sul formato file dell'immagine rappresentata da questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [hasColorMap()](#hasColorMap--) | Recupera se questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) contiene una mappa dei colori. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Restituisce la parte numeratore del valore gamma, che è essenziale per una rappresentazione accurata dei colori nelle immagini. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Recupera la parte denominatore del valore gamma, un fattore integrante nella determinazione della rappresentazione dei colori nelle immagini. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Recupera il componente numeratore del Rapporto di Aspetto del Pixel, che influenza l'aspetto visivo dei pixel all'interno dell'immagine. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Recupera la parte denominatore del Rapporto di Aspetto del Pixel, un fattore cruciale nella determinazione dell'aspetto visivo dei pixel all'interno dell'immagine. |
| [getXOrigin()](#getXOrigin--) | Restituisce la coordinata orizzontale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA). |
| [setXOrigin(int value)](#setXOrigin-int-) | Imposta la coordinata orizzontale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA). |
| [getYOrigin()](#getYOrigin--) | Restituisce la coordinata verticale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA). |
| [setYOrigin(int value)](#setYOrigin-int-) | Imposta la coordinata verticale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA). |
| [getImageId()](#getImageId--) | Restituisce l'identificatore univoco associato all'immagine. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Imposta l'identificatore univoco associato all'immagine. |
| [getAuthorComments()](#getAuthorComments--) | Recupera o imposta i commenti forniti dall'autore dell'immagine. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Recupera o imposta i commenti forniti dall'autore dell'immagine. |
| [getAuthorName()](#getAuthorName--) | Recupera o imposta il nome dell'autore associato all'immagine. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Recupera o imposta il nome dell'autore associato all'immagine. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Ottiene il timestamp data/ora. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Imposta il timestamp data/ora. |
| [getJobNameOrId()](#getJobNameOrId--) | Recupera o imposta il nome o l'ID del lavoro associato all'immagine. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Recupera o imposta il nome o l'ID del lavoro associato all'immagine. |
| [getJobTime()](#getJobTime--) | Recupera o imposta il timestamp che indica l'ora del lavoro associato all'immagine. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Recupera o imposta il timestamp che indica l'ora del lavoro associato all'immagine. |
| [getTransparentColor()](#getTransparentColor--) | Recupera o imposta il colore chiave associato all'immagine. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Recupera o imposta il colore chiave associato all'immagine. |
| [hasTransparentColor()](#hasTransparentColor--) | Recupera o imposta un valore booleano che indica se l'immagine contiene un colore trasparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Recupera o imposta un valore booleano che indica se l'immagine contiene un colore trasparente. |
| [getBackgroundColor()](#getBackgroundColor--) | Recupera o imposta il colore di sfondo dell'immagine. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Recupera o imposta il colore di sfondo dell'immagine. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Recupera o imposta un valore che indica se l'immagine contiene un colore di sfondo. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Recupera o imposta un valore che indica se l'immagine contiene un colore di sfondo. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Recupera o imposta la versione del software associata all'immagine. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Recupera o imposta la versione del software associata all'immagine. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Recupera o imposta la componente letterale della versione del software associata all'immagine. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Recupera o imposta la componente letterale della versione del software associata all'immagine. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Recupera o imposta la componente numerica della versione del software associata all'immagine. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Recupera o imposta la componente numerica della versione del software associata all'immagine. |
| [getSoftwareId()](#getSoftwareId--) | Gestisce l'identificazione del software (ID) associata all'immagine, consentendo fino a 40 caratteri ASCII. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Gestisce l'identificazione del software (ID) associata all'immagine, consentendo fino a 40 caratteri ASCII. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Esegue un confronto di uguaglianza tra due immagini TGA, considerando sia la prima che la seconda immagine coinvolta nel processo di confronto. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Esegue un confronto di disuguaglianza tra due immagini TGA, valutando sia la prima che la seconda immagine coinvolta nel confronto. |
| [deepClone()](#deepClone--) | Produce un duplicato dell'istanza corrente, generando un nuovo oggetto che clona tutti gli attributi e le proprietà dell'originale. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Replica le proprietà di un altro oggetto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), creando una nuova istanza con attributi identici. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | In un confronto di uguaglianza, il metodo valuta se l'istanza corrente di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) è uguale alla seconda immagine fornita come parametro. |
| [equals(Object other)](#equals-java.lang.Object-) | Il metodo esegue un confronto di uguaglianza tra l'istanza corrente di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) e un altro oggetto fornito come parametro. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Il metodo "rotateFlip" consente operazioni di rotazione e capovolgimento sull'immagine. |
| [hashCode()](#hashCode--) | Recupera il codice hash dell'istanza corrente. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia l'immagine a una regione specificata. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Ritaglia l'immagine specificando gli spostamenti per i bordi sinistro, destro, superiore e inferiore. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona l'immagine applicando impostazioni specifiche per mantenere le dimensioni desiderate e il rapporto d'aspetto. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Regola le dimensioni dell'immagine utilizzando un tipo di ridimensionamento specificato, che determina come viene eseguita l'operazione di ridimensionamento. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Ruota l'immagine attorno al suo centro di un angolo specificato mantenendo la proporzionalità del ridimensionamento e preservando il colore di sfondo. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Inizializza un nuovo oggetto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) utilizzando il percorso file fornito per caricare il contenuto dell'immagine. Questo costruttore inizializza in modo efficiente l'istanza dell'immagine, consentendo un accesso senza interruzioni ai file immagine TGA, semplificando l'integrazione nel flusso di lavoro della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso per caricare un'immagine. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Crea una nuova istanza della classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) fornendo un oggetto immagine raster. Questo costruttore facilita l'integrazione diretta delle immagini raster esistenti nel formato immagine TGA, semplificando il processo di conversione per una maggiore compatibilità all'interno dei tuoi sistemi software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Inizializza una nuova istanza della classe [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) utilizzando uno stream per caricare l'immagine. Questo costruttore consente un'integrazione senza interruzioni dei dati immagine provenienti da stream, facilitando la gestione efficiente e l'elaborazione delle immagini TGA nelle tue applicazioni software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream per caricare un'immagine. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera il valore dei bit per pixel, fornendo informazioni essenziali sulla profondità di colore dell'immagine. Questa proprietà funge da metrica cruciale per comprendere il livello di dettaglio e la ricchezza cromatica presenti nell'immagine, aiutando gli sviluppatori a ottimizzare gli algoritmi di elaborazione e l'allocazione delle risorse per una manipolazione e rendering efficienti dell'immagine.

**Returns:**
int - bit per pixel.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Ottieni il valore dei byte per pixel, che indica la quantità di memoria occupata da ciascun pixel nell'immagine. Questa proprietà è una metrica cruciale per la gestione e l'ottimizzazione della memoria, aiutando gli sviluppatori a allocare risorse e a elaborare i dati dell'immagine in modo efficiente.

**Returns:**
int - byte per pixel.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Recupera un valore booleano che indica se il [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) include un canale alfa, facilitando gli effetti di trasparenza. Questa proprietà fornisce informazioni essenziali per la gestione della composizione e del rendering dell'immagine, aiutando gli sviluppatori a implementare diversi effetti visivi e operazioni di composizione.

**Returns:**
boolean - un valore che indica se questo [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) ha un canale alfa.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Ottieni un valore booleano che indica se il [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) rappresenta un'immagine in scala di grigi. Questa proprietà è fondamentale per distinguere tra immagini a colori e in scala di grigi, aiutando gli sviluppatori ad applicare tecniche di elaborazione e rendering appropriate in base alle caratteristiche cromatiche dell'immagine.

**Returns:**
boolean - un valore che indica se questo [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) è in scala di grigi.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Recupera la larghezza dell'immagine rappresentata da questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Questa proprietà fornisce agli sviluppatori informazioni essenziali sulle dimensioni dell'immagine, facilitando varie attività di manipolazione e elaborazione dell'immagine nelle loro applicazioni software.

**Returns:**
int - larghezza di questa immagine in pixel.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottieni l'altezza dell'immagine racchiusa da questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Questa proprietà fornisce agli sviluppatori dettagli critici riguardo alle dimensioni verticali dell'immagine, consentendo un'integrazione e manipolazione senza interruzioni delle immagini nelle loro soluzioni software.

**Returns:**
int - altezza di questa immagine in pixel.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ottieni informazioni fondamentali sul formato file dell'immagine rappresentata da questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Comprendere il formato file è essenziale per i controlli di compatibilità e per garantire un'integrazione senza soluzione di continuità nei sistemi software, consentendo una elaborazione e manipolazione efficienti delle immagini.

**Returns:**
long - informazioni fondamentali sul formato file dell'immagine rappresentata da questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage).
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Recupera se questa istanza di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) contiene una mappa dei colori. Comprendere la presenza di una mappa dei colori è fondamentale per un'interpretazione accurata e per la manipolazione dei dati cromatici dell'immagine.

**Returns:**
boolean - un valore che indica se questa immagine ha una mappa dei colori.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Ottiene la parte numeratore del valore gamma, che è essenziale per una rappresentazione cromatica accurata nelle immagini. Nelle immagini senza correzione gamma, questo valore dovrebbe essere 1,0. Comprendere e utilizzare questo valore è fondamentale per mantenere la fedeltà dei colori e garantire una resa accurata dell'immagine.

**Returns:**
int - la parte numeratore del valore gamma, che è essenziale per una rappresentazione cromatica accurata nelle immagini.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Recupera la parte denominatore del valore gamma, un fattore integrante nella determinazione della rappresentazione cromatica nelle immagini. Per le immagini prive di correzione gamma, questo valore dovrebbe essere 1,0, garantendo una resa cromatica accurata. Apprezzare e sfruttare questo parametro è fondamentale per mantenere la fedeltà dei colori e ottenere una visualizzazione precisa dell'immagine.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Recupera la componente numeratore del Rapporto di Aspetto dei Pixel, che influenza l'aspetto visivo dei pixel all'interno dell'immagine. Comprendere e manipolare questo valore è essenziale per ottenere una rappresentazione accurata dei pixel e dei rapporti di aspetto nella resa e nella elaborazione delle immagini.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Recupera la parte denominatore del Rapporto di Aspetto dei Pixel, un fattore cruciale nella determinazione dell'aspetto visivo dei pixel all'interno dell'immagine. Questo valore è essenziale per preservare una rappresentazione accurata dei pixel e dei rapporti di aspetto durante le varie operazioni di resa e elaborazione delle immagini, garantendo un output visivo di alta qualità.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Restituisce la coordinata orizzontale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA).

**Returns:**
int - coordinata orizzontale assoluta per l'angolo inferiore sinistro dell'immagine così come posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Imposta la coordinata orizzontale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | coordinata orizzontale assoluta per l'angolo inferiore sinistro dell'immagine così come posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Restituisce la coordinata verticale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA).

**Returns:**
int - coordinata verticale assoluta per l'angolo inferiore sinistro dell'immagine così come posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Imposta la coordinata verticale assoluta per l'angolo inferiore sinistro dell'immagine così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo (ad esempio, la serie TARGA).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | coordinata verticale assoluta per l'angolo inferiore sinistro dell'immagine così come posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello schermo. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Ottiene l'identificatore univoco associato all'immagine. Questo ID funge da punto di riferimento per identificare e distinguere l'immagine dalle altre all'interno di un sistema o di un'applicazione. Impostando o recuperando l'Image ID, è possibile gestire e tracciare le immagini in modo efficace, facilitando processi organizzati di gestione e recupero delle immagini.

Questo campo opzionale contiene informazioni identificative sull'immagine. La lunghezza massima per questo campo è di 255 byte.

**Returns:**
java.lang.String - l'identificatore univoco associato all'immagine.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Imposta l'identificatore univoco associato all'immagine. Questo ID funge da punto di riferimento per identificare e distinguere l'immagine dalle altre all'interno di un sistema o di un'applicazione. Impostando o recuperando l'Image ID, è possibile gestire e tracciare le immagini in modo efficace, facilitando processi organizzati di gestione e recupero delle immagini.

Questo campo opzionale contiene informazioni identificative sull'immagine. La lunghezza massima per questo campo è di 255 byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | l'identificatore univoco associato all'immagine. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Recupera o imposta i commenti forniti dall'autore dell'immagine. Questi commenti spesso contengono informazioni preziose, come descrizioni, annotazioni o contesto aggiuntivo sull'immagine. Accedendo o modificando la proprietà Author Comments, gli sviluppatori possono arricchire i metadati associati all'immagine, fornendo agli utenti approfondimenti e contesto utili riguardo al contenuto o alla creazione dell'immagine. Si tratta di un campo ASCII di 324 byte organizzato in quattro righe di 80 caratteri, ciascuna seguita da un terminatore nullo.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Recupera o imposta i commenti forniti dall'autore dell'immagine. Questi commenti spesso contengono informazioni preziose, come descrizioni, annotazioni o contesto aggiuntivo sull'immagine. Accedendo o modificando la proprietà Author Comments, gli sviluppatori possono arricchire i metadati associati all'immagine, fornendo agli utenti approfondimenti e contesto utili riguardo al contenuto o alla creazione dell'immagine. Si tratta di un campo ASCII di 324 byte organizzato in quattro righe di 80 caratteri, ciascuna seguita da un terminatore nullo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Recupera o imposta il nome dell'autore associato all'immagine. Questa proprietà consente agli sviluppatori di accedere o modificare i metadati del nome dell'autore, fornendo informazioni preziose sul creatore dell'immagine. Utilizzando la proprietà Author Name, gli utenti possono identificare facilmente la persona responsabile della creazione o del contributo all'immagine, migliorando i metadati complessivi e fornendo un contesto utile per gli spettatori. Questo campo è composto da un totale di 40 caratteri ASCII per il nome. Se il campo è utilizzato, dovrebbe contenere il nome della persona che ha creato l'immagine (autore).

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Recupera o imposta il nome dell'autore associato all'immagine. Questa proprietà consente agli sviluppatori di accedere o modificare i metadati del nome dell'autore, fornendo informazioni preziose sul creatore dell'immagine. Utilizzando la proprietà Author Name, gli utenti possono identificare facilmente la persona responsabile della creazione o del contributo all'immagine, migliorando i metadati complessivi e fornendo un contesto utile per gli spettatori. Questo campo è composto da un totale di 40 caratteri ASCII per il nome. Se il campo è utilizzato, dovrebbe contenere il nome della persona che ha creato l'immagine (autore).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nome Autore. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Ottiene il Timestamp Data/Ora. Questo campo definisce il valore per la data e l'ora in cui l'immagine è stata salvata. Sebbene i sistemi operativi tipicamente applichino data e ora ai file, questa funzionalità è fornita perché il sistema operativo può modificare la data e l'ora se il file viene copiato. Utilizzando quest'area, si garantisce una regione non modificata per la registrazione di data e ora.

**Returns:**
java.util.Date - Timestamp Data/Ora.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Imposta il Timestamp Data/Ora. Questo campo definisce il valore per la data e l'ora in cui l'immagine è stata salvata. Anche se i sistemi operativi tipicamente aggiungono data e ora ai file, questa funzionalità è fornita perché il sistema operativo può modificare il timestamp se il file viene copiato. Utilizzando quest'area, si garantisce una regione non modificata per la registrazione di data e ora.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date | Timestamp Data/Ora. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


Recupera o imposta il nome o l'ID del lavoro associato all'immagine. Questa proprietà consente di accedere o modificare i metadati relativi al lavoro o progetto specifico associato all'immagine. Utilizzando la proprietà Job Name/ID, gli utenti possono identificare facilmente il progetto o compito a cui l'immagine si riferisce, facilitando l'organizzazione e la gestione delle risorse immagine all'interno di flussi di lavoro o progetti più ampi.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Recupera o imposta il nome o l'ID del lavoro associato all'immagine. Questa proprietà consente di accedere o modificare i metadati relativi al lavoro o progetto specifico associato all'immagine. Utilizzando la proprietà Job Name/ID, gli utenti possono identificare facilmente il progetto o compito a cui l'immagine si riferisce, facilitando l'organizzazione e la gestione delle risorse immagine all'interno di flussi di lavoro o progetti più ampi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Recupera o imposta il timestamp che indica l'ora del lavoro associata all'immagine. Questa proprietà consente agli sviluppatori di accedere o modificare i metadati temporali relativi al lavoro o progetto specifico associato all'immagine.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Recupera o imposta il timestamp che indica l'ora del lavoro associata all'immagine. Questa proprietà consente agli sviluppatori di accedere o modificare i metadati temporali relativi al lavoro o progetto specifico associato all'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date | Ora del lavoro. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Recupera o imposta il colore chiave associato all'immagine. Questa proprietà consente di accedere o modificare il colore designato come colore chiave per specifici compiti o effetti di elaborazione delle immagini. Utilizzando la proprietà Key Color, gli utenti possono applicare operazioni basate sul colore come chroma keying o sostituzione del colore, migliorando le capacità di manipolazione delle immagini e le possibilità creative.

Il Key Color può essere considerato come il \\u2018colore di sfondo\\u2019 o il \\u2018colore trasparente\\u2019. Questo è il colore dell'area \\u2018non immagine\\u2019 dello schermo, e lo stesso colore a cui lo schermo verrebbe cancellato se cancellato nell'applicazione.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Recupera o imposta il colore chiave associato all'immagine. Questa proprietà consente di accedere o modificare il colore designato come colore chiave per specifici compiti o effetti di elaborazione delle immagini. Utilizzando la proprietà Key Color, gli utenti possono applicare operazioni basate sul colore come chroma keying o sostituzione del colore, migliorando le capacità di manipolazione delle immagini e le possibilità creative.

Il Key Color può essere considerato come il \\u2018colore di sfondo\\u2019 o il \\u2018colore trasparente\\u2019. Questo è il colore dell'area \\u2018non immagine\\u2019 dello schermo, e lo stesso colore a cui lo schermo verrebbe cancellato se cancellato nell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Recupera o imposta un valore booleano che indica se l'immagine contiene un colore trasparente. Questa proprietà è essenziale per identificare se l'immagine supporta la trasparenza, aiutandoti a implementare una gestione appropriata delle operazioni legate alla trasparenza come blending, compositing o masking.

**Returns:**
boolean - un valore che indica se l'immagine ha un colore trasparente.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Recupera o imposta un valore booleano che indica se l'immagine contiene un colore trasparente. Questa proprietà è essenziale per identificare se l'immagine supporta la trasparenza, aiutandoti a implementare una gestione appropriata delle operazioni legate alla trasparenza come blending, compositing o masking.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se l'immagine ha un colore trasparente. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Recupera o imposta il colore di sfondo dell'immagine. Questa proprietà consente di specificare il colore utilizzato per lo sfondo dell'immagine, garantendo coerenza e migliorando la presentazione visiva. È particolarmente utile per scenari in cui l'immagine viene visualizzata su uno sfondo di colore diverso o quando si rende l'immagine su un'altra tela.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Recupera o imposta il colore di sfondo dell'immagine. Questa proprietà consente di specificare il colore utilizzato per lo sfondo dell'immagine, garantendo coerenza e migliorando la presentazione visiva. È particolarmente utile per scenari in cui l'immagine viene visualizzata su uno sfondo di colore diverso o quando si rende l'immagine su un'altra tela.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | il colore di sfondo. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Recupera o imposta un valore che indica se l'immagine contiene un colore di sfondo. Questa proprietà è utile per determinare se l'immagine include un colore di sfondo distinto rispetto al contenuto in primo piano. Consente di personalizzare l'elaborazione o il rendering dell'immagine in base alla presenza o assenza di un colore di sfondo.

**Returns:**
boolean - un valore che indica se l'immagine ha un colore di sfondo.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Recupera o imposta un valore che indica se l'immagine contiene un colore di sfondo. Questa proprietà è utile per determinare se l'immagine include un colore di sfondo distinto rispetto al contenuto in primo piano. Consente di personalizzare l'elaborazione o il rendering dell'immagine in base alla presenza o assenza di un colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se l'immagine ha un colore di sfondo. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Recupera o imposta la versione del software associata all'immagine. La lunghezza accettata per la stringa di versione è tipicamente di 3-4 caratteri. Questa proprietà è utile per tracciare il software utilizzato per creare o manipolare l'immagine e può fornire contesto prezioso per l'elaborazione delle immagini e i controlli di compatibilità.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Recupera o imposta la versione del software associata all'immagine. La lunghezza accettata per la stringa di versione è tipicamente di 3-4 caratteri. Questa proprietà è utile per tracciare il software utilizzato per creare o manipolare l'immagine e può fornire contesto prezioso per l'elaborazione delle immagini e i controlli di compatibilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Versione Software. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Recupera o imposta la componente lettera della versione del software associata all'immagine. Questa proprietà rappresenta un dettaglio aggiuntivo all'interno della stringa di versione del software e può essere utile per una differenziazione più fine delle versioni.

**Returns:**
char - Parte lettera della versione del software.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Recupera o imposta la componente lettera della versione del software associata all'immagine. Questa proprietà rappresenta un dettaglio aggiuntivo all'interno della stringa di versione del software e può essere utile per una differenziazione più fine delle versioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | char | Parte lettera della versione del software. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Recupera o imposta la componente numerica della versione del software associata all'immagine. Questa proprietà rappresenta la parte numerica della stringa della versione del software, fornendo informazioni importanti sulla versione del software utilizzato per creare o modificare l'immagine.

**Returns:**
int - Parte numerica della versione del software.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Recupera o imposta la componente numerica della versione del software associata all'immagine. Questa proprietà rappresenta la parte numerica della stringa della versione del software, fornendo informazioni importanti sulla versione del software utilizzato per creare o modificare l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Parte numerica della versione del software. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Gestisce l'identificazione del software (ID) associata all'immagine, consentendo fino a 40 caratteri ASCII. Questa proprietà serve come mezzo per identificare in modo univoco il software utilizzato nella creazione o nell'elaborazione dell'immagine, fornendo metadati preziosi per scopi organizzativi e informativi.

**Returns:**
java.lang.String - ID del software.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Gestisce l'identificazione del software (ID) associata all'immagine, consentendo fino a 40 caratteri ASCII. Questa proprietà serve come mezzo per identificare in modo univoco il software utilizzato nella creazione o nell'elaborazione dell'immagine, fornendo metadati preziosi per scopi organizzativi e informativi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | ID del software. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Esegue un confronto di uguaglianza tra due immagini TGA, considerando sia la prima che la seconda immagine coinvolte nel processo di confronto. Questo metodo facilita una valutazione diretta dell'uguaglianza delle immagini, garantendo un'analisi accurata e decisioni informate nei flussi di lavoro di elaborazione delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Prima [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) che partecipa al confronto. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Seconda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) che partecipa al confronto. |

**Returns:**
boolean - Risultati del confronto.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Esegue un confronto di non uguaglianza tra due immagini TGA, valutando sia la prima che la seconda immagine coinvolte nel confronto. Questo metodo aiuta a identificare discrepanze o differenze tra le immagini, consentendo un'analisi precisa e decisioni informate nelle attività di elaborazione delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Prima [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) che partecipa al confronto. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Seconda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) che partecipa al confronto. |

**Returns:**
boolean - Risultati del confronto.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Produce un duplicato dell'istanza corrente, generando un nuovo oggetto che clona tutti gli attributi e le proprietà dell'originale. Questo metodo facilita la creazione di copie identiche, garantendo l'integrità dei dati e preservando lo stato dell'istanza corrente senza influire sull'oggetto originale.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Replica le proprietà di un altro oggetto [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), creando una nuova istanza con attributi identici. Questa operazione assicura la preservazione dell'integrità dei dati e facilita la duplicazione delle proprietà dell'immagine senza alterare l'oggetto sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Altro [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


In un confronto di uguaglianza, il metodo valuta se l'istanza corrente di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) è uguale alla seconda immagine fornita come parametro. Questa operazione facilita la determinazione se due immagini TGA sono identiche, aiutando nelle attività di elaborazione e confronto delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Seconda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) che partecipa al confronto. |

**Returns:**
boolean - Risultati del confronto.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Il metodo esegue un confronto di uguaglianza tra l'istanza corrente di [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) e un altro oggetto fornito come parametro. In particolare, valuta se le proprietà dell'immagine corrente corrispondono a quelle del secondo oggetto, contribuendo a determinare la loro equivalenza per scopi di confronto all'interno dei flussi di lavoro di elaborazione delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | java.lang.Object | Seconda [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) che partecipa al confronto. |

**Returns:**
boolean - Risultati del confronto.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Il metodo "rotateFlip" consente operazioni di rotazione e capovolgimento sull'immagine. Offre una funzionalità versatile per manipolare l'orientamento dell'immagine, permettendo agli utenti di eseguire rotazioni e capovolgimenti secondo le loro esigenze, facilitando attività efficienti di elaborazione delle immagini all'interno delle applicazioni software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Recupera il codice hash dell'istanza corrente. Tuttavia, è importante notare che questo codice hash potrebbe non essere adatto per l'uso come chiave, in particolare perché le istanze della classe TgaImage non sono immutabili.

**Returns:**
int - Codice hash di questa istanza.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia l'immagine a una regione specificata. Questo metodo consente di definire un'area rettangolare all'interno dell'immagine da conservare, scartando il resto. Questa operazione è utile per focalizzarsi su contenuti specifici dell'immagine o per rimuovere parti indesiderate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Ritaglia l'immagine specificando gli spostamenti per i bordi sinistro, destro, superiore e inferiore. Questo metodo consente di tagliare l'immagine spostando i suoi bordi in modo indipendente lungo gli assi orizzontale e verticale. Regolando questi spostamenti, è possibile controllare con precisione quali parti dell'immagine conservare, ritagliandola efficacemente alle dimensioni desiderate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | int | Lo spostamento sinistro. |
| rightShift | int | Lo spostamento destro. |
| topShift | int | Lo spostamento superiore. |
| bottomShift | int | Lo spostamento inferiore. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine applicando impostazioni specifiche per mantenere le dimensioni e il rapporto d'aspetto desiderati. Personalizzando le impostazioni dell'immagine, è possibile ridimensionare efficacemente l'immagine garantendo la qualità visiva ottimale e la compatibilità con diversi dispositivi di visualizzazione o applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Regola le dimensioni dell'immagine utilizzando un tipo di ridimensionamento specificato, che determina come viene eseguita l'operazione di ridimensionamento. Questo metodo offre flessibilità nel ridimensionare le immagini secondo diversi algoritmi o tecniche. Scegliendo il tipo di ridimensionamento appropriato, è possibile ottenere il giusto equilibrio tra qualità dell'immagine ed efficienza computazionale in base a requisiti o preferenze specifici.

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


Ruota l'immagine attorno al suo centro di un angolo specificato mantenendo la proporzionalità del ridimensionamento e preservando il colore di sfondo. Questo metodo consente una manipolazione precisa dell'immagine, garantendo che la rotazione mantenga l'equilibrio visivo e la coerenza con il colore di sfondo specificato. È ideale per attività in cui è necessaria una rotazione accurata attorno al centro, come la correzione dell'orientamento o regolazioni artistiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | Se impostato su `true` la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

