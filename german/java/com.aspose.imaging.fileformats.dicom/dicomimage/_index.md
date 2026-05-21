---
title: "DicomImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Diese Klasse implementiert Digital Imaging and Communications in Medicine DICOM Rasterbildformat-Unterstützung und bietet eine umfassende Lösung für die präzise und flexible Verarbeitung von DICOM‑Bildern."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Diese Klasse implementiert Digital Imaging and Communications in Medicine (DICOM) Rasterbildformat-Unterstützung und bietet eine umfassende Lösung für die präzise und flexible Verarbeitung von DICOM‑Bildern. Sie können Bildseiten nahtlos manipulieren, einschließlich Operationen zum Abrufen, Hinzufügen oder Entfernen von Seiten, und die Standard‑ und aktive Seite steuern. Mit Funktionen zur Arbeit mit Alphakanälen, Einbetten von XMP‑Metadaten, Skalieren, Drehen, Zuschneiden, Binarisieren, Anpassen, Anwenden von Filtern und Konvertieren in andere Rasterformate. Diese API ermöglicht Entwicklern, DICOM‑Bilder effektiv zu handhaben und gleichzeitig unterschiedliche Anwendungsanforderungen im medizinischen Bildgebungsbereich zu erfüllen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | Initialisieren Sie mühelos eine neue Instanz der DicomImage‑Klasse mit diesem Konstruktor, wobei die Parameter dicomOptions verwendet werden. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Initialisieren Sie eine neue Instanz der DicomImage-Klasse reibungslos, indem Sie im Konstruktor einen Stream- und loadOptions-Parameter verwenden. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | Erstellen Sie eine neue Instanz der DicomImage-Klasse, indem Sie im Konstruktor einen Stream-Parameter verwenden. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageCount()](#getPageCount--) | Rufen Sie die Gesamtseitenzahl des Bildes über diese intuitive Eigenschaft ab. |
| [getPages()](#getPages--) | Greifen Sie über diese intuitive Eigenschaft auf die Seiten des Bildes zu. |
| [getFileInfo()](#getFileInfo--) | Rufen Sie mühelos wertvolle Header-Informationen aus der DICOM-Datei über diese intuitive Eigenschaft ab. |
| [getDicomPages()](#getDicomPages--) | Greifen Sie über diese intuitive Eigenschaft auf die Seiten des Bildes zu. |
| [getActivePage()](#getActivePage--) | Greifen Sie über diese intuitive Eigenschaft auf die aktive Seite des Bildes zu. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | Verwalten Sie die aktive Seite des Bildes über diese intuitive Eigenschaft. |
| [getActivePageIndex()](#getActivePageIndex--) | Rufen Sie mühelos den Index der aktiven Seite über diese intuitive Eigenschaft ab. |
| [getFileFormat()](#getFileFormat--) | Rufen Sie den Dateiformatwert mühelos über diese intuitive Eigenschaft ab. |
| [hasAlpha()](#hasAlpha--) | Ermitteln Sie mühelos, ob das Bild einen Alpha-Kanal besitzt, über diese intuitive Eigenschaft. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Erweitern Sie Ihre Bildsammlung, indem Sie mit dieser intuitiven Methode eine neue Seite hinzufügen. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Bewahren Sie die Daten des Objekts, indem Sie es am vorgesehenen Dateipfad (Indexer + Dateiname) zusammen mit dem angegebenen Dateiformat und den Optionen speichern. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Passen Sie die Auflösung dieses [RasterImage](../../com.aspose.imaging/rasterimage) präzise mit dieser einfachen Methode an. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Ändern Sie die Größe des Bildes, wobei das Seitenverhältnis erhalten bleibt, mit dieser praktischen Methode. |
| [addPage()](#addPage--) | Fügen Sie am Ende der Seitenliste des Bildes eine neue Seite mit dieser einfachen Methode hinzu. |
| [insertPage(int pageIndex)](#insertPage-int-) | Fügen Sie an einem angegebenen Index eine neue Seite in die Seitenliste des Bildes ein mit dieser intuitiven Methode. |
| [removePage(int pageIndex)](#removePage-int-) | Entfernen Sie die Seite am angegebenen Index aus der Seitenliste mit dieser praktischen Methode. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Drehen Sie das Bild um sein Zentrum mit dieser praktischen Methode. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Passen Sie die Größe des Bildes mit dieser einfachen Methode an. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Passen Sie die Breite des Bildes an, wobei das Seitenverhältnis erhalten bleibt, mit dieser praktischen Methode. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Passen Sie die Höhe des Bildes an, wobei das Seitenverhältnis erhalten bleibt, mit dieser benutzerfreundlichen Methode. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Manipulieren Sie den aktiven Frame einfach, indem Sie ihn drehen, spiegeln oder beide Aktionen gleichzeitig ausführen, mit dieser einfachen Methode. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Verbessern Sie das aktuelle Bild, indem Sie Dithering-Effekte mit dieser einfachen Methode anwenden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beschneiden Sie das Bild, um unerwünschte Bereiche zu entfernen und den wesentlichen Inhalt zu fokussieren, mit dieser einfachen Methode. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Passen Sie den Beschnittbereich des Bildes an, indem Sie Verschiebungen mit dieser vielseitigen Methode anwenden. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Konvertieren Sie das Bild einfach in ein Binärformat, indem Sie einen vordefinierten Schwellenwert mit dieser einfachen Methode verwenden. |
| [binarizeOtsu()](#binarizeOtsu--) | Wenden Sie die Otsu-Schwellenwertbestimmung an, um das Bild zu binarisieren, wobei der optimale Schwellenwert basierend auf dem Histogramm des Bildes automatisch ermittelt wird. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisieren Sie Bilder mit Bradleys adaptivem Schwellenwertalgorithmus und nutzen Sie die Integralbild‑Schwellenwertbestimmung für verbesserte Leistung. |
| [grayscale()](#grayscale--) | Transformieren Sie Bilder mühelos in ihre Graustufen‑Darstellung, wodurch die visuelle Analyse und Verarbeitung vereinfacht wird. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Verbessern Sie die Bildqualität und passen Sie sie mit der Gammakorrektur an, einer leistungsstarken Technik zur Feinabstimmung des visuellen Erscheinungsbildes. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Erreichen Sie präzise Farbkorrekturen, indem Sie die Gammakorrektur unabhängig auf die roten, grünen und blauen Komponenten eines Bildes anwenden. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Verbessern Sie die Bildluminanz durch die Anpassung von `brightness`, einer parametrisierten Methode, die Entwicklern ermöglicht, die Helligkeit von Bildern fein abzustimmen. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Verbessern Sie den Kontrast von [Image](../../com.aspose.imaging/image) mit dieser benutzerfreundlichen Methode, die den Unterschied zwischen hellen und dunklen Bereichen anpasst. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Verbessern Sie mühelos bestimmte Bereiche Ihres Bildes, indem Sie Filter auf festgelegte Rechtecke anwenden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Passen Sie die Größe Ihres Bildes mit dieser einfachen Skalierungsmethode an. |
| [cacheData()](#cacheData--) | Diese Methode cached Daten effizient, optimiert die Leistung und sorgt für schnellen Zugriff bei Bedarf. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// Ein Bild laden
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Zeichnen Sie etwas mit Vektorgrafiken.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Speichern Sie die Pixel des gezeichneten Bildes. Sie befinden sich nun auf der ersten Seite des Dicom‑Bildes.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Fügen Sie ein paar Seiten danach hinzu und machen Sie sie dunkler.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Fügen Sie ein paar Seiten vor der Hauptseite hinzu und machen Sie sie heller.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Speichern Sie das erstellte mehrseitige Bild in der Ausgabedatei.
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


Initialisieren Sie mühelos eine neue Instanz der Klasse DicomImage mit diesem Konstruktor und verwenden Sie die Parameter dicomOptions. Perfekt für Entwickler, die schnell und effizient in [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage)-Objekte in ihren Projekten einsteigen möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | Die DICOM-Optionen (derzeit ignoriert). |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


Initiieren Sie eine neue Instanz der Klasse DicomImage reibungslos, indem Sie in diesem Konstruktor einen Stream und die Parameter loadOptions verwenden. Ideal für Entwickler, die zügig und effektiv mit [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage)-Objekten in ihren Projekten arbeiten möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


Erstellen Sie eine neue Instanz der Klasse DicomImage, indem Sie in diesem Konstruktor einen Stream-Parameter verwenden. Perfekt für Entwickler, die einen schlanken Weg suchen, um [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage)-Objekte aus bestehenden Datenströmen in ihren Projekten zu initialisieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Rufen Sie die Gesamtseitenzahl des Bildes mit dieser intuitiven Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf die Anzahl der Seiten eines Bildes benötigen, um eine effiziente Navigation und Verwaltung zu gewährleisten.

**Returns:**
int – die Seitenanzahl.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Greifen Sie mit dieser intuitiven Eigenschaft auf die Seiten des Bildes zu. Ideal für Entwickler, die mit einzelnen Seiten des Bildes interagieren möchten, um nahtlose Navigation und Manipulation zu gewährleisten.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


Rufen Sie wertvolle Header-Informationen aus der DICOM-Datei mühelos mit dieser intuitiven Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf wesentliche Details in der DICOM-Datei benötigen, um eine effiziente Datenextraktion und Analyse zu gewährleisten.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


Greifen Sie mit dieser intuitiven Eigenschaft auf die Seiten des Bildes zu. Ideal für Entwickler, die mit einzelnen Seiten des Bildes interagieren möchten, um nahtlose Navigation und Manipulation zu gewährleisten.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] – die Seiten.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


Zugriff auf die aktive Seite des Bildes mit dieser intuitiven Eigenschaft. Ideal für Entwickler, die dynamisch zwischen Seiten in mehrseitigen Bildern wechseln möchten, um eine effiziente Navigation und Verarbeitung zu gewährleisten.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


Verwalten Sie die aktive Seite des Bildes mit dieser intuitiven Eigenschaft. Ideal für Entwickler, die dynamisch zwischen Seiten in mehrseitigen Bildern wechseln möchten, um eine effiziente Navigation und Verarbeitung zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | die aktive Seite. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


Rufen Sie den Index der aktiven Seite mühelos mit dieser intuitiven Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf den aktuellen Seitenindex in mehrseitigen Bildern benötigen, um eine effiziente Navigation und Verarbeitung zu gewährleisten.

**Returns:**
int – der Index der aktiven Seite.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie den Dateiformatwert mühelos mit dieser intuitiven Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf das Format der Bilddatei benötigen, um eine effiziente Handhabung und Verarbeitung basierend auf dem Dateityp zu gewährleisten.

**Returns:**
long - ein Wert des Dateiformats [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Ermitteln Sie mühelos, ob das Bild einen Alpha‑Kanal besitzt, mit dieser intuitiven Eigenschaft. Ideal für Entwickler, die feststellen möchten, ob das Bild Transparenzinformationen enthält, und eine präzise Handhabung von Alpha‑Kanal‑Daten in Bildverarbeitungsaufgaben sicherstellen.

**Returns:**
boolean - true, wenn das Bild einen Alpha‑Kanal hat.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Erweitern Sie Ihre Bildsammlung, indem Sie mit dieser intuitiven Methode eine neue Seite hinzufügen. Ideal für Entwickler, die dynamisch Seiten zu mehrseitigen Bildern hinzufügen möchten, um eine nahtlose Erweiterung und Organisation des Bildinhalts zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Die hinzuzufügende Seite. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


Bewahren Sie die Daten des Objekts, indem Sie sie am vorgesehenen Speicherort (Indexer + Dateiname) zusammen mit dem angegebenen Dateiformat und Optionen speichern. Ideal für Entwickler, die Daten sicher in verschiedenen Formaten speichern möchten, wobei Flexibilität und Kontrolle über die Speicherparameter erhalten bleiben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Optionen. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Passen Sie die Auflösung dieses [RasterImage](../../com.aspose.imaging/rasterimage) präzise mit dieser unkomplizierten Methode an. Ideal für Entwickler, die die Bildauflösung an spezifische Anforderungen anpassen möchten, um optimale Anzeigequalität und Dateigrößenverwaltung zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | double | Die horizontale Auflösung in Punkten pro Zoll (dpi) des [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Die vertikale Auflösung in Punkten pro Zoll (dpi) des [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Skalieren Sie das Bild bei Beibehaltung des Seitenverhältnisses mit dieser praktischen Methode. Ideal für Entwickler, die die Bildabmessungen proportional anpassen möchten, um Konsistenz zu gewährleisten und die Proportionen des Originalinhalts zu erhalten. Die proportionale Skalierung ändert die Größe jedes Frames gemäß dem Verhältnis von `newWidth`/width und `newHeight`/height.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


Fügen Sie mit dieser unkomplizierten Methode eine neue Seite am Ende der Seitenliste des Bildes hinzu. Ideal für Entwickler, die mehrseitige Bilder dynamisch erweitern möchten, um eine nahtlose Integration und Organisation des Bildinhalts zu gewährleisten.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


Fügen Sie mit dieser intuitiven Methode eine neue Seite an einem angegebenen Index in die Seitenliste des Bildes ein. Ideal für Entwickler, die präzise Kontrolle über die Anordnung von Seiten in mehrseitigen Bildern benötigen, um eine nahtlose Organisation und Anpassung des Bildinhalts zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageIndex | int | Index der Seite. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Zeichnen Sie etwas mit Vektorgrafiken.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Speichern Sie die Pixel des gezeichneten Bildes. Sie befinden sich nun auf der ersten Seite des Dicom‑Bildes.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Fügen Sie ein paar Seiten danach hinzu und machen Sie sie dunkler.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Fügen Sie ein paar Seiten vor der Hauptseite hinzu und machen Sie sie heller.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Speichern Sie das erstellte mehrseitige Bild in der Ausgabedatei.
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


Entfernen Sie die Seite am angegebenen Index aus der Seitenliste mit dieser praktischen Methode. Ideal für Entwickler, die präzise Kontrolle über die Verwaltung von mehrseitigen Bildern benötigen, um eine nahtlose Organisation und Anpassung des Bildinhalts zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageIndex | int | Index der Seite. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Drehen Sie das Bild um sein Zentrum mit dieser praktischen Methode. Ideal für Entwickler, die die Bildausrichtung dynamisch anpassen möchten, um eine optimale Darstellung und Ausrichtung in ihren Anwendungen zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur die `` Bildinhalte werden rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Laden Sie ein DICOM‑Bild aus einem Dateistream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // Drehen Sie das Bild um das Zentrum um 60 Grad im Uhrzeigersinn.
        // Verwenden Sie Grau als Hintergrundfarbe.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Beachten Sie, dass ein farbiges Bild automatisch in das Graustufenformat konvertiert wird, gemäß den untenstehenden Optionen.
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // Erstellen Sie ein Array von TIFF‑Frames.
        // Die Anzahl der Frames entspricht der Anzahl der DJVU‑Seiten.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // Speichern Sie jede Seite als einzelnen TIFF‑Frame.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // Erstellen Sie einen TIFF‑Frame basierend auf der DICOM‑Seite.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // Erstellen Sie ein TIFF‑Bild aus den Frames.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // In einer Datei speichern.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Passen Sie die Größe des Bildes mit dieser unkomplizierten Methode an. Ideal für Entwickler, die Bilder dynamisch skalieren möchten, um sie nahtlos in verschiedene Kontexte und Layouts ihrer Anwendungen einzufügen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Passen Sie die Breite des Bildes bei Beibehaltung des Seitenverhältnisses mit dieser praktischen Methode an. Ideal für Entwickler, die Bilder proportional skalieren möchten, um konsistente und optisch ansprechende Ergebnisse in verschiedenen Anzeigeumgebungen zu erzielen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein DICOM‑Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Breite angegeben, die Höhe wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Passen Sie die Höhe des Bildes an, während Sie das Seitenverhältnis mit dieser benutzerfreundlichen Methode beibehalten. Perfekt für Entwickler, die Bilder dynamisch skalieren möchten, wobei die Proportionen erhalten bleiben, um eine optimale Anzeige und Benutzerfreundlichkeit in ihren Anwendungen zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein DICOM‑Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Höhe angegeben, die Breite wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Manipulieren Sie das aktive Bild einfach durch Drehen, Spiegeln oder beides gleichzeitig mit dieser unkomplizierten Methode. Ideal für Entwickler, die die Orientierung einzelner Frames in Bildsequenzen dynamisch anpassen müssen, um eine optimale Darstellung und Ausrichtung zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Rotations‑Flip‑Typ. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Drehen, spiegeln und in die Ausgabedatei speichern.
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Verbessern Sie das aktuelle Bild, indem Sie Dithering‑Effekte mit dieser einfachen Methode anwenden. Perfekt für Entwickler, die Textur und Tiefe zu Bildern hinzufügen möchten, um deren visuelle Qualität und Gesamteindruck zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Führen Sie Schwellenwert-Dithering mit einer 4‑Bit-Farbpalette durch, die 16 Farben enthält.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Führen Sie Floyd-Dithering mit einer 1‑Bit-Farbpalette durch, die nur 2 Farben enthält – Schwarz und Weiß.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beschneiden Sie das Bild, um unerwünschte Bereiche zu entfernen und den Fokus auf wesentliche Inhalte zu legen, mit dieser einfachen Methode. Ideal für Entwickler, die die visuelle Zusammensetzung von Bildern anpassen möchten, um die gewünschte Botschaft effektiv zu vermitteln.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |


**Example: The following example crops a DICOM image.**
Das folgende Beispiel schneidet ein DICOM‑Bild zu. Der Zuschnittbereich wird über Aspose.Imaging.Rectangle angegeben.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Schneiden Sie das Bild zu. Der Zuschnittsbereich ist der rechteckige zentrale Bereich des Bildes.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // Speichern Sie das zugeschnittene Bild als PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Passen Sie den Zuschnittbereich des Bildes an, indem Sie Verschiebungen mit dieser vielseitigen Methode anwenden. Perfekt für Entwickler, die eine präzise Kontrolle über den Zuschnitt benötigen, um wichtige Details zu erhalten und gleichzeitig unnötige Elemente zu entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |


**Example: The following example crops a DICOM image.**
Das folgende Beispiel schneidet ein DICOM‑Bild zu. Der Zuschnittbereich wird über die Ränder Links, Oben, Rechts, Unten angegeben.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Erneut zuschneiden. Setzen Sie einen Rand von 10 % der Bildgröße.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Speichern Sie das zugeschnittene Bild als PNG.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Konvertieren Sie das Bild einfach in ein Binärformat, indem Sie mit dieser unkomplizierten Methode einen vordefinierten Schwellenwert verwenden. Ideal für Entwickler, die Bildverarbeitungsaufgaben vereinfachen möchten, indem sie das Bild anhand festgelegter Intensitätswerte in Vorder‑ und Hintergrundkomponenten segmentieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, andernfalls 0. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
Das folgende Beispiel binarisiert ein DICOM‑Bild mit dem vordefinierten Schwellenwert. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisieren Sie das Bild mit einem Schwellenwert von 127.
    // Wenn der entsprechende Grauwert eines Pixels größer als 127 ist, wird ihm der Wert 255 zugewiesen, sonst 0.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Wenden Sie die Otsu‑Schwellwertbestimmung an, um das Bild zu binarisieren, wobei der optimale Schwellenwert automatisch anhand des Histogramms des Bildes ermittelt wird. Perfekt für Entwickler, die eine zuverlässige Methode suchen, um Bilder mit minimalem manuellem Aufwand in Vorder‑ und Hintergrundbereiche zu segmentieren.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
Das folgende Beispiel binarisiert ein DICOM‑Bild mit Otsu‑Schwellwertbestimmung. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisieren Sie das Bild mit Otsu‑Schwellenwertverfahren.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisieren Sie Bilder mit Bradleys adaptivem Schwellwert‑Algorithmus, der die Integral‑Bild‑Schwellwertbestimmung für bessere Leistung nutzt. Ideal für Entwickler, die Bilder automatisch anhand lokaler Helligkeitsvariationen segmentieren möchten, um eine genaue Objekterkennung und -extraktion bei unterschiedlichen Lichtbedingungen zu gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| windowSize | int | Die Größe des s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
Das folgende Beispiel binarisiert ein DICOM‑Bild mit Bradleys adaptivem Schwellwert‑Algorithmus und der angegebenen Fenstergröße. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisieren Sie das Bild mit einem Helligkeitsunterschied von 5. Die Helligkeit ist die Differenz zwischen einem Pixel und dem Durchschnitt eines 10 × 10‑Pixel‑Fensters, das um diesen Pixel zentriert ist.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformieren Sie Bilder einfach in ihre Graustufen‑Darstellung, wodurch die visuelle Analyse und Verarbeitung vereinfacht wird. Perfekt für Entwickler, die die Bildklarheit verbessern, die Komplexität reduzieren und effiziente Graustufen‑Algorithmen für verschiedene Anwendungen ermöglichen möchten.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
Das folgende Beispiel wandelt ein farbiges DICOM‑Bild in seine Graustufen‑Darstellung um. Graustufenbilder bestehen ausschließlich aus Grautönen und enthalten nur Intensitätsinformationen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Verbessern Sie die Bildqualität und passen Sie sie mit der Gammakorrektur an, einer leistungsstarken Technik zur Feinabstimmung des visuellen Erscheinungsbildes. Perfekt für Entwickler, die die Bilddarstellung optimieren, das Farbgleichgewicht anpassen und ein konsistentes Rendering auf verschiedenen Geräten und in unterschiedlichen Umgebungen sicherstellen möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma für Rot-, Grün- und Blaukanäle-Koeffizient |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Setzen Sie den Gamma-Koeffizienten für Rot-, Grün- und Blaukanäle.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Erreichen Sie präzise Farbanpassungen, indem Sie die Gammakorrektur unabhängig auf die Rot‑, Grün‑ und Blau‑Komponenten eines Bildes anwenden. Diese Methode gewährleistet ein genaues Farbgleichgewicht und optimale visuelle Ergebnisse und richtet sich an Entwickler, die eine feine Kontrolle über Bildrendering und Farbgenauigkeit benötigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gammaRed | float | Gamma‑Koeffizient für den Rotkanal |
| gammaGreen | float | Gamma‑Koeffizient für den Grünkanal |
| gammaBlue | float | Gamma für den Blaukanal-Koeffizienten |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Setzen Sie individuelle Gamma-Koeffizienten für die Rot-, Grün- und Blaukanäle.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Verbessern Sie die Bildhelligkeit durch die Anpassung von `brightness`, einer parametrisierten Methode, die Entwicklern ermöglicht, die Leuchtkraft von Bildern fein abzustimmen. Diese benutzerfreundliche Funktion befähigt Entwickler, die Bildhelligkeit nahtlos zu manipulieren und bietet Flexibilität und Kontrolle über die visuelle Ästhetik.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Legen Sie den Helligkeitswert fest. Die zulässigen Helligkeitswerte liegen im Bereich [-255, 255].
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Verbessern Sie den Kontrast von [Image](../../com.aspose.imaging/image) mit dieser benutzerfreundlichen Methode, die den Unterschied zwischen hellen und dunklen Bereichen anpasst. Verbessern Sie mühelos die visuelle Klarheit und Definition und geben Sie Entwicklern eine intuitive Kontrolle über den Bildkontrast für ein optimales Rendering.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | float | Kontrastwert (im Bereich [-100; 100]) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Legen Sie den Kontrastwert fest. Die zulässigen Kontrastwerte liegen im Bereich [-100f, 100f].
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Verbessern Sie mühelos bestimmte Bereiche Ihres Bildes, indem Sie Filter auf festgelegte Rechtecke anwenden. Diese Methode bietet Entwicklern eine präzise Kontrolle über die Bildbearbeitung und ermöglicht gezielte Anpassungen, um gewünschte visuelle Effekte einfach zu erzielen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Die Optionen. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Wenden Sie einen Gaußschen Weichzeichner mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Wenden Sie einen Gauss-Wiener-Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Passen Sie die Größe Ihres Bildes mit dieser einfachen Skalierungsmethode an. Egal, ob Sie Ihr Bild verkleinern oder vergrößern müssen, diese Funktion stellt sicher, dass Ihre Skalierungsanforderungen effizient und exakt erfüllt werden, und ist damit ideal für Entwickler, die schnelle und einfache Bildgrößenanpassungen suchen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Der adaptive Algorithmus basierend auf gewichteter und gemischter rationaler Funktion sowie Lanczos‑3‑Interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Der kleine rechteckige Filter
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Die Anzahl der Farben in der Palette.
resizeSettings.setEntriesCount(256);

// Die Farbquantisierung wird nicht verwendet
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Die euklidische Methode
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Verkleinern Sie um das 2‑fache mittels adaptiver Resampling.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Als PNG speichern
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Diese Methode cached Daten effizient, optimiert die Leistung und gewährleistet bei Bedarf schnellen Zugriff. Ideal für Entwickler, die die Geschwindigkeit und Effizienz ihrer Anwendungen durch intelligentes Datenmanagement verbessern möchten.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// Laden Sie ein Bild aus einer DICOM‑Datei.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Dieser Aufruf zwischenspeichert alle Seiten, sodass kein zusätzliches Laden von Daten aus dem zugrunde liegenden Datenstrom durchgeführt wird.
    image.cacheData();

    // Oder Sie können die Seiten einzeln zwischenspeichern.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

