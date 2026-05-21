---
title: "MultiPageOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Basklass för format som stöder flera sidor."
type: docs
weight: 30
url: /sv/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Basklass för format som stöder flera sidor.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initierar en ny instans av klassen `MultiPageOptions`. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen `MultiPageOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPages()](#getPages--) | Hämtar eller anger sidorna. |
| [setPages(int[] value)](#setPages-int---) | Hämtar eller anger sidorna. |
| [getPageTitles()](#getPageTitles--) | Hämtar eller anger sidtitlarna. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Hämtar eller anger sidtitlarna. |
| [getTimeInterval()](#getTimeInterval--) | Hämtar tidsintervallet. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Ställer in tidsintervallet. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Hämtar sidans rasteriseringsalternativ. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Ställer in sidans rasteriseringsalternativ. |
| [getExportArea()](#getExportArea--) | Hämtar eller anger exportområdet. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Hämtar eller anger exportområdet. |
| [getMode()](#getMode--) | Hämtar eller anger läget. |
| [setMode(int value)](#setMode-int-) | Hämtar eller anger läget. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stöder namngivning av lager, till exempel för Psd) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stöder namngivning av lager, till exempel för Psd) |
| [getMergeLayers()](#getMergeLayers--) | Hämtar ett värde som indikerar om [merge layers]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Ställer in ett värde som indikerar om [merge layers]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Initierar sidorna från intervallarrayen |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initierar en ny instans av klassen `MultiPageOptions`.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sidor | int[] | Sidorna. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sidor | int[] | Arrayen av sidor. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Exportområdet. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sidtitlarna. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sidtitlarna. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Exportområdet. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Den `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Den `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Exportområdet. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Den `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Den `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Exportområdet. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | int | Sidindexet. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initierar en ny instans av klassen `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | int | Sidindexet. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Exportområdet. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Hämtar eller anger sidorna.

Värde: Sidorna.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Hämtar eller anger sidorna.

Värde: Sidorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Observera att om bilden är färgrik, kommer den automatiskt att konverteras till S/V-format enligt alternativet nedan:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Som standard kommer alla sidor att sparas till utdata-TIFF, men den önskade uppsättningen av sidor kan specificeras explicit.
        // Endast den första och den andra sidan kommer att exporteras.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Ange sidtitlar.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Spara till TIFF
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


Hämtar eller anger sidtitlarna.

Värde: Sidtitlarna.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Hämtar eller anger sidtitlarna.

Värde: Sidtitlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Observera att om bilden är färgrik, kommer den automatiskt att konverteras till S/V-format enligt alternativet nedan:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Som standard kommer alla sidor att sparas till utdata-TIFF, men den önskade uppsättningen av sidor kan specificeras explicit.
        // Endast den första och den andra sidan kommer att exporteras.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Ange sidtitlar.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Spara till TIFF
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


Hämtar tidsintervallet.

Värde: Tidsintervallet.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Ställer in tidsintervallet.

Värde: Tidsintervallet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | tidsintervallet. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Hämtar sidans rasteriseringsalternativ.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - sidrasteriseringsalternativen.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Ställer in sidans rasteriseringsalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | sidrasteriseringsalternativen. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Hämtar eller anger exportområdet.

Värde: Exportområdet.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Hämtar eller anger exportområdet.

Värde: Exportområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Hämtar eller anger läget.

Värde: Läge.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Hämtar eller anger läget.

Värde: Läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stöder namngivning av lager, till exempel för Psd)

Värde: Namnen på utdataskikten.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stöder namngivning av lager, till exempel för Psd)

Värde: Namnen på utdataskikten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Hämtar ett värde som indikerar om [merge layers].

Värde: `true` om [merge layers]; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om [merge layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Ställer in ett värde som indikerar om [merge layers].

Värde: `true` om [merge layers]; annars, `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [merge layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Initierar sidorna från intervallarrayen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Intervallen. |

