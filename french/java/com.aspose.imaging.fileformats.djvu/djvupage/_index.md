---
title: "DjvuPage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe de page Djvu"
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Classe de page Djvu
## Champs

| Champ | Description |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | Se produit lorsque [page exported action]. |
| [PropertyChanged](#PropertyChanged) | Se produit lorsqu'une valeur de propriété change. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getParentImage()](#getParentImage--) | Obtient l'image parente à laquelle la page appartient |
| [getWidth()](#getWidth--) | Obtient la largeur de la page |
| [getHeight()](#getHeight--) | Obtient la hauteur de la page |
| [getImage()](#getImage--) | Obtient l'image. |
| [getThumbnailImage()](#getThumbnailImage--) | Obtient ou définit l'image miniature pour la page |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Obtient ou définit l'image miniature pour la page |
| [getPageNumber()](#getPageNumber--) | Obtient le numéro de page. |
| [isColor()](#isColor--) | Obtient une valeur indiquant si cette instance est en couleur. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Obtient le texte pour l'emplacement du rectangle |
| [getForegroundImage()](#getForegroundImage--) | Obtient l'image de premier plan pour la page |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Obtient l'image de premier plan pour la page |
| [getTextImage()](#getTextImage--) | Obtient l'image du texte. |
| [getTextImage(int subsample)](#getTextImage-int-) | Obtient l'image du texte. |
| [getBackgroundImage()](#getBackgroundImage--) | Obtient l'image d'arrière-plan. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Extrait l'image miniature de la page Djvu. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


Se produit lorsque [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Se produit lorsqu'une valeur de propriété change.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

Valeur : le nombre de bits par pixel de l'image.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Obtient l'image parente à laquelle la page appartient

Valeur: le document.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de la page

Valeur: la largeur.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de la page

Valeur: la hauteur.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Obtient l'image.

Valeur : l'image.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Obtient ou définit l'image miniature pour la page

Valeur: l'image miniature.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Obtient ou définit l'image miniature pour la page

Valeur: l'image miniature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Obtient le numéro de page.

Valeur : le numéro de page.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
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

//La sortie peut ressembler à ceci :
//Le nombre total de pages : 2
//Le numéro de page actif :    1
//Le numéro de la première page :     1
//Le numéro de la dernière page :      2
//--------------------------------------------------
//Numéro de page :     1
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
//--------------------------------------------------
//Numéro de page :     2
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtient une valeur indiquant si cette instance est en couleur.

Valeur : `true` si cette instance est en couleur ; sinon, `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Obtient le texte pour l'emplacement du rectangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle d'emplacement. |

**Returns:**
java.lang.String - Texte trouvé à l'emplacement
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Obtient l'image de premier plan pour la page

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Obtient l'image de premier plan pour la page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sous-échantillonnage | int | Le sous-échantillonnage. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Obtient l'image du texte.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Obtient l'image du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sous-échantillonnage | int | Le sous-échantillonnage. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Obtient l'image d'arrière-plan.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Extrait l'image miniature de la page Djvu.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
