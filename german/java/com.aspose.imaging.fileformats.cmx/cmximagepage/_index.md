---
title: "CmxImagePage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Bild der CMX-Seite"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

Das Bild der CMX-Seite
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Initialisiert eine neue Instanz der Klasse [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Initialisiert eine neue Instanz der Klasse [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | Ruft die CMX-Seite ab. |
| [getFileFormat()](#getFileFormat--) | Ruft einen Wert des Dateiformats ab |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [isCached()](#isCached--) | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [getWidthF()](#getWidthF--) | Ermittelt die Objektbreite in Zoll. |
| [getHeightF()](#getHeightF--) | Ermittelt die Objekthöhe in Zoll. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ruft die Standardoptionen ab. |
| [cacheData()](#cacheData--) | Cache kann nicht verwendet werden. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Legt die Bildpalette fest. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Initialisiert eine neue Instanz der Klasse [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | Die CMX-Seite. |
| container | [Image](../../com.aspose.imaging/image) | Der Container. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Initialisiert eine neue Instanz der Klasse [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | Die CMX-Seite. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Ruft die CMX-Seite ab.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ruft einen Wert des Dateiformats ab

**Returns:**
long – ein Wert des Dateiformats
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – die Bit‑Pro‑Pixel‑Anzahl des Bildes.
### isCached() {#isCached--}
```
public boolean isCached()
```


Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.

Wert: `true`, wenn die Daten des Objekts zwischengespeichert sind; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Ermittelt die Objektbreite in Zoll.

**Returns:**
float - die Objektbreite, in Zoll.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Ermittelt die Objekthöhe in Zoll.

**Returns:**
float - die Objekthöhe, in Zoll.
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
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Ruft die Standardoptionen ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | java.lang.Object[] | Die Argumente. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache kann nicht verwendet werden.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Lädt ein Bild aus einer CMX-Datei.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Dieser Aufruf cached nur die Standardseite.
    image.cacheData();

    // Cache alle Seiten, sodass keine zusätzlichen Daten aus dem zugrunde liegenden Datenstrom geladen werden.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

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

