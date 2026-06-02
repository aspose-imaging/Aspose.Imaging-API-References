---
title: "EmfImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per il supporto del formato immagine vettoriale Enhanced Metafile Format EMF è uno strumento completo per l'elaborazione di immagini grafiche in modo indipendente dal dispositivo, preservando le loro proprietà originali."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

L'API per il supporto del formato immagine vettoriale Enhanced Metafile Format (EMF) è uno strumento completo per l'elaborazione di immagini grafiche in modo indipendente dal dispositivo, preservando le loro proprietà originali. Sviluppata per mantenere proporzioni, dimensioni, colori e altri attributi grafici, include il supporto al formato EMF Plus e funzionalità per ritagliare regioni, ridimensionare la tela e le immagini, ruotare, capovolgere, impostare le palette delle immagini, esportare e importare nel contesto dispositivo APS, comprimere e convertire EMF in altri formati, garantendo una manipolazione versatile e un'integrazione fluida delle immagini EMF in tutte le applicazioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfImage()](#EmfImage--) | Inizia a lavorare con le immagini EMF inizializzando una nuova istanza della classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Crea una nuova istanza della classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) specificando i parametri di larghezza e altezza. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeader()](#getHeader--) | Recupera il record dell'intestazione del metafile EMF con questa proprietà. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Modifica il record dell'intestazione del metafile EMF con questa proprietà. |
| [isCached()](#isCached--) | Accedi a un valore che indica se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di ulteriori letture dei dati. |
| [getRecords()](#getRecords--) | Recupera o modifica i record associati all'oggetto. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Modifica i record associati all'oggetto. |
| [getFileFormat()](#getFileFormat--) | Accedi al valore del formato file associato all'oggetto. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera il conteggio bit-per-pixel specifico per le immagini raster, poiché questo parametro non si applica alle immagini vettoriali. |
| [getWidthF()](#getWidthF--) | Accedi alla larghezza dell'immagine, fornendo informazioni essenziali per una resa e un'elaborazione precise. |
| [getHeightF()](#getHeightF--) | Recupera l'altezza dell'immagine, facilitando una resa accurata e regolazioni del layout. |
| [cacheData()](#cacheData--) | Metti nella cache i dati in modo efficiente e previeni il caricamento ridondante dalla sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) con questo metodo. |
| [getUsedFonts()](#getUsedFonts--) | Recupera l'elenco dei font utilizzati all'interno del metafile con questo metodo. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ridimensiona la tela con facilità usando questa funzione. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni originali dell'immagine. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Imposta la tavolozza dell'immagine. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Il testo verrà convertito in forme.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La dimensione della pagina.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Se esiste un emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Imposta il margine orizzontale
    rasterizationOptions.setBorderX(50);

    // Imposta il margine verticale
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


Inizia a lavorare con le immagini EMF inizializzando una nuova istanza della classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). Ideale per incorporare rapidamente le immagini EMF nei tuoi progetti con facilità ed efficienza.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Crea una nuova istanza della classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) specificando i parametri di larghezza e altezza. Questo costruttore semplifica il processo di inizializzazione delle immagini EMF con dimensioni specifiche, migliorando l'efficienza del tuo flusso di lavoro di sviluppo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza. |
| height | int | L'altezza. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Recupera il record dell'intestazione del metafile EMF con questa proprietà. Ideale per gestire i dati del metafile in modo efficiente all'interno della tua applicazione. Migliora il tuo flusso di lavoro con un accesso semplificato alle informazioni dell'intestazione del metafile.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Modifica il record dell'intestazione del metafile EMF con questa proprietà. Ideale per gestire i dati del metafile in modo efficiente all'interno della tua applicazione. Migliora il tuo flusso di lavoro con un accesso semplificato alle informazioni dell'intestazione del metafile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Accedi a un valore che indica se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di ulteriori letture dei dati. Aumenta l'efficienza determinando rapidamente se i dati nella cache sono disponibili per l'accesso immediato. Ottimizza il tuo flusso di lavoro con processi di recupero dati semplificati.

**Returns:**
boolean - `true` se i dati dell'oggetto sono nella cache; altrimenti, `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Recupera o modifica i record associati all'oggetto. Accedi e gestisci efficientemente la collezione di record per una migliore manipolazione e elaborazione dei dati. Ottimizza il tuo flusso di lavoro interagendo senza interruzioni con i record dell'oggetto.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Modifica i record associati all'oggetto. Accedi e gestisci efficientemente la collezione di record per una migliore manipolazione e elaborazione dei dati. Ottimizza il tuo flusso di lavoro interagendo senza interruzioni con i record dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | I record. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accedi al valore del formato file associato all'oggetto. Determina facilmente il formato del file associato all'oggetto per una elaborazione semplificata e controlli di compatibilità. Semplifica il tuo flusso di lavoro recuperando le informazioni sul formato file con facilità.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera il conteggio dei bit per pixel specifico per le immagini raster, poiché questo parametro non si applica alle immagini vettoriali. Determina rapidamente la profondità dei pixel delle immagini raster per un'analisi e manipolazione precise, garantendo una gestione accurata dei dati dell'immagine.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Accedi alla larghezza dell'immagine, fornendo informazioni essenziali per un rendering e una elaborazione precisi. Recupera rapidamente la larghezza dell'immagine per garantire compatibilità e un layout corretto all'interno di varie applicazioni e piattaforme.

**Returns:**
float - La larghezza dell'immagine in pixel.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Recupera l'altezza dell'immagine, facilitando un rendering accurato e regolazioni del layout. L'accesso alla proprietà altezza garantisce compatibilità e integrazione fluida su diverse piattaforme e applicazioni.

**Returns:**
float - L'altezza dell'immagine in pixel.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache i dati in modo efficiente e previeni il caricamento ridondante dal sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) con questo metodo. Migliora le prestazioni e semplifica l'accesso ai dati nella tua applicazione, ottimizzando l'utilizzo delle risorse per una maggiore reattività.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Memorizza nella cache i dati per caricare tutti i record.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // La chiave è un tipo di record, il valore è il numero di record di quel tipo nell'immagine WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Raccogli statistiche
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Stampa statistiche
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Allinea l'output con spazi
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//L'output potrebbe apparire così:
//Il numero totale di record: 1188
//Tipo di Record                              Conteggio
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Recupera l'elenco dei font utilizzati all'interno del metafile con questo metodo. Ottieni informazioni sull'uso dei font, facilitando una gestione efficiente e l'ottimizzazione delle risorse dei font per un rendering e una fedeltà di visualizzazione migliorati.

**Returns:**
java.lang.String[] - L'elenco dei caratteri
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Ridimensiona la tela con facilità usando questa funzione. Perfetta per regolare le dimensioni complessive dell'immagine senza alterarne il contenuto. Migliora la presentazione e prepara le immagini per varie dimensioni di visualizzazione senza sforzo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il nuovo rettangolo. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni originali dell'immagine.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Imposta la tavolozza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

