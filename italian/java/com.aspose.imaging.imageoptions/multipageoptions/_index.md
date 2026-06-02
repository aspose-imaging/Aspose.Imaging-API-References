---
title: "MultiPageOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe base per i formati supportati a più pagine"
type: docs
weight: 30
url: /it/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Classe base per i formati supportati a più pagine
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | Inizializza una nuova istanza della classe `MultiPageOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPages()](#getPages--) | Ottiene o imposta le pagine. |
| [setPages(int[] value)](#setPages-int---) | Ottiene o imposta le pagine. |
| [getPageTitles()](#getPageTitles--) | Ottiene o imposta i titoli delle pagine. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Ottiene o imposta i titoli delle pagine. |
| [getTimeInterval()](#getTimeInterval--) | Ottiene l'intervallo di tempo. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Imposta l'intervallo di tempo. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Ottiene le opzioni di rasterizzazione della pagina. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Imposta le opzioni di rasterizzazione della pagina. |
| [getExportArea()](#getExportArea--) | Ottiene o imposta l'area di esportazione. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Ottiene o imposta l'area di esportazione. |
| [getMode()](#getMode--) | Ottiene o imposta la modalità. |
| [setMode(int value)](#setMode-int-) | Ottiene o imposta la modalità. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Ottiene o imposta i nomi dei livelli di output(Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Ottiene o imposta i nomi dei livelli di output(Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd) |
| [getMergeLayers()](#getMergeLayers--) | Ottiene un valore che indica se [merge layers]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Imposta un valore che indica se [merge layers]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Inizializza le pagine dall'array di intervalli |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagine | int[] | Le pagine. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagine | int[] | L'array di pagine. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di esportazione. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageTitles | java.lang.String[] | I titoli delle pagine. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageTitles | java.lang.String[] | I titoli delle pagine. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di esportazione. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Il `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Il `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di esportazione. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Il `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Il `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di esportazione. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | int | L'indice della pagina. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Inizializza una nuova istanza della classe `MultiPageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | int | L'indice della pagina. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di esportazione. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Ottiene o imposta le pagine.

Valore: Le pagine.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Ottiene o imposta le pagine.

Valore: Le pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Nota che se l'immagine è a colori, verrà automaticamente convertita in formato B/N secondo l'opzione seguente:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Per impostazione predefinita, tutte le pagine verranno salvate nel TIFF di output, ma è possibile specificare esplicitamente il set desiderato di pagine.
        // Solo la prima e la seconda pagina verranno esportate.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Imposta i titoli delle pagine.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Salva in TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Ottiene o imposta i titoli delle pagine.

Valore: I titoli delle pagine.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Ottiene o imposta i titoli delle pagine.

Valore: I titoli delle pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Nota che se l'immagine è a colori, verrà automaticamente convertita in formato B/N secondo l'opzione seguente:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Per impostazione predefinita, tutte le pagine verranno salvate nel TIFF di output, ma è possibile specificare esplicitamente il set desiderato di pagine.
        // Solo la prima e la seconda pagina verranno esportate.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Imposta i titoli delle pagine.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Salva in TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


Ottiene l'intervallo di tempo.

Valore: L'intervallo di tempo.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Imposta l'intervallo di tempo.

Valore: L'intervallo di tempo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | l'intervallo di tempo. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Ottiene le opzioni di rasterizzazione della pagina.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - le opzioni di rasterizzazione della pagina.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Imposta le opzioni di rasterizzazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | le opzioni di rasterizzazione della pagina. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Ottiene o imposta l'area di esportazione.

Valore: L'area di esportazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Ottiene o imposta l'area di esportazione.

Valore: L'area di esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Ottiene o imposta la modalità.

Valore: La modalità.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Ottiene o imposta la modalità.

Valore: La modalità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Ottiene o imposta i nomi dei livelli di output(Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd)

Valore: I nomi dei layer di output.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Ottiene o imposta i nomi dei livelli di output(Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd)

Valore: I nomi dei layer di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Ottiene un valore che indica se [merge layers].

Valore: `true` se [merge layers]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [merge layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Imposta un valore che indica se [merge layers].

Valore: `true` se [merge layers]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [merge layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Inizializza le pagine dall'array di intervalli

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Gli intervalli. |

