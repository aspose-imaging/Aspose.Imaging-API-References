---
title: "MultiPageOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe de base pour les formats prenant en charge plusieurs pages"
type: docs
weight: 30
url: /fr/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Classe de base pour les formats prenant en charge plusieurs pages
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe `MultiPageOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPages()](#getPages--) | Obtient ou définit les pages. |
| [setPages(int[] value)](#setPages-int---) | Obtient ou définit les pages. |
| [getPageTitles()](#getPageTitles--) | Obtient ou définit les titres de page. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Obtient ou définit les titres de page. |
| [getTimeInterval()](#getTimeInterval--) | Obtient l'intervalle de temps. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Définit l'intervalle de temps. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Obtient les options de rasterisation de la page. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Définit les options de rasterisation de la page. |
| [getExportArea()](#getExportArea--) | Obtient ou définit la zone d'exportation. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Obtient ou définit la zone d'exportation. |
| [getMode()](#getMode--) | Obtient ou définit le mode. |
| [setMode(int value)](#setMode-int-) | Obtient ou définit le mode. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour le PSD) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour le PSD) |
| [getMergeLayers()](#getMergeLayers--) | Obtient une valeur indiquant si [merge layers]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Définit une valeur indiquant si [merge layers]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Initialise les pages à partir du tableau de plages |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pages | int[] | Les pages. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pages | int[] | Le tableau de pages. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | La zone d'exportation. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Les titres de page. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Les titres de page. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | La zone d'exportation. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Le `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Le `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | La zone d'exportation. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Le `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Le `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | La zone d'exportation. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | int | L'index de page. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe `MultiPageOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | int | L'index de page. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | La zone d'exportation. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Obtient ou définit les pages.

Valeur: Les pages.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Obtient ou définit les pages.

Valeur: Les pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Notez que si l'image est colorée, elle sera automatiquement convertie au format N/B selon l'option ci‑dessous :
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Par défaut, toutes les pages seront enregistrées dans le TIFF de sortie, mais l'ensemble de pages souhaité peut être spécifié explicitement.
        // Seules la première et la deuxième page seront exportées.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Définir les titres de page.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Enregistrer au format TIFF
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


Obtient ou définit les titres de page.

Valeur: Les titres de page.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Obtient ou définit les titres de page.

Valeur: Les titres de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Notez que si l'image est colorée, elle sera automatiquement convertie au format N/B selon l'option ci‑dessous :
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Par défaut, toutes les pages seront enregistrées dans le TIFF de sortie, mais l'ensemble de pages souhaité peut être spécifié explicitement.
        // Seules la première et la deuxième page seront exportées.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Définir les titres de page.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Enregistrer au format TIFF
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


Obtient l'intervalle de temps.

Valeur: L'intervalle de temps.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Définit l'intervalle de temps.

Valeur: L'intervalle de temps.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | l'intervalle de temps. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Obtient les options de rasterisation de la page.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - les options de rastérisation de page.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Définit les options de rasterisation de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | les options de rastérisation de page. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Obtient ou définit la zone d'exportation.

Valeur: La zone d'exportation.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Obtient ou définit la zone d'exportation.

Valeur: La zone d'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Obtient ou définit le mode.

Valeur: Le mode.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Obtient ou définit le mode.

Valeur: Le mode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour le PSD)

Valeur: Les noms des calques de sortie.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour le PSD)

Valeur: Les noms des calques de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Obtient une valeur indiquant si [merge layers].

Valeur: `true` si [merge layers] ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si [merge layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Définit une valeur indiquant si [merge layers].

Valeur: `true` si [merge layers] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [merge layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Initialise les pages à partir du tableau de plages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Les plages. |

