---
title: "EpsImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für die Unterstützung des Encapsulated PostScript (EPS) Bilddateiformats bietet robuste Möglichkeiten zur Manipulation von Kompositionen, die Text, Grafiken und Bilder enthalten."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

Die API für die Unterstützung des Encapsulated PostScript (EPS) Bilddateiformats bietet robuste Möglichkeiten zur Manipulation von Kompositionen, die Text, Grafiken und Bilder enthalten. Mit Funktionen wie der Handhabung von Bitmap‑Vorschau‑Bildern, dem Drehen der Ausrichtung, dem Abrufen von Begrenzungsrahmen für Illustrationsgrenzen, dem Skalieren, Drehen von Bildern und dem Hinzufügen von Vorschaubildern. Diese API gewährleistet eine nahtlose Verarbeitung und Integration von EPS‑Dateien in verschiedene Anwendungen mit Präzision und Vielseitigkeit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Greifen Sie einfach auf die Anzahl der verfügbaren Vorschaubilder zu. |
| [getPreviewImages()](#getPreviewImages--) | Rufen Sie die mit Ihrer Datei verknüpften Vorschaubilder ab. |
| [getFileFormat()](#getFileFormat--) | Greifen Sie mit dieser Eigenschaft auf das Dateiformat Ihres Bildes zu. |
| [getEpsType()](#getEpsType--) | Greifen Sie auf den Subtypwert Ihres EPS‑Bildes zu und interpretieren Sie ihn, um Ihren Arbeitsablauf zu optimieren und die Kompatibilität über Plattformen hinweg zu verbessern. |
| [hasRasterPreview()](#hasRasterPreview--) | Erkennen Sie mühelos das Vorhandensein einer Raster‑Vorschau mit dieser Eigenschaft. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Greifen Sie mühelos mit dieser Eigenschaft auf die genaue Bit‑Tiefe des Bildes zu. |
| [getWidthF()](#getWidthF--) | Rufen Sie die Breite des Bildes mit dieser praktischen Eigenschaft ab. |
| [getHeightF()](#getHeightF--) | Greifen Sie mit dieser Eigenschaft auf die Höhe des Bildes zu. |
| [isCached()](#isCached--) | Diese Eigenschaft bietet eine bequeme Möglichkeit zu prüfen, ob die Daten des Objekts derzeit im Cache sind, wodurch zusätzliches Datenlesen entfällt. |
| [getPsStream()](#getPsStream--) | Liefert den Stream, der das auszuführende PostScript enthält. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Diese Eigenschaft ruft die PostScript‑Version ab, die mit der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)‑Instanz verknüpft ist. |
| [getTitle()](#getTitle--) | Diese Eigenschaft ruft den Titel ab, der aus den im EPS‑Datei eingebetteten EPS Document Structuring Conventions (DSC)‑Kommentaren extrahiert wurde. |
| [getCreator()](#getCreator--) | Diese Eigenschaft bietet Zugriff auf die Ersteller‑Informationen, die aus den EPS Document Structuring Conventions (DSC)‑Kommentaren in der EPS‑Datei stammen. |
| [getCreationDate()](#getCreationDate--) | Durch das Abrufen des Erstellungsdatums aus den EPS Document Structuring Conventions (DSC)‑Kommentaren liefert diese Eigenschaft wichtige Metadaten, die den Entstehungszeitpunkt der EPS‑Datei anzeigen. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Durch das Abrufen des Erstellungsdatums aus den EPS Document Structuring Conventions (DSC)‑Kommentaren liefert diese Eigenschaft wichtige Metadaten, die den Entstehungszeitpunkt der EPS‑Datei anzeigen. |
| [getBoundingBox()](#getBoundingBox--) | Durch den Zugriff auf den ursprünglichen Begrenzungsrahmen in geräteunabhängigen Punkten liefert diese Eigenschaft entscheidende geometrische Informationen über die Abmessungen der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Diese Eigenschaft gibt den ursprünglichen Begrenzungsrahmen der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)‑Instanz in Pixeln zurück und liefert wichtige geometrische Daten für eine präzise Darstellung und Manipulation. |
| [cacheData()](#cacheData--) | Diese Eigenschaft gibt den ursprünglichen Begrenzungsrahmen der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)‑Instanz in Pixeln zurück und liefert wichtige geometrische Daten für eine präzise Darstellung und Manipulation. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Greift auf die mit der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)‑Instanz verknüpften Vorschaubilder zu und ermöglicht eine nahtlose Abrufung zur Inspektion oder Nutzung in Anwendungen. |
| [getPreviewImage()](#getPreviewImage--) | Ruft das vorhandene Vorschaubild im angegebenen `format` ab oder gibt `` zurück, wenn keines gefunden wird. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Ruft das vorhandene Vorschaubild im angegebenen `format` ab oder gibt `` zurück, wenn keines gefunden wird. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Passen Sie Bildpaletten an, um einzigartige Farbschemata zu erzielen und die visuelle Attraktivität zu steigern. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// EPS-Bild laden.
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Bild skalieren mit der Mitchell-Kubik-Interpolationsmethode.
    image.resize(400, 400, ResizeType.Mitchell);

    // Bild in das PNG-Format exportieren.
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// EPS-Bild laden.
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Interpolationsmodus festlegen.
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Filtertyp festlegen.
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Legt die Farbvergleichsmethode fest.
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Farbquantisierungsmethode festlegen.
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Bild skalieren mit erweiterten Skalierungseinstellungen.
    image.resize(400, 400, resizeSettings);

    // Bild in das PNG-Format exportieren.
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Greifen Sie einfach auf die Anzahl der verfügbaren Vorschaubilder zu. Diese Eigenschaft ermöglicht es Ihnen, mühelos die Anzahl der mit Ihrer Datei verknüpften Vorschaubilder abzurufen, was eine effiziente Verwaltung und Navigation Ihrer Bildvorschauen ermöglicht. Ideal, um Ihren Arbeitsablauf zu optimieren und Ihre Bildressourcen effektiv zu organisieren.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Rufen Sie die mit Ihrer Datei verknüpften Vorschaubilder ab. Diese Eigenschaft bietet nahtlosen Zugriff auf die Sammlung von Vorschaubildern, sodass Sie sie bei Bedarf effizient durchsuchen und verwalten können. Ideal, um schnell Vorschauen zu sehen und das passende Bild für Ihr Projekt auszuwählen.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Greifen Sie mit dieser Eigenschaft auf das Dateiformat Ihres Bildes zu. Rufen Sie wesentliche Informationen über das Format Ihrer Bilddatei ab, um Kompatibilität und effiziente Verarbeitung zu ermöglichen. Ideal, um das Format Ihrer Bilddateien zu identifizieren und eine nahtlose Integration in Ihre Projekte zu gewährleisten.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Greifen Sie auf den Subtypwert Ihres EPS-Bildes zu und interpretieren Sie ihn, um Ihren Arbeitsablauf zu optimieren und die Kompatibilität über Plattformen hinweg zu verbessern. Ideal, um die EPS-Subtyp‑Abrufung in Ihren Projekten präzise und effizient zu optimieren.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Erkennen Sie mühelos das Vorhandensein einer Rastervorschau mit dieser Eigenschaft. Greifen Sie auf den booleschen Wert zu, der angibt, ob die [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-Instanz eine Rastervorschau enthält, und stärken Sie Ihre Bildverarbeitungsaufgaben mit Klarheit und Effizienz. Ideal, um Workflow‑Entscheidungen basierend auf dem Vorhandensein oder Fehlen von Rastervorschauen in EPS‑Bildern zu vereinfachen.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Greifen Sie mit dieser Eigenschaft mühelos auf die genaue Bit‑Tiefe des Bildes zu. Rufen Sie die Bits‑pro‑Pixel‑Anzahl ab, was wichtige Einblicke in die Farbtiefe des Bildes liefert und bei der Optimierung von Verarbeitungsaufgaben hilft. Ideal für Anwendungen, die eine feinkörnige Kontrolle über Bildmanipulation und Analyse erfordern.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Rufen Sie mit dieser praktischen Eigenschaft die Breite des Bildes ab. Erhalten Sie die Bildbreite mühelos, was präzise Layout‑Berechnungen, Skalierungsoperationen und dimensionbezogene Aufgaben in Ihrer Anwendung erleichtert. Ideal, um eine genaue Darstellung und Anzeige von Bildern über verschiedene Plattformen und Geräte hinweg sicherzustellen.

**Returns:**
float - Die Bildbreite in Pixeln.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Greifen Sie mit dieser Eigenschaft auf die Höhe des Bildes zu. Erhalten Sie die Bildhöhe mühelos, was nahtlose Layout‑Anpassungen, Seitenverhältnis‑Berechnungen und eine präzise Darstellung über verschiedene Bildschirmauflösungen und Anzeigeumgebungen ermöglicht.

**Returns:**
float - Die Bildhöhe in Pixeln.
### isCached() {#isCached--}
```
public boolean isCached()
```


Diese Eigenschaft bietet eine bequeme Möglichkeit zu prüfen, ob die Daten des Objekts derzeit im Cache liegen, wodurch zusätzliches Datenlesen entfällt. Sie ermöglicht eine schnelle und effiziente Methode, um festzustellen, ob die benötigten Informationen sofort verfügbar sind, was die Leistung optimiert und den Ressourcenaufwand bei datenintensiven Vorgängen reduziert.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Liefert den Stream, der das auszuführende PostScript enthält.

**Returns:**
java.io.InputStream – der Stream, der das auszuführende PostScript enthält.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Diese Eigenschaft ruft die PostScript‑Version ab, die mit der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-Instanz verknüpft ist. Sie liefert Einblicke in die spezifische PostScript‑Sprachversion, die in der EPS‑Datei verwendet wird, und unterstützt die Bewertung der Kompatibilität sowie die nahtlose Integration in PostScript‑kompatible Umgebungen.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


Diese Eigenschaft ruft den Titel ab, der aus den EPS Document Structuring Conventions (DSC)-Kommentaren extrahiert wurde, die in der EPS‑Datei eingebettet sind. Sie liefert wertvolle Metadaten über den Inhalt der EPS‑Datei und unterstützt die Dokumentenorganisation sowie die Identifizierung in kompatiblen Softwareanwendungen.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Diese Eigenschaft bietet Zugriff auf die Erstellerinformationen, die aus den EPS Document Structuring Conventions (DSC)-Kommentaren der EPS‑Datei stammen. Das Verständnis der Erstellerdetails liefert Einblicke in die Software oder das Werkzeug, das zur Erstellung der EPS‑Datei verwendet wurde, und erleichtert die Bewertung der Kompatibilität über verschiedene Plattformen und Anwendungen hinweg.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Durch das Abrufen des Erstellungsdatums aus den EPS Document Structuring Conventions (DSC)-Kommentaren liefert diese Eigenschaft wesentliche Metadaten, die den Beginn der EPS‑Datei anzeigen. Durch den Zugriff auf diese Informationen erhalten Benutzer Einblicke in die Herkunft und Chronologie der Datei, was das Dateimanagement und die Organisation verbessert.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Durch das Abrufen des Erstellungsdatums aus den EPS Document Structuring Conventions (DSC)-Kommentaren liefert diese Eigenschaft wesentliche Metadaten, die den Beginn der EPS‑Datei anzeigen. Durch den Zugriff auf diese Informationen erhalten Benutzer Einblicke in die Herkunft und Chronologie der Datei, was das Dateimanagement und die Organisation verbessert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Durch den Zugriff auf die ursprüngliche Begrenzungsbox in geräteunabhängigen Punkten liefert diese Eigenschaft wichtige geometrische Informationen über die Abmessungen der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Durch das Abrufen dieser Daten können Benutzer die Bildgröße und das Seitenverhältnis genau beurteilen, was präzises Layout und Positionierung in verschiedenen Anwendungen ermöglicht.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Diese Eigenschaft gibt die ursprüngliche Begrenzungsbox der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-Instanz in Pixeln zurück und liefert wesentliche geometrische Daten für eine genaue Darstellung und Manipulation. Mit diesen Informationen können Benutzer die präzise Platzierung und Größe von EPS‑Bildern in ihren Projekten sicherstellen, was die Gesamtpräsentation und -qualität verbessert.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


Diese Eigenschaft gibt die ursprüngliche Begrenzungsbox der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-Instanz in Pixeln zurück und liefert wesentliche geometrische Daten für eine genaue Darstellung und Manipulation. Mit diesen Informationen können Benutzer die präzise Platzierung und Größe von EPS‑Bildern in ihren Projekten sicherstellen, was die Gesamtpräsentation und -qualität verbessert.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Greift auf die mit der [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)-Instanz verknüpften Vorschaubilder zu und ermöglicht ein nahtloses Abrufen zur Inspektion oder Nutzung in Anwendungen. Diese Methode bietet einen bequemen Zugriff auf Vorschaubilder und verbessert die Benutzerinteraktion mit den Bilddaten.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> – die Vorschaubilder.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Ruft das vorhandene Vorschaubild im angegebenen `format` ab oder gibt `` zurück, wenn keines gefunden wird. Diese Methode bietet Flexibilität beim Zugriff auf Vorschaubilder, die für bestimmte Formate angepasst sind, und optimiert die Kompatibilität sowie das Ressourcenmanagement in Anwendungen.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Ruft das vorhandene Vorschaubild im angegebenen `format` ab oder gibt `` zurück, wenn keines gefunden wird. Diese Methode bietet Flexibilität beim Zugriff auf Vorschaubilder, die für bestimmte Formate angepasst sind, und optimiert die Kompatibilität sowie das Ressourcenmanagement in Anwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | long | Das EPS‑Vorschaubildformat. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Passen Sie Bildpaletten an, um einzigartige Farbschemata zu erzielen und die visuelle Attraktivität zu steigern. Gestalten Sie Farben für spezifische Effekte und optimieren Sie die Bildqualität mühelos über verschiedene Plattformen und Geräte hinweg.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

