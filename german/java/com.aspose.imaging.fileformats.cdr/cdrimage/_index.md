---
title: "CdrImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für die Unterstützung des CorelDRAW CDR-Vektorbildformats ist ein unverzichtbares Toolkit für Entwickler, die mit Vektorgrafiken arbeiten."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

Die API für die Unterstützung des CorelDRAW CDR-Vektorbildformats ist ein unverzichtbares Toolkit für Entwickler, die mit Vektorgrafiken arbeiten. Diese API ermöglicht die nahtlose Verarbeitung von CDR‑Dateien und erlaubt die Speicherung und Manipulation verschiedener Elemente wie Text, Linien, Formen, Bilder, Farben und Effekte. Mit ihren umfassenden Funktionen können Entwickler effizient mit Vektorrepräsentationen von Bildinhalten arbeiten und dabei Präzision sowie Flexibilität beim programmgesteuerten Erstellen und Bearbeiten von CorelDRAW-Vektorgrafiken sicherstellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Beginnen Sie mühelos mit der [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage)-Klasse zu arbeiten, indem Sie eine neue Instanz mit einem Stream und den loadOptions‑Parametern initialisieren. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Beginnen Sie mühelos mit der [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage)-Klasse zu arbeiten, indem Sie eine neue Instanz mit einem Stream und den loadOptions‑Parametern initialisieren. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Rufen Sie die Standardseite des Bildes ganz einfach über diese benutzerfreundliche Eigenschaft ab. |
| [isCached()](#isCached--) | Ermitteln Sie mühelos, ob die Daten des Objekts derzeit im Cache liegen, und vermeiden Sie so das erneute Lesen der Daten. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Rufen Sie die Bit-Tiefe des Bildes mühelos über diese benutzerfreundliche Eigenschaft ab. |
| [getPageCount()](#getPageCount--) | Rufen Sie mit dieser intuitiven Eigenschaft die Gesamtseitenzahl des Bildes ab oder aktualisieren Sie sie mühelos. |
| [getPages()](#getPages--) | Rufen Sie die Seiten des Bildes nahtlos über diese intuitive Eigenschaft ab. |
| [getCdrDocument()](#getCdrDocument--) | Greifen Sie mit dieser intuitiven Eigenschaft mühelos auf das CDR‑Dokument zu oder aktualisieren Sie es. |
| [getFileFormat()](#getFileFormat--) | Ermitteln Sie das Dateiformat des Bildes mühelos über diese intuitive Eigenschaft. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [cacheData()](#cacheData--) | Cache‑en Sie die Daten mühelos, um ein zusätzliches Laden aus der zugrunde liegenden Quelle zu verhindern, indem Sie diese benutzerfreundliche Methode verwenden. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Passen Sie die Farbpalette des Bildes mit dieser intuitiven Methode an. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Laden Sie ein Bild aus einer CDR‑Datei.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Dieser Aufruf cached nur die Standardseite.
    image.cacheData();

    // Cache alle Seiten, sodass keine zusätzlichen Daten aus dem zugrunde liegenden Datenstrom geladen werden.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Beginnen Sie mühelos mit der [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage)-Klasse zu arbeiten, indem Sie eine neue Instanz mit einem Stream und den loadOptions‑Parametern initialisieren. Ideal für Entwickler, die eine bequeme Möglichkeit suchen, CDR‑Bilder aus verschiedenen Datenquellen zu laden und den Ladevorgang bei Bedarf anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Beginnen Sie mühelos mit der [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage)-Klasse zu arbeiten, indem Sie eine neue Instanz mit einem Stream und den loadOptions‑Parametern initialisieren. Ideal für Entwickler, die eine bequeme Möglichkeit suchen, CDR‑Bilder aus verschiedenen Datenquellen zu laden und den Ladevorgang bei Bedarf anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | com.aspose.ms.System.IO.Stream | Der Stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Rufen Sie die Standardseite des Bildes ganz einfach über diese benutzerfreundliche Eigenschaft ab. Perfekt für Entwickler, die schnellen Zugriff auf die Hauptseite ihres Bildes benötigen und dabei eine effiziente Navigation und Verwaltung sicherstellen.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Ermitteln Sie mühelos, ob die Daten des Objekts derzeit im Cache liegen, und vermeiden Sie so das erneute Lesen der Daten. Ideal für Entwickler, die die Leistung optimieren möchten, indem sie zwischengespeicherte Daten effizient nutzen und so einen schnelleren Zugriff auf Objektinformationen gewährleisten.

**Returns:**
boolean – `true`, wenn die Daten des Objekts im Cache sind; andernfalls `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Rufen Sie die Bit-Tiefe des Bildes mühelos über diese benutzerfreundliche Eigenschaft ab. Ideal für Entwickler, die den Detailgrad oder die Farbtiefe ihrer Bilder bestimmen möchten, um eine genaue Verarbeitung und Manipulation sicherzustellen.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Rufen Sie mit dieser intuitiven Eigenschaft die Gesamtseitenzahl des Bildes ab oder aktualisieren Sie sie mühelos. Ideal für Entwickler, die mehrseitige Bilder dynamisch verwalten möchten und dabei eine effiziente Navigation sowie Manipulation des Bildinhalts sicherstellen.

**Returns:**
int – die Seitenanzahl.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Rufen Sie die Seiten des Bildes nahtlos mit dieser intuitiven Eigenschaft ab. Ideal für Entwickler, die auf einzelne Seiten in mehrseitigen Bildern zugreifen und diese manipulieren möchten, um eine effiziente Navigation und Verarbeitung zu gewährleisten.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Greifen Sie mit dieser intuitiven Eigenschaft mühelos auf das CDR‑Dokument zu oder aktualisieren Sie es. Ideal für Entwickler, die das CDR‑Dokument zugreifen oder ändern möchten und dabei Flexibilität und Effizienz in ihren Anwendungen sicherstellen.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ermitteln Sie das Dateiformat des Bildes mühelos über diese intuitive Eigenschaft. Ideal für Entwickler, die das Format ihrer Bilder dynamisch bestimmen möchten und dabei Kompatibilität sowie eine genaue Verarbeitung in ihren Anwendungen sicherstellen.

**Returns:**
long
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
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache‑en Sie die Daten mühelos, um ein zusätzliches Laden aus der zugrunde liegenden Quelle zu verhindern, indem Sie diese benutzerfreundliche Methode verwenden. Ideal für Entwickler, die die Leistung optimieren möchten, indem sie Daten vorab laden und so einen schnelleren Zugriff sowie einen reibungsloseren Betrieb in ihren Anwendungen gewährleisten. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Laden Sie ein Bild aus einer CDR‑Datei.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Dieser Aufruf cached nur die Standardseite.
    image.cacheData();

    // Cache alle Seiten, sodass keine zusätzlichen Daten aus dem zugrunde liegenden Datenstrom geladen werden.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
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

