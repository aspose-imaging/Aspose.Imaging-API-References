---
title: "CmxImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für das Corel Metafile Exchange CMX-Vektorbildformat mit Unterstützung von Metadatenbeschreibungen ist eine umfassende Lösung für Entwickler, die mit CMX-Dateien arbeiten."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

Die API für Corel Metafile Exchange (CMX) Vektorbildformat mit Unterstützung von Metadatenbeschreibungen ist eine umfassende Lösung für Entwickler, die mit CMX-Dateien arbeiten. Diese API ermöglicht das nahtlose Laden von CMX-Bildern, das Extrahieren von Metadaten wie Bits pro Pixel, Objektabmessungen und mehr. Mit zusätzlichen Funktionen wie Skalieren, Drehen, Festlegen von Paletten und der Konvertierung in andere Formate befähigt diese API Entwickler, CMX-Vektorbilder effizient zu manipulieren und anzupassen, um ihre spezifischen Anwendungsanforderungen zu erfüllen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Beginnen Sie die Arbeit mit der Klasse [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) nahtlos, indem Sie eine neue Instanz mit den Parametern streamContainer und loadOptions initialisieren. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Rufen Sie das Dateiformat des Bildes mühelos über diese benutzerfreundliche Eigenschaft ab. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Rufen Sie die Bit-Tiefe des Bildes mühelos über diese benutzerfreundliche Eigenschaft ab. |
| [getDefaultPage()](#getDefaultPage--) | Rufen Sie die Standardseite des Bildes mühelos über diese intuitive Eigenschaft ab. |
| [isCached()](#isCached--) | Bestimmen Sie, ob die Daten des Objekts derzeit im Cache sind, wodurch das Lesen von Daten entfällt. |
| [getWidthF()](#getWidthF--) | Rufen Sie die Breite des Objekts in Zoll über diese intuitive Eigenschaft ab. |
| [getHeightF()](#getHeightF--) | Erhalten Sie die Höhe des Objekts, gemessen in Zoll, mühelos über diese benutzerfreundliche Eigenschaft. |
| [getDocument()](#getDocument--) | Rufen Sie das CMX-Dokument mühelos über diese intuitive Eigenschaft ab. |
| [getCmxPage()](#getCmxPage--) | Rufen Sie die CMX-Seite des Bildes mühelos über diese intuitive Eigenschaft ab. |
| [getPageCount()](#getPageCount--) | Rufen Sie die Gesamtseitenzahl des Bildes über diese intuitive Eigenschaft ab. |
| [getPages()](#getPages--) | Rufen Sie die Seiten des Bildes nahtlos über diese intuitive Eigenschaft ab. |
| [cacheData()](#cacheData--) | Zwischenspeichern Sie die Daten, um zusätzliches Laden aus der zugrunde liegenden Quelle [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) mit dieser praktischen Methode zu verhindern. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Passen Sie die Farbpalette des Bildes mit dieser intuitiven Methode an. |

## Example: The following example shows how to cache all pages of a CMX image.

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

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Beginnen Sie die Arbeit mit der Klasse [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) nahtlos, indem Sie eine neue Instanz mit den Parametern streamContainer und loadOptions initialisieren. Ideal für Entwickler, die eine bequeme Möglichkeit suchen, CMX-Bilder aus verschiedenen Datenquellen zu laden und den Ladevorgang bei Bedarf anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie das Dateiformat des Bildes mühelos über diese benutzerfreundliche Eigenschaft ab. Ideal für Entwickler, die das Format ihrer Bilder dynamisch bestimmen möchten, um Kompatibilität und genaue Verarbeitung in ihren Anwendungen sicherzustellen.

**Returns:**
long - Das Dateiformat [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Rufen Sie die Bit-Tiefe des Bildes mühelos über diese benutzerfreundliche Eigenschaft ab. Ideal für Entwickler, die den Detailgrad oder die Farbtiefe ihrer Bilder bestimmen möchten, um eine genaue Verarbeitung und Manipulation sicherzustellen.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Rufen Sie die Standardseite des Bildes mühelos über diese intuitive Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf die Hauptseite ihres Bildes benötigen, um eine effiziente Navigation und Verwaltung zu gewährleisten.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Bestimmen Sie, ob die Daten des Objekts derzeit im Cache sind, wodurch das Lesen von Daten entfällt. Ideal für Entwickler, die die Leistung optimieren möchten, indem sie zwischengespeicherte Daten effizient nutzen, um einen schnelleren Zugriff auf Objektinformationen zu gewährleisten.

**Returns:**
boolean – `true`, wenn die Daten des Objekts im Cache sind; andernfalls `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Rufen Sie die Breite des Objekts in Zoll über diese intuitive Eigenschaft ab. Ideal für Entwickler, die präzise Messungen von Objekten in ihren Anwendungen benötigen, um ein genaues Layout und eine präzise Darstellung zu gewährleisten.

**Returns:**
float - Die Objektbreite in Zoll.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Erhalten Sie die Höhe des Objekts, gemessen in Zoll, mühelos über diese benutzerfreundliche Eigenschaft. Ideal für Entwickler, die präzise dimensionsbezogene Informationen für ein effektives Layout und eine ansprechende Darstellung in ihren Anwendungen benötigen.

**Returns:**
float - Die Objekthöhe in Zoll.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Rufen Sie das CMX-Dokument mühelos über diese intuitive Eigenschaft ab. Ideal für Entwickler, die auf CMX-Bilder zugreifen oder diese ändern möchten, um Flexibilität und Effizienz in ihren Anwendungen zu gewährleisten.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Rufen Sie die CMX-Seite des Bildes mühelos über diese intuitive Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf einzelne Seiten innerhalb von CMX-Bildern benötigen, um eine effiziente Navigation und Verwaltung zu gewährleisten.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Rufen Sie die Gesamtseitenzahl des Bildes mit dieser intuitiven Eigenschaft ab. Ideal für Entwickler, die mehrseitige Bilder dynamisch verwalten möchten und dabei eine effiziente Navigation und Manipulation des Bildinhalts sicherstellen.

**Returns:**
int – die Seitenanzahl.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Rufen Sie die Seiten des Bildes nahtlos mit dieser intuitiven Eigenschaft ab. Ideal für Entwickler, die auf einzelne Seiten in mehrseitigen Bildern zugreifen und diese manipulieren möchten, um eine effiziente Navigation und Verarbeitung zu gewährleisten.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.

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

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache die Daten, um zusätzliches Laden aus der zugrunde liegenden Quelle [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) mit dieser praktischen Methode zu verhindern. Ideal für Entwickler, die die Leistung durch Vorladen von Daten optimieren möchten und so einen schnelleren Zugriff sowie einen reibungsloseren Betrieb in ihren Anwendungen sicherstellen.


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


Passen Sie die Farbpalette des Bildes mit dieser intuitiven Methode an. Ideal für Entwickler, die spezifische Farbschemata oder Anpassungen dynamisch anwenden möchten und dabei eine präzise Kontrolle über das visuelle Erscheinungsbild ihrer Bilder sicherstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

