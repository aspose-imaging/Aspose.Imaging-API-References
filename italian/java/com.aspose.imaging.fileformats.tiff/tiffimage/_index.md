---
title: "TiffImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Elabora le immagini raster Tagged Image File Format (TIFF) con la nostra API, offrendo supporto completo per varie risoluzioni e funzionalità avanzate di modifica come la manipolazione dei dati EXIF e i canali alfa."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Elabora le immagini raster Tagged Image File Format (TIFF) con la nostra API, offrendo supporto completo per varie risoluzioni e funzionalità avanzate di modifica come la manipolazione dei dati EXIF e i canali alfa. Normalizza gli angoli delle immagini scansionate, ridimensiona, trasforma in scala di grigi e applica filtri, correzioni gamma e regolazioni dei parametri dell'immagine con facilità. Gestisci senza problemi i file TIFF multi-frame, crea percorsi grafici, aggiungi forme e salva le immagini in diversi formati senza sforzo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Inizializza un nuovo oggetto della classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), specificando il parametro frame. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Crea una nuova istanza della classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), fornendo un elenco di frame come parametro. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupera il valore del formato file associato all'immagine. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Indica se i componenti richiedono la premoltiplicazione, garantendo una gestione efficiente degli elementi visivi. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Indica se i componenti richiedono la premoltiplicazione, garantendo una gestione efficiente degli elementi visivi. |
| [getByteOrder()](#getByteOrder--) | Attiva/disattiva l'ordine dei byte per i file TIFF senza interruzioni, garantendo un controllo preciso sull'interpretazione dei dati. |
| [setByteOrder(int value)](#setByteOrder-int-) | Attiva/disattiva l'ordine dei byte per i file TIFF senza interruzioni, garantendo un controllo preciso sull'interpretazione dei dati. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Recupera la risoluzione orizzontale dell'[Image](../../com.aspose.imaging/image) specificata in pixel per pollice, facilitando regolazioni precise e capacità di rendering. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Modifica la risoluzione orizzontale dell'[Image](../../com.aspose.imaging/image) specificata in pixel per pollice, facilitando regolazioni precise e capacità di rendering. |
| [getVerticalResolution()](#getVerticalResolution--) | Accedi alla risoluzione verticale dell'[Image](../../com.aspose.imaging/image) designata in pixel per pollice, consentendo regolazioni precise e ottimizzazioni del rendering. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Accedi alla risoluzione verticale dell'[Image](../../com.aspose.imaging/image) designata in pixel per pollice, consentendo regolazioni precise e ottimizzazioni del rendering. |
| [getActiveFrame()](#getActiveFrame--) | Gestisci il frame attivo senza interruzioni, facilitando la navigazione dinamica e la manipolazione nel contesto designato. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Gestisci il frame attivo senza interruzioni, facilitando la navigazione dinamica e la manipolazione nel contesto designato. |
| [getFrames()](#getFrames--) | Recupera un array di istanze di [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), consentendo un accesso completo e la manipolazione dei singoli frame all'interno dell'immagine TIFF. |
| [getPageCount()](#getPageCount--) | Recupera il conteggio totale delle pagine nel documento specificato, facilitando una navigazione efficiente e la gestione di contenuti multipagina. |
| [getPages()](#getPages--) | Accedi alle pagine del documento senza interruzioni, consentendo una navigazione dinamica e la manipolazione all'interno della struttura dei contenuti. |
| [hasAlpha()](#hasAlpha--) | Determina se l'immagine possiede un canale alfa, fornendo informazioni cruciali per le operazioni di rendering e composizione. |
| [removeMetadata()](#removeMetadata--) | Rimuove i metadati di questa istanza di immagine impostando il valore di `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) a `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Recupera le opzioni derivanti dalle impostazioni del file originale, facilitando la conservazione senza interruzioni dei parametri chiave come la profondità di bit e altri attributi essenziali dell'immagine originale. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Incorpora una nuova pagina nell'immagine esistente senza interruzioni, ampliandone il contenuto e la versatilità. |
| [alignResolutions()](#alignResolutions--) | Implementa il metodo di supporto AlignResolutions per sincronizzare le risoluzioni orizzontale e verticale, garantendo uniformità nelle dimensioni dell'immagine. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Stabilisce la risoluzione per il [RasterImage](../../com.aspose.imaging/rasterimage) specificato, consentendo un controllo preciso sul rendering dell'immagine e sulle proprietà di visualizzazione. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Utilizza il metodo NormalizeAngle specificamente progettato per documenti di testo scansionati per rettificare le scansioni inclinate, garantendo un allineamento preciso. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Incorpora il frame specificato senza soluzione di continuità nell'immagine, ampliandone il contenuto e la versatilità. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Aggiungi i frame dall'immagine specificata senza soluzione di continuità al frame corrente, consolidandone il contenuto e migliorando la flessibilità compositiva. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Integra l'array di frame senza soluzione di continuità nell'immagine, arricchendone il contenuto e la versatilità. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Inserisci il nuovo frame all'indice specificato all'interno della sequenza di frame, garantendo un controllo preciso sulla disposizione dei frame. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Sostituisci il frame nella posizione designata con un altro frame senza soluzione di continuità, facilitando la gestione dinamica dei frame nella sequenza di immagini. |
| [removeFrame(int index)](#removeFrame-int-) | Elimina senza sforzo il frame identificato dal suo indice dalla sequenza di immagini, semplificando la gestione dei frame nella tua applicazione. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Rimuovi in modo efficiente il frame specificato dalla sequenza di immagini, facilitando una gestione semplificata dei frame nella tua applicazione. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Esegui un'operazione di ridimensionamento proporzionale sull'immagine, preservando il suo rapporto d'aspetto mentre ne regoli le dimensioni. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Regola la larghezza dell'immagine mantenendo il suo rapporto d'aspetto, garantendo un ridimensionamento proporzionale per una presentazione visiva ottimale. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Esegui una regolazione proporzionale dell'altezza dell'immagine, preservando il suo rapporto d'aspetto per mantenere un'integrità visiva coerente. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Esegui rotazione, capovolgimento o una combinazione di entrambe le operazioni esclusivamente sul frame attivo. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Esegui il dithering sull'immagine corrente per migliorare la sua qualità visiva e ridurre gli artefatti di bande di colore. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia l'immagine usando una regione rettangolare specificata, consentendo una selezione precisa del contenuto desiderato. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Esegui il ritaglio sull'immagine specificando gli spostamenti a sinistra, destra, in alto e in basso. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Applica la binarizzazione all'immagine usando una soglia predefinita, convertendola in un'immagine binaria con regioni di primo piano e sfondo distinte. |
| [binarizeOtsu()](#binarizeOtsu--) | Utilizza la soglia di Otsu per eseguire la binarizzazione sull'immagine, determinando automaticamente il valore di soglia ottimale basato sull'istogramma dell'immagine. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Implementa la binarizzazione sull'immagine impiegando l'algoritmo di soglia adattiva di Bradley con soglia basata su immagine integrale. |
| [grayscale()](#grayscale--) | Converti l'immagine nella sua rappresentazione in scala di grigi, trasformandola in un'immagine a canale singolo dove ogni pixel rappresenta l'intensità. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Applica la correzione gamma all'immagine, regolando le intensità dei pixel per ottenere il bilanciamento colore desiderato. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Esegui la correzione gamma sull'immagine usando coefficienti individuali per i canali rosso, verde e blu, consentendo regolazioni precise del bilanciamento colore e del contrasto. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implementa la regolazione della `brightness` per l'immagine, consentendo la modifica dei livelli di luminanza complessiva. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Migliora il contrasto dell'istanza [Image](../../com.aspose.imaging/image), amplificando le differenze tra le sue aree chiare e scure. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtra il contenuto all'interno del rettangolo specificato, applicando un filtro di elaborazione immagini designato per migliorare o modificare la regione selezionata. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Regola le dimensioni dell'immagine in base alle impostazioni specificate, consentendo un controllo preciso su dimensioni, rapporto d'aspetto e comportamento di scaling. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Crea il GraphicsPath usando PathResources dall'immagine TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Disegna una linea rossa e salva l'immagine
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Crea una Figure rettangolare per GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Crea GraphicsPath usando la nostra Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Imposta PathResources usando GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Salva l'immagine
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Inizializza un nuovo oggetto della classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), specificando il parametro frame. Questo costruttore facilita la creazione di un'istanza di TiffImage, consentendo agli sviluppatori di specificare il frame da caricare o elaborare, semplificando le attività di gestione delle immagini Tiff nelle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Il frame tiff con cui inizializzare l'immagine. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Crea una nuova istanza della classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), fornendo un elenco di frame come parametro. Questo costruttore consente l'inizializzazione di un oggetto TiffImage con più frame, facilitando la gestione efficiente e l'elaborazione di sequenze di immagini TIFF all'interno delle applicazioni software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | I frame. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera il valore del formato file associato all'immagine. Questa proprietà serve come aspetto critico del recupero dei metadati dell'immagine, consentendo alle applicazioni software di identificare e interpretare il formato dei dati dell'immagine in modo efficiente.

**Returns:**
long - un valore del formato file
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Indica se i componenti richiedono la premoltiplicazione, garantendo una gestione efficiente degli elementi visivi. Migliora i processi di rendering attivando o disattivando questa proprietà, semplificando i flussi di lavoro grafici per prestazioni ottimizzate.

**Returns:**
boolean - `true` se i componenti devono essere premoltiplicati; altrimenti, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Indica se i componenti richiedono la premoltiplicazione, garantendo una gestione efficiente degli elementi visivi. Migliora i processi di rendering attivando o disattivando questa proprietà, semplificando i flussi di lavoro grafici per prestazioni ottimizzate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se i componenti devono essere premoltiplicati; altrimenti, `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Salva i pixel per l'intera immagine.
    image.savePixels(image.getBounds(), colors);

    // I pixel sono memorizzati nell'immagine originale nella forma non premoltiplicata.
    // È necessario specificare esplicitamente l'opzione corrispondente per ottenere componenti di colore premoltiplicati.
    // I componenti di colore premoltiplicati sono calcolati con le formule:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//L'output avrà questo aspetto:
//Colore originale: Color [A=127, R=255, G=0, B=0]
//Colore premoltiplicato: Color [A=127, R=127, G=0, B=0]
//Colore originale: Color [A=127, R=0, G=255, B=0]
//Colore premoltiplicato: Color [A=127, R=0, G=127, B=0]
//Colore originale: Color [A=127, R=0, G=0, B=255]
//Colore premoltiplicato: Color [A=127, R=0, G=0, B=127]
//Colore originale: Color [A=127, R=255, G=255, B=0]
//Colore premoltiplicato: Color [A=127, R=127, G=127, B=0]
//Colore originale: Color [A=127, R=255, G=0, B=255]
//Colore premoltiplicato: Color [A=127, R=127, G=0, B=127]
//Colore originale: Color [A=127, R=0, G=255, B=255]
//Colore premoltiplicato: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


Attiva/disattiva l'ordine dei byte per i file TIFF in modo fluido, garantendo un controllo preciso sull'interpretazione dei dati. Potenzia le tue applicazioni con la flessibilità di adattarsi a specifiche di file diverse, migliorando la compatibilità e l'efficienza nell'elaborazione dei dati.

**Returns:**
int - L'ordine dei byte TIFF.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


Attiva/disattiva l'ordine dei byte per i file TIFF in modo fluido, garantendo un controllo preciso sull'interpretazione dei dati. Potenzia le tue applicazioni con la flessibilità di adattarsi a specifiche di file diverse, migliorando la compatibilità e l'efficienza nell'elaborazione dei dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'ordine dei byte TIFF. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Recupera la risoluzione orizzontale dell'[Image](../../com.aspose.imaging/image) specificata in pixel per pollice, facilitando regolazioni precise e capacità di rendering. Accedi facilmente ai metadati essenziali dell'immagine, potenziando flussi di lavoro di elaborazione delle immagini semplificati per migliorare l'esperienza dell'utente.

**Returns:**
double - La risoluzione orizzontale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ottieni la risoluzione orizzontale e verticale dell'immagine TIFF.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 96.0
// La risoluzione verticale, in pixel per pollice: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Modifica la risoluzione orizzontale dell'[Image](../../com.aspose.imaging/image) specificata in pixel per pollice, facilitando regolazioni precise e capacità di rendering. Accedi facilmente ai metadati essenziali dell'immagine, potenziando flussi di lavoro di elaborazione delle immagini semplificati per migliorare l'esperienza dell'utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione orizzontale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Accedi alla risoluzione verticale dell'[Image](../../com.aspose.imaging/image) designata in pixel per pollice, consentendo regolazioni precise e ottimizzazioni del rendering. Utilizza facilmente i dati essenziali dell'immagine per semplificare i flussi di lavoro di elaborazione delle immagini, garantendo qualità e prestazioni superiori nelle tue applicazioni.

**Returns:**
double - La risoluzione verticale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ottieni la risoluzione orizzontale e verticale dell'immagine TIFF.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 96.0
// La risoluzione verticale, in pixel per pollice: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Accedi alla risoluzione verticale dell'[Image](../../com.aspose.imaging/image) designata in pixel per pollice, consentendo regolazioni precise e ottimizzazioni del rendering. Utilizza facilmente i dati essenziali dell'immagine per semplificare i flussi di lavoro di elaborazione delle immagini, garantendo qualità e prestazioni superiori nelle tue applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione verticale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Gestisci il frame attivo in modo fluido, facilitando la navigazione dinamica e la manipolazione nel contesto designato. Potenzia la tua applicazione per interagire in modo efficiente con i contenuti multimediali, migliorando il coinvolgimento e la produttività dell'utente.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Questo è Font e Brush per disegnare testo su singoli fotogrammi.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crea 5 fotogrammi
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crea un'immagine PNG e disegna il numero di pagina su di essa.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crea un fotogramma basato sull'immagine PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Aggiungi il fotogramma all'immagine TIFF.
        tiffImage.addFrame(frame);
    }

    // L'immagine è stata creata con un unico fotogramma predefinito. Rimuoviamolo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Non dimenticare di eliminare il fotogramma se non lo aggiungerai a un altro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Gestisci il frame attivo in modo fluido, facilitando la navigazione dinamica e la manipolazione nel contesto designato. Potenzia la tua applicazione per interagire in modo efficiente con i contenuti multimediali, migliorando il coinvolgimento e la produttività dell'utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Frame attivo. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Questo è Font e Brush per disegnare testo su singoli fotogrammi.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crea 5 fotogrammi
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crea un'immagine PNG e disegna il numero di pagina su di essa.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crea un fotogramma basato sull'immagine PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Aggiungi il fotogramma all'immagine TIFF.
        tiffImage.addFrame(frame);
    }

    // L'immagine è stata creata con un unico fotogramma predefinito. Rimuoviamolo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Non dimenticare di eliminare il fotogramma se non lo aggiungerai a un altro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


Recupera un array di istanze di [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), consentendo un accesso completo e la manipolazione dei singoli frame all'interno dell'immagine TIFF. Sfrutta la potenza di questo array per semplificare i flussi di lavoro di elaborazione delle immagini, garantendo un controllo preciso e l'ottimizzazione del contenuto visivo.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] - l'array di [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe).

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Questo è Font e Brush per disegnare testo su singoli fotogrammi.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crea 5 fotogrammi
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crea un'immagine PNG e disegna il numero di pagina su di essa.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crea un fotogramma basato sull'immagine PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Aggiungi il fotogramma all'immagine TIFF.
        tiffImage.addFrame(frame);
    }

    // L'immagine è stata creata con un unico fotogramma predefinito. Rimuoviamolo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Non dimenticare di eliminare il fotogramma se non lo aggiungerai a un altro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il conteggio totale delle pagine all'interno del documento specificato, facilitando una navigazione efficiente e la gestione di contenuti multipagina. Integra questa funzionalità per migliorare l'esperienza dell'utente, consentendo un accesso fluido a strutture documentali complete.

**Returns:**
int - il conteggio delle pagine.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accedi alle pagine del documento in modo fluido, consentendo una navigazione dinamica e la manipolazione all'interno della struttura del contenuto. Potenzia la tua applicazione con un accesso efficiente alle singole pagine, facilitando l'elaborazione semplificata dei documenti e migliorando l'interazione dell'utente.

**Returns:**
com.aspose.imaging.Image[] - le pagine.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determina se l'immagine ha un canale alfa, fornendo informazioni cruciali per le operazioni di rendering e composizione. Integra questa funzionalità per ottimizzare i flussi di lavoro di elaborazione visiva, garantendo una rappresentazione accurata e la manipolazione degli elementi trasparenti.

**Returns:**
boolean - `true` se è presente un canale alfa.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Se il frame TIFF attivo ha un canale alfa, allora l'intera immagine TIFF è considerata dotata di canale alfa.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// ImageFile=c:\\temp\\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Rimuove i metadati di questa istanza di immagine impostando il valore di `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) a `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupera le opzioni derivanti dalle impostazioni del file originale, facilitando la conservazione fluida dei parametri chiave come la profondità di bit e altri attributi essenziali dell'immagine originale. Utilizza questo metodo per mantenere fedeltà e coerenza nelle attività di elaborazione delle immagini, garantendo risultati ottimali senza alterazioni inutili. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e poi la salviamo usando il metodo [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), verrà prodotta un'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, usa questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorpora una nuova pagina nell'immagine esistente in modo fluido, ampliandone il contenuto e la versatilità. Utilizza questo metodo per migliorare la composizione e la gestione dei documenti, consentendo una gestione efficiente delle immagini multipagina nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La pagina da aggiungere. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Implementa il metodo di supporto AlignResolutions per sincronizzare le risoluzioni orizzontali e verticali, garantendo uniformità nelle dimensioni dell'immagine. Questa funzionalità facilita flussi di lavoro di elaborazione delle immagini semplificati armonizzando i parametri di risoluzione, ottimizzando la qualità visiva e la coerenza su varie piattaforme e dispositivi.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Stabilisce la risoluzione per il [RasterImage](../../com.aspose.imaging/rasterimage) specificato, consentendo un controllo preciso sul rendering e sulle proprietà di visualizzazione dell'immagine. Integra questa funzionalità per ottimizzare l'output visivo e garantire la compatibilità con diversi dispositivi e piattaforme di output, migliorando l'esperienza complessiva dell'utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpiX | double | La risoluzione orizzontale, in punti per pollice, del [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La risoluzione verticale, in punti per pollice, del [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ottieni la risoluzione orizzontale e verticale dell'immagine TIFF.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 96.0
// La risoluzione verticale, in pixel per pollice: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Utilizza il metodo NormalizeAngle specificamente progettato per documenti di testo scansionati per correggere scansioni inclinate, garantendo un allineamento accurato. Integra senza soluzione di continuità questa funzionalità nei tuoi flussi di lavoro di elaborazione del testo per migliorare la leggibilità e la qualità dei documenti, aumentando l'efficienza complessiva nel riconoscimento e nell'analisi del testo. Questo metodo utilizza i metodi [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) e [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeProportionally | boolean | se impostato su `true` le dimensioni dell'immagine verranno modificate in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Incorpora il frame specificato nell'immagine in modo fluido, ampliandone il contenuto e la versatilità. Utilizza questo metodo per migliorare la composizione e la gestione delle immagini, consentendo una gestione efficiente delle immagini multi-frame nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Il frame da aggiungere. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Questo è Font e Brush per disegnare testo su singoli fotogrammi.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crea 5 fotogrammi
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crea un'immagine PNG e disegna il numero di pagina su di essa.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crea un fotogramma basato sull'immagine PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Aggiungi il fotogramma all'immagine TIFF.
        tiffImage.addFrame(frame);
    }

    // L'immagine è stata creata con un unico fotogramma predefinito. Rimuoviamolo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Non dimenticare di eliminare il fotogramma se non lo aggiungerai a un altro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Aggiungi i frame dall'immagine specificata nell'attuale frame in modo fluido, consolidandone il contenuto e migliorando la flessibilità compositiva. Integra questo metodo per semplificare la gestione e la manipolazione dei frame nella tua applicazione, facilitando una gestione efficiente delle immagini multi-frame.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | L'immagine di origine. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Integra l'array di frame nell'immagine in modo fluido, arricchendone il contenuto e la versatilità. Utilizza questo metodo per migliorare la composizione e la gestione delle immagini, consentendo una gestione efficiente delle immagini multi-frame nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | L'array di frame da aggiungere |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


Inserisci il nuovo frame all'indice specificato all'interno della sequenza di frame, garantendo un controllo preciso sulla disposizione dei frame. Utilizza questo metodo per gestire efficacemente le sequenze di frame, facilitando la manipolazione dinamica e l'organizzazione del contenuto dell'immagine nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice di `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Il frame da inserire. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


Sostituisci il frame nella posizione designata con un altro frame in modo fluido, facilitando la gestione dinamica dei frame nella sequenza di immagini. Integra questo metodo per migliorare la flessibilità e la precisione nella manipolazione dei frame, garantendo un'organizzazione e una presentazione ottimali del contenuto dell'immagine nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | La posizione del frame basata su zero. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Il frame da sostituire. |

Nota: non dimenticare di eliminare/chiudere il frame se non lo aggiungerai a un altro TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Elimina senza sforzo il frame identificato dal suo indice nella sequenza di immagini, semplificando la gestione dei frame nella tua applicazione. Integra questa funzionalità per migliorare l'efficienza e la precisione nella manipolazione dei frame, facilitando un'organizzazione e una presentazione fluide del contenuto dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | index | int | Indice del frame da rimuovere. |

--------------------

Nota: non dimenticare di Dispose il frame se non lo aggiungerai a un altro TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Questo è Font e Brush per disegnare testo su singoli fotogrammi.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crea 5 fotogrammi
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crea un'immagine PNG e disegna il numero di pagina su di essa.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crea un fotogramma basato sull'immagine PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Aggiungi il fotogramma all'immagine TIFF.
        tiffImage.addFrame(frame);
    }

    // L'immagine è stata creata con un unico fotogramma predefinito. Rimuoviamolo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Non dimenticare di eliminare il fotogramma se non lo aggiungerai a un altro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Rimuovi in modo efficiente il frame specificato dalla sequenza di immagini, facilitando una gestione semplificata dei frame nella tua applicazione. Integra questa funzionalità per migliorare la precisione e la flessibilità nella manipolazione dei frame, garantendo un'organizzazione e una presentazione fluide del contenuto dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Il frame da rimuovere. |

--------------------

Nota: non dimenticare di Dispose il frame se non lo aggiungerai a un altro TiffImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Esegui un'operazione di ridimensionamento proporzionale sull'immagine, preservando il suo rapporto d'aspetto mentre ne regoli le dimensioni. Utilizza questo metodo per scalare dinamicamente le immagini nella tua applicazione, garantendo una rappresentazione visiva coerente dell'integrità del contenuto. Il ridimensionamento proporzionale ridimensionerà ogni frame secondo il rapporto `newWidth`/width e `newHeight`/height.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Regola la larghezza dell'immagine mantenendo il suo rapporto d'aspetto, garantendo un ridimensionamento proporzionale per una presentazione visiva ottimale. Utilizza questo metodo per scalare dinamicamente le immagini nella tua applicazione, facilitando una resa coerente ed esteticamente gradevole su vari contesti di visualizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| resizeType | int | Tipo di ridimensionamento. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Questo esempio carica un'immagine TIFF e la ridimensiona proporzionalmente utilizzando vari metodi di ridimensionamento. Viene specificata solo la larghezza, l'altezza viene calcolata automaticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
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


Esegui una regolazione proporzionale dell'altezza dell'immagine, preservando il suo rapporto d'aspetto per mantenere un'integrità visiva coerente. Utilizza questo metodo per ridimensionare dinamicamente le immagini nella tua applicazione, garantendo una visualizzazione ottimale su diverse piattaforme e dispositivi senza compromettere la qualità del contenuto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |
| resizeType | int | Tipo di ridimensionamento. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Questo esempio carica un'immagine TIFF e la ridimensiona proporzionalmente utilizzando vari metodi di ridimensionamento. Viene specificata solo l'altezza, la larghezza viene calcolata automaticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
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


Esegui rotazione, capovolgimento o una combinazione di entrambe le operazioni esclusivamente sul fotogramma attivo. Questo metodo consente una manipolazione precisa dei singoli fotogrammi all'interno della sequenza di immagini, migliorando la flessibilità nella modifica e composizione delle immagini nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Questa è una classe di supporto.
class Utils {
    // Restituisce una rappresentazione stringa del tipo di rotazione e capovolgimento.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Ecco l'esempio principale
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Ruota, capovolgi e salva nel file di output.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Esegui la dithering sull'immagine corrente per migliorare la sua qualità visiva e ridurre gli artefatti di bande di colore. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per garantire transizioni più fluide tra i colori, ottenendo un aspetto complessivo dell'immagine migliorato e una maggiore chiarezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Esegui il dithering a soglia usando una palette di colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Esegui il dithering Floyd usando una palette di colori a 1 bit che contiene solo 2 colori - nero e bianco.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia l'immagine utilizzando una regione rettangolare specificata, consentendo una selezione precisa del contenuto desiderato. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per rimuovere in modo efficiente le aree indesiderate e concentrarti sui dettagli essenziali, migliorando la chiarezza e la composizione complessiva dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |


**Example: The following example crops a TIFF image.**
Il seguente esempio ritaglia un'immagine TIFF. L'area di ritaglio è specificata tramite Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ritaglia l'immagine. L'area di ritaglio è la zona rettangolare centrale dell'immagine.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Salva l'immagine ritagliata in PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Esegui il ritaglio dell'immagine specificando gli spostamenti a sinistra, destra, in alto e in basso. Questo metodo consente una selezione precisa della porzione desiderata dell'immagine, facilitando la rimozione efficiente delle aree indesiderate e concentrandosi sul contenuto essenziale. Integra questa funzionalità nel tuo pipeline di elaborazione delle immagini per migliorare la chiarezza e la composizione secondo le necessità nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | int | Lo spostamento sinistro. |
| rightShift | int | Lo spostamento destro. |
| topShift | int | Lo spostamento superiore. |
| bottomShift | int | Lo spostamento inferiore. |


**Example: The following example crops a TIFF image.**
Il seguente esempio ritaglia un'immagine TIFF. L'area di ritaglio è specificata tramite i margini Left, Top, Right, Bottom.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ritaglia di nuovo. Imposta un margine del 10% della dimensione dell'immagine.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Salva l'immagine ritagliata in PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Applica la binarizzazione all'immagine utilizzando una soglia predefinita, convertendola in un'immagine binaria con regioni di primo piano e sfondo distinte. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per facilitare le attività di segmentazione e estrazione delle caratteristiche, migliorando l'accuratezza e l'efficienza dell'analisi delle immagini nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato il valore 255, altrimenti 0. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
Il seguente esempio binarizza un'immagine TIFF con la soglia predefinita. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarizza l'immagine con un valore di soglia di 127.
    // Se il valore di grigio corrispondente di un pixel è maggiore di 127, gli verrà assegnato un valore di 255, altrimenti 0.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Utilizza la soglia di Otsu per eseguire la binarizzazione dell'immagine, determinando automaticamente il valore soglia ottimale in base all'istogramma dell'immagine. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ottenere una segmentazione efficace e l'estrazione delle caratteristiche, migliorando l'accuratezza e l'affidabilità delle attività di analisi delle immagini nella tua applicazione.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
Il seguente esempio binarizza un'immagine TIFF con la soglia di Otsu. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarizza l'immagine con la sogliatura di Otsu.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Implementa la binarizzazione sull'immagine impiegando l'algoritmo di soglia adattiva di Bradley con soglia dell'immagine integrale. Questo approccio calcola dinamicamente soglie locali basate sul vicinato dell'immagine, migliorando l'adattabilità a condizioni di illuminazione variabili e garantendo una segmentazione robusta per le successive attività di elaborazione nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel. |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
Il seguente esempio binarizza un'immagine TIFF con l'algoritmo di soglia adattiva di Bradley con la dimensione della finestra specificata. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarizza l'immagine con una differenza di luminosità di 5. La luminosità è la differenza tra un pixel e la media di una finestra 10 x 10 di pixel centrata su quel pixel.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Converti l'immagine nella sua rappresentazione in scala di grigi, trasformandola in un'immagine a canale singolo dove ogni pixel rappresenta l'intensità. Integra questo metodo nel tuo pipeline di elaborazione delle immagini per semplificare l'analisi e migliorare la compatibilità con gli algoritmi basati sulla scala di grigi, facilitando varie attività di visione artificiale e analisi delle immagini nella tua applicazione.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
Il seguente esempio trasforma un'immagine TIFF a colori nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da tonalità di grigio e contengono solo informazioni di intensità.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Applica la correzione gamma all'immagine, regolando le intensità dei pixel per ottenere il bilanciamento colore desiderato. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per migliorare la qualità visiva e aumentare l'accuratezza delle successive attività di analisi o visualizzazione nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Imposta il coefficiente gamma per i canali rosso, verde e blu.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Esegui la correzione gamma sull'immagine utilizzando coefficienti individuali per i canali rosso, verde e blu, consentendo regolazioni precise del bilanciamento colore e del contrasto. Integra questo metodo nel tuo pipeline di elaborazione delle immagini per ottenere un controllo preciso sulla resa dei colori e migliorare la fedeltà visiva nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementa la regolazione `brightness` per l'immagine, consentendo la modifica dei livelli di luminanza complessiva. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per migliorare la visibilità e la qualità visiva delle immagini nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Imposta il valore di luminosità. I valori accettati per la luminosità sono nell'intervallo [-255, 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Migliora il contrasto dell'istanza [Image](../../com.aspose.imaging/image), amplificando le differenze tra le aree chiare e scure. Integra questa funzionalità per migliorare la chiarezza visiva e la qualità complessiva dell'immagine nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Imposta il valore di contrasto. I valori accettati per il contrasto sono nell'intervallo [-100f, 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtra il contenuto all'interno del rettangolo specificato, applicando un filtro di elaborazione delle immagini designato per migliorare o modificare la regione selezionata. Integra questo metodo nel tuo flusso di lavoro di manipolazione delle immagini per ottenere miglioramenti o trasformazioni mirate nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Regola le dimensioni dell'immagine in base alle impostazioni specificate, consentendo un controllo preciso su dimensioni, rapporto d'aspetto e comportamento di ridimensionamento. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ottenere operazioni di ridimensionamento personalizzate, adattate ai requisiti specifici della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Riduci di 2 volte usando il ricampionamento adattivo.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Salva in PNG
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

