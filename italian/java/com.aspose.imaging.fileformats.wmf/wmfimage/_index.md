---
title: "WmfImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola le immagini Microsoft Windows Metafile WMF con la nostra API gestendo senza problemi sia i dati vettoriali che bitmap memorizzati in record di lunghezza variabile."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Manipola le immagini Microsoft Windows Metafile (WMF) con la nostra API, gestendo senza problemi sia i dati vettoriali che bitmap memorizzati in record di lunghezza variabile. Ridimensiona, ruota e capovolgi le immagini con facilità impostando palette di immagini personalizzate. Converti i file WMF in formati WMZ compressi o salvali in formati di immagine raster per un utilizzo versatile su piattaforme e applicazioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfImage()](#WmfImage--) | Crea una nuova istanza della classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), inizializzandola per ulteriori manipolazioni e l'elaborazione dei dati immagine Windows Metafile (WMF). |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Istanzia una nuova istanza della classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) con parametri di larghezza e altezza personalizzabili, facilitando la creazione di immagini WMF vuote su misura per dimensioni specifiche. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isCached()](#isCached--) | Recupera un valore booleano che indica se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di ulteriori operazioni di lettura dei dati. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera il conteggio dei bit per pixel dell'immagine, indicando il livello di profondità o granularità del colore. |
| [getWidthF()](#getWidthF--) | Accedi alla larghezza dell'immagine, indicando il numero di pixel lungo l'asse orizzontale. |
| [getHeightF()](#getHeightF--) | Accedi all'altezza dell'immagine, rappresentando il numero di pixel lungo l'asse verticale. |
| [getInch()](#getInch--) | Accedi o modifica la proprietà inch, che rappresenta un'unità di misura tipicamente usata per specificare le dimensioni fisiche in contesti di stampa o visualizzazione. |
| [setInch(int value)](#setInch-int-) | Accedi o modifica la proprietà inch, che rappresenta un'unità di misura tipicamente usata per specificare le dimensioni fisiche in contesti di stampa o visualizzazione. |
| [getFileFormat()](#getFileFormat--) | Accedi al valore del formato file associato all'immagine, fornendo informazioni sul formato in cui l'immagine è memorizzata. |
| [getFrameBounds()](#getFrameBounds--) | Accedi ai limiti del fotogramma, indicando la sua posizione e le dimensioni all'interno dell'immagine. |
| [cacheData()](#cacheData--) | Cache i dati in modo efficiente, eliminando la necessità di ulteriori caricamenti dal sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Applica una palette specificata all'immagine, consentendo la personalizzazione della rappresentazione dei colori. |
| [getUsedFonts()](#getUsedFonts--) | Recupera l'elenco dei font utilizzati nel metafile, fornendo una panoramica delle risorse di font impiegate nell'immagine. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ridimensiona la tela dell'immagine, regolando le sue dimensioni mantenendo intatto il contenuto dell'immagine. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Incorpora l'oggetto record specificato nell'immagine, arricchendo il suo contenuto con dati o metadati aggiuntivi. |
| [getPostScript()](#getPostScript--) | Accedi ai dati PostScript associati all'immagine, fornendo informazioni dettagliate sulla sua struttura o contenuto. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni originali dell'immagine. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Il testo verrà convertito in forme.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La dimensione della pagina.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Se esiste un emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
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


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Crea una nuova istanza della classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), inizializzandola per ulteriori manipolazioni e l'elaborazione dei dati immagine Windows Metafile (WMF). Questo costruttore fornisce un oggetto di base per lavorare con le immagini WMF, consentendo un'integrazione fluida delle capacità di gestione delle immagini WMF nella funzionalità della tua applicazione.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Istanzia una nuova istanza della classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) con parametri di larghezza e altezza personalizzabili, facilitando la creazione di immagini WMF vuote su misura per dimensioni specifiche. Utilizza questo costruttore per generare dinamicamente immagini WMF con dimensioni precise, consentendo una creazione e manipolazione flessibile delle immagini nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza. |
| height | int | L'altezza. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Recupera un valore booleano che indica se i dati dell'oggetto sono attualmente memorizzati nella cache, eliminando la necessità di ulteriori operazioni di lettura dei dati. Utilizza questa proprietà per ottimizzare le prestazioni determinando se i dati dell'oggetto sono prontamente disponibili senza la necessità di costosi processi di recupero dei dati nella tua applicazione.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera il conteggio dei bit per pixel dell'immagine, indicando il livello di profondità o granularità del colore. Utilizza questa proprietà per determinare la rappresentazione cromatica e la precisione dell'immagine, facilitando i controlli di compatibilità e l'elaborazione correlata al colore nella tua applicazione.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Accedi alla larghezza dell'immagine, indicando il numero di pixel lungo l'asse orizzontale. Utilizza questa proprietà per determinare le dimensioni spaziali e il rapporto d'aspetto dell'immagine, consentendo regolazioni precise del layout e del rendering nella tua applicazione.

**Returns:**
float - La larghezza dell'immagine in pixel.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Accedi all'altezza dell'immagine, rappresentando il numero di pixel lungo l'asse verticale. Utilizza questa proprietà per determinare le dimensioni spaziali e il rapporto d'aspetto dell'immagine, consentendo regolazioni accurate del layout e del rendering nella tua applicazione.

**Returns:**
float - L'altezza dell'immagine in pixel.
### getInch() {#getInch--}
```
public int getInch()
```


Accedi o modifica la proprietà inch, che rappresenta un'unità di misura tipicamente usata per specificare le dimensioni fisiche in contesti di stampa o visualizzazione. Utilizza questa proprietà per stabilire o recuperare i valori in pollici associati all'immagine, facilitando una rappresentazione accurata delle dimensioni fisiche nella tua applicazione.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Accedi o modifica la proprietà inch, che rappresenta un'unità di misura tipicamente usata per specificare le dimensioni fisiche in contesti di stampa o visualizzazione. Utilizza questa proprietà per stabilire o recuperare i valori in pollici associati all'immagine, facilitando una rappresentazione accurata delle dimensioni fisiche nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accedi al valore del formato file associato all'immagine, fornendo informazioni sul formato in cui l'immagine è memorizzata. Utilizza questa proprietà per determinare il formato file dell'immagine, facilitando i controlli di compatibilità e l'elaborazione specifica del formato nella tua applicazione.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Accedi ai limiti del fotogramma, indicando la sua posizione e le sue dimensioni all'interno dell'immagine. Utilizza questa proprietà per recuperare informazioni dettagliate sulla posizione spaziale del fotogramma, consentendo una manipolazione e un rendering precisi nella tua applicazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Memorizza nella cache i dati in modo efficiente, eliminando la necessità di ulteriori caricamenti dal sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Utilizza questo metodo per ottimizzare le prestazioni e ridurre al minimo l'uso delle risorse nella tua applicazione memorizzando e accedendo alla cache locale dei dati.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Memorizza nella cache i dati per caricare tutti i record.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // La chiave è un tipo di record, il valore è il numero di record di quel tipo nell'immagine WMF.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // Raccogli statistiche
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
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
    wmfImage.dispose();
}

//L'output potrebbe apparire così:
//Il numero totale di record: 613
//Tipo di Record                              Conteggio
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Applica una palette specificata all'immagine, consentendo la personalizzazione della rappresentazione dei colori. Utilizza questo metodo per migliorare il rendering visivo e ottenere effetti di colore specifici all'interno della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Recupera l'elenco dei caratteri utilizzati nel metafile, fornendo informazioni sulle risorse tipografiche impiegate nell'immagine. Utilizza questo metodo per analizzare l'uso dei caratteri e garantire la disponibilità dei caratteri per il rendering o per ulteriori elaborazioni all'interno della tua applicazione.

**Returns:**
java.lang.String[] - L'elenco dei caratteri
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Ridimensiona la tela dell'immagine, regolando le sue dimensioni mantenendo intatto il contenuto dell'immagine. Utilizza questo metodo per modificare le dimensioni della tela senza alterare il contenuto, facilitando le regolazioni del layout e le modifiche alla composizione all'interno della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il nuovo rettangolo. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Incorpora l'oggetto record specificato nell'immagine, arricchendo il suo contenuto con dati aggiuntivi o metadati. Utilizza questo metodo per integrare senza soluzione di continuità gli oggetti record nell'immagine, facilitando l'archiviazione e l'organizzazione completa dei dati all'interno della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | Il record. |

**Returns:**
int - Numero di record.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Accedi ai dati PostScript associati all'immagine, fornendo informazioni dettagliate sulla sua struttura o sul suo contenuto. Utilizza questo metodo per recuperare i dati PostScript per ulteriori analisi o elaborazioni all'interno della tua applicazione, abilitando funzionalità avanzate relative al rendering o alla manipolazione di PostScript.

**Returns:**
java.lang.String - Il PostScript
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni originali dell'immagine.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
