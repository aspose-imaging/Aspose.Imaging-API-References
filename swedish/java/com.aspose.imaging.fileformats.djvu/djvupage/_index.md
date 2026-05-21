---
title: "DjvuPage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Djvu-sidklass"
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Djvu-sidklass
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | Uppstår när [page exported action]. |
| [PropertyChanged](#PropertyChanged) | Uppstår när ett egenskapsvärde ändras. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getParentImage()](#getParentImage--) | Hämtar föräldrabilden som sidan tillhör |
| [getWidth()](#getWidth--) | Hämtar sidans bredd |
| [getHeight()](#getHeight--) | Hämtar sidans höjd |
| [getImage()](#getImage--) | Hämtar bilden. |
| [getThumbnailImage()](#getThumbnailImage--) | Hämtar eller anger miniatyrbilden för sidan |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Hämtar eller anger miniatyrbilden för sidan |
| [getPageNumber()](#getPageNumber--) | Hämtar sidnumret. |
| [isColor()](#isColor--) | Hämtar ett värde som indikerar om detta objekt är färg. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Hämtar texten för rektangelns position |
| [getForegroundImage()](#getForegroundImage--) | Hämtar förgrundsbilden för sidan |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Hämtar förgrundsbilden för sidan |
| [getTextImage()](#getTextImage--) | Hämtar textbilden. |
| [getTextImage(int subsample)](#getTextImage-int-) | Hämtar textbilden. |
| [getBackgroundImage()](#getBackgroundImage--) | Hämtar bakgrundsbilden. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Extraherar miniatyrbilden från Djvu-sidan. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


Uppstår när [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Uppstår när ett egenskapsvärde ändras.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

Värde: Bildens bitar per pixel-antal.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Hämtar föräldrabilden som sidan tillhör

Värde: Dokumentet.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar sidans bredd

Värde: Bredden.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar sidans höjd

Värde: Höjden.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Hämtar bilden.

Värde: Bilden.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Hämtar eller anger miniatyrbilden för sidan

Värde: Miniatyrbilden.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Hämtar eller anger miniatyrbilden för sidan

Värde: Miniatyrbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Hämtar sidnumret.

Värde: Sidnumret.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
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

//Utdata kan se ut så här:
//Det totala antalet sidor: 2
//Det aktiva sidnumret:    1
//Det första sidnumret:     1
//Det sista sidnumret:      2
//--------------------------------------------------
//Sidnummer:     1
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
//--------------------------------------------------
//Sidnummer:     2
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


Hämtar ett värde som indikerar om detta objekt är färg.

Värde: `true` om denna instans är färg; annars `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Hämtar texten för rektangelns position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Placeringsrektangeln. |

**Returns:**
java.lang.String - Text hittad på plats
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Hämtar förgrundsbilden för sidan

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Hämtar förgrundsbilden för sidan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subsample | int | Subsamplet. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Hämtar textbilden.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Hämtar textbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subsample | int | Subsamplet. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Hämtar bakgrundsbilden.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Extraherar miniatyrbilden från Djvu-sidan.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
