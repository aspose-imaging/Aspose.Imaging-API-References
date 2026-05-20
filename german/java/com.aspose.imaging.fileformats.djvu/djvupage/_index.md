---
title: "DjvuPage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Djvu-Seitenklasse"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Djvu-Seitenklasse
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | Tritt auf, wenn [page exported action]. |
| [PropertyChanged](#PropertyChanged) | Tritt auf, wenn ein Eigenschaftswert geändert wird. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getParentImage()](#getParentImage--) | Liefert das übergeordnete Bild, zu dem die Seite gehört |
| [getWidth()](#getWidth--) | Liefert die Breite der Seite |
| [getHeight()](#getHeight--) | Ermittelt die Höhe der Seite |
| [getImage()](#getImage--) | Liefert das Bild. |
| [getThumbnailImage()](#getThumbnailImage--) | Liest oder setzt das Miniaturbild für die Seite |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Liest oder setzt das Miniaturbild für die Seite |
| [getPageNumber()](#getPageNumber--) | Liefert die Seitenzahl. |
| [isColor()](#isColor--) | Liefert einen Wert, der angibt, ob diese Instanz farbig ist. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Liefert den Text für die Rechteckposition |
| [getForegroundImage()](#getForegroundImage--) | Liefert das Vordergrundbild für die Seite |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Liefert das Vordergrundbild für die Seite |
| [getTextImage()](#getTextImage--) | Liefert das Textbild. |
| [getTextImage(int subsample)](#getTextImage-int-) | Liefert das Textbild. |
| [getBackgroundImage()](#getBackgroundImage--) | Liefert das Hintergrundbild. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Extrahiert das Miniaturbild aus der Djvu‑Seite. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


Tritt auf, wenn [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Tritt auf, wenn ein Eigenschaftswert geändert wird.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

Wert: Die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Liefert das übergeordnete Bild, zu dem die Seite gehört

Wert: Das Dokument.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Liefert die Breite der Seite

Wert: Die Breite.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Höhe der Seite

Wert: Die Höhe.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Liefert das Bild.

Wert: Das Bild.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Liest oder setzt das Miniaturbild für die Seite

Wert: Das Miniaturbild.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Liest oder setzt das Miniaturbild für die Seite

Wert: Das Miniaturbild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Liefert die Seitenzahl.

Wert: Die Seitenzahl.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
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

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Seiten: 2
//Die aktive Seitennummer:    1
//Die erste Seitennummer:     1
//Die letzte Seitennummer:      2
//--------------------------------------------------
//Seitennummer:     1
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
//--------------------------------------------------
//Seitennummer:     2
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


Liefert einen Wert, der angibt, ob diese Instanz farbig ist.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Liefert den Text für die Rechteckposition

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Positionsrechteck. |

**Returns:**
java.lang.String - Text gefunden an der Position
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Liefert das Vordergrundbild für die Seite

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Liefert das Vordergrundbild für die Seite

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subsample | int | Die Unterabtastung. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Liefert das Textbild.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Liefert das Textbild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subsample | int | Die Unterabtastung. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Liefert das Hintergrundbild.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Extrahiert das Miniaturbild aus der Djvu‑Seite.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
