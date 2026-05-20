---
title: "VectorMultipageImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Vektor‑Mehrseitige Bild"
type: docs
weight: 118
url: /de/java/com.aspose.imaging/vectormultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class VectorMultipageImage extends VectorImage implements IMultipageImage
```

Das Vektor‑Mehrseitige Bild
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VectorMultipageImage()](#VectorMultipageImage--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isCached()](#isCached--) | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getDefaultPage()](#getDefaultPage--) | Ermittelt die Standardseite. |
| [getPageExportingAction()](#getPageExportingAction--) | Ermittelt die Seitenexportaktion. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Legt die Seitenexportaktion fest. |
| [getMetadata()](#getMetadata--) | Ermittelt die Metadaten des Bildes. |
| [cacheData()](#cacheData--) | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) durchgeführt werden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet das angegebene Rechteck zu. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändert die Größe des Bildes. |
| [rotate(float angle)](#rotate-float-) | Bild um die Mitte drehen. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändert die Größe des Bildes. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Entfernt den Hintergrund. |
| [removeBackground()](#removeBackground--) | Entfernt den Hintergrund. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Legt die Bildpalette fest. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Ermittelt die eingebetteten Bilder. |
### VectorMultipageImage() {#VectorMultipageImage--}
```
public VectorMultipageImage()
```


### isCached() {#isCached--}
```
public boolean isCached()
```


Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.

Wert: `true`, wenn die Daten des Objekts zwischengespeichert sind; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

Wert: Die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – die Bit‑Pro‑Pixel‑Anzahl des Bildes.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

Wert: Die Bildbreite.

**Returns:**
int – die Bildbreite.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

Wert: Die Bildhöhe.

**Returns:**
int – die Bildhöhe.
### getDefaultPage() {#getDefaultPage--}
```
public abstract Image getDefaultPage()
```


Ermittelt die Standardseite.

Wert: Die Standardseite.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Ermittelt die Seitenexportaktion. Bitte beachten Sie, dass das Setzen dieser Methode automatisch die Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt.

Wert: Die Seitenexportaktion.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Legt die Seitenexportaktion fest. Bitte beachten Sie, dass das Setzen dieser Methode automatisch die Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt.

Wert: Die Seitenexportaktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | die Seitenexportaktion. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Ermittelt die Metadaten des Bildes.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) durchgeführt werden.

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Schneidet das angegebene Rechteck zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändert die Größe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Bild um die Mitte drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändert die Größe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Typ der Drehung und Spiegelung. |

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Entfernt den Hintergrund.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Die Einstellungen. |

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


Entfernt den Hintergrund.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Legt die Bildpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Ermittelt die eingebetteten Bilder.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - Array von Bildern
