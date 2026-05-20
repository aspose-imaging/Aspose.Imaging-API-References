---
title: "CdrImagePage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die CDR‑Bildseite"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

Die CDR‑Bildseite
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParentImage()](#getParentImage--) | Liefert das übergeordnete Bild. |
| [getPageNumber()](#getPageNumber--) | Liefert die Seitenzahl. |
| [isCached()](#isCached--) | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getFileFormat()](#getFileFormat--) | Ruft einen Wert des Dateiformats ab |
| [getCdrDocument()](#getCdrDocument--) | Liefert das CDR-Dokument. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ruft die Standardoptionen ab. |
| [cacheData()](#cacheData--) | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` durchgeführt werden. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Legt die Bildpalette fest. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Liefert das übergeordnete Bild.

Wert: Das übergeordnete Bild.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Liefert die Seitenzahl.

Wert: Die Seitenzahl.

**Returns:**
int – die Seitenzahl.
### isCached() {#isCached--}
```
public boolean isCached()
```


Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – die Bit‑Pro‑Pixel‑Anzahl des Bildes.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ruft einen Wert des Dateiformats ab

**Returns:**
long – ein Wert des Dateiformats
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Liefert das CDR-Dokument.

Wert: Das CDR-Dokument.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
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
public synchronized void cacheData()
```


Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` durchgeführt werden.

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

