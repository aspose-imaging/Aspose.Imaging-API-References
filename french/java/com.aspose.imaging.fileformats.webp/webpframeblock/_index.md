---
title: "WebPFrameBlock"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente le registre des ouvreurs de blocs webp."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Représente le registre des ouvreurs de blocs webp.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Initialise une nouvelle instance de la classe `WebPFrameBlock`. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Initialise une nouvelle instance de la classe `WebPFrameBlock`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [hasAlpha()](#hasAlpha--) | Obtient une valeur indiquant si cette instance possède de l'alpha. |
| [getDuration()](#getDuration--) | Obtient ou définit la durée de la trame. |
| [setDuration(short value)](#setDuration-short-) | Obtient ou définit la durée de la trame. |
| [getLeft()](#getLeft--) | Obtient ou définit la position gauche de la trame. |
| [setLeft(short value)](#setLeft-short-) | Obtient ou définit la position gauche de la trame. |
| [getTop()](#getTop--) | Obtient ou définit la position supérieure de la trame. |
| [setTop(short value)](#setTop-short-) | Obtient ou définit la position supérieure de la trame. |
| [getFrameTime()](#getFrameTime--) | Obtient la durée de la trame. |
| [getFrameTop()](#getFrameTop--) | Obtient le décalage supérieur de la trame. |
| [getFrameLeft()](#getFrameLeft--) | Obtient le décalage gauche de la trame. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtient la méthode de disposition. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Définit la méthode de disposition. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Obtient la valeur indiquant si la trame actuelle est mélangée avec les valeurs alpha de la trame précédente. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Définit la valeur indiquant si la trame actuelle est mélangée avec les valeurs alpha de la trame précédente. |
| [getFullFrame()](#getFullFrame--) | Obtient la trame complète. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Initialise une nouvelle instance de la classe `WebPFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Initialise une nouvelle instance de la classe `WebPFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

**Returns:**
int - La hauteur de l'image.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

**Returns:**
int - La largeur de l'image.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient une valeur indiquant si cette instance possède de l'alpha.

**Returns:**
boolean - `true` si cette instance possède un canal alpha ; sinon, `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Si la trame TIFF active possède un canal alpha, alors l'ensemble de l'image TIFF est considéré comme ayant un canal alpha.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// ImageFile=c:\\temp\\sample.webp, FileFormat=RgbIndexed1Bpp, canaux utilisés : 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, canaux utilisés : 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


Obtient ou définit la durée de la trame.

**Returns:**
short - La durée.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Obtient ou définit la durée de la trame.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | La durée. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Obtient ou définit la position gauche de la trame.

**Returns:**
short - La gauche.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Obtient ou définit la position gauche de la trame.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | La gauche. |

### getTop() {#getTop--}
```
public short getTop()
```


Obtient ou définit la position supérieure de la trame.

**Returns:**
short - Le haut.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Obtient ou définit la position supérieure de la trame.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | Le haut. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Obtient la durée de la trame.

**Returns:**
int - la durée de la trame.
### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Obtient le décalage supérieur de la trame.

**Returns:**
int - le décalage supérieur de la trame.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Obtient le décalage gauche de la trame.

**Returns:**
int - le décalage gauche de la trame.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Obtient la méthode de disposition.

**Returns:**
int - la méthode de disposition.
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


Définit la méthode de disposition.

Valeur : la méthode de disposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la méthode de disposition. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Obtient la valeur indiquant si la trame actuelle est mélangée avec les valeurs alpha de la trame précédente.

Valeur : `` si cette trame utilise le mélange alpha ; sinon, ``.

**Returns:**
boolean - la valeur indiquant si la trame actuelle est mélangée avec les valeurs alpha de la trame précédente.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Définit la valeur indiquant si la trame actuelle est mélangée avec les valeurs alpha de la trame précédente.

Valeur : `` si cette trame utilise le mélange alpha ; sinon, ``.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | la valeur indiquant si la trame actuelle est mélangée avec les valeurs alpha de la trame précédente. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Obtient la trame complète.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
