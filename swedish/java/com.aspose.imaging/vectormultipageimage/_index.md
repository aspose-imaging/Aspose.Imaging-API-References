---
title: "VectorMultipageImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Vektor-multipagesbild"
type: docs
weight: 118
url: /sv/java/com.aspose.imaging/vectormultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class VectorMultipageImage extends VectorImage implements IMultipageImage
```

Vektor-multipagesbild
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VectorMultipageImage()](#VectorMultipageImage--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getDefaultPage()](#getDefaultPage--) | Hämtar standardsidan. |
| [getPageExportingAction()](#getPageExportingAction--) | Hämtar sidexportåtgärden. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Ställer in sidexportåtgärden. |
| [getMetadata()](#getMetadata--) | Hämtar bildmetadata. |
| [cacheData()](#cacheData--) | Cacherar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär den angivna rektangeln. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på bilden. |
| [rotate(float angle)](#rotate-float-) | Rotera bilden kring centrum. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar storlek på bilden. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roterar, vänder eller roterar och vänder bilden. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Tar bort bakgrunden. |
| [removeBackground()](#removeBackground--) | Tar bort bakgrunden. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Ställer in bildpaletten. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Hämtar de inbäddade bilderna. |
### VectorMultipageImage() {#VectorMultipageImage--}
```
public VectorMultipageImage()
```


### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.

Värde: `true` om objektets data är cachade; annars `false`.

**Returns:**
boolean - ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

Värde: Bildens bitar per pixel-antal.

**Returns:**
int - bildens bitar per pixel-antal.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

Värde: Bildens bredd.

**Returns:**
int - bildens bredd.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

Värde: Bildens höjd.

**Returns:**
int - bildens höjd.
### getDefaultPage() {#getDefaultPage--}
```
public abstract Image getDefaultPage()
```


Hämtar standardsidan.

Värde: Standardsidan.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Hämtar sidexportåtgärden. Observera att inställning av denna metod automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas.

Värde: Sidexportåtgärden.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Ställer in sidexportåtgärden. Observera att inställning av denna metod automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas.

Värde: Sidexportåtgärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | sidexportåtgärden. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Hämtar bildmetadata.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cacherar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotera bilden kring centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Typ av rotation och spegling. |

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Tar bort bakgrunden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Inställningarna. |

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


Tar bort bakgrunden.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Ställer in bildpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Hämtar de inbäddade bilderna.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - Array av bilder
