---
title: "JpegImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Manipulieren Sie JPEG-Rasterbilder effizient mit unserer API, die Unterstützung für verschiedene Farbprofile wie RGB und CMYK, anpassbare Bits‑pro‑Pixel‑Auflösung und die Verarbeitung von EXIF-, JFIF- und XMP-Metadatencontainern bietet."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

Manipulieren Sie JPEG-Rasterbilder effizient mit unserer API, die Unterstützung für verschiedene Farbprofile wie RGB und CMYK, anpassbare Bits‑pro‑Pixel‑Auflösung und die Verarbeitung von EXIF-, JFIF- und XMP-Metadatencontainern bietet. Nutzen Sie die automatische Drehung basierend auf Orientierungsdaten und wählen Sie aus verschiedenen Kompressionsstufen, einschließlich verlustfreiem JPEG, um für Ihre Projekte ein optimales Gleichgewicht zwischen Bildqualität und Dateigröße zu erreichen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | Die [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Klasse wird mühelos initiiert, indem ihr Konstruktor mit dem angegebenen Pfadparameter aufgerufen wird. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Initialisieren Sie ein JPEG-Bildobjekt mit der [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Klasse unter Verwendung eines Stream-Parameters. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Initialisieren Sie eine neue Instanz der [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Klasse mit einem Rasterbild-Parameter. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Erstellen Sie eine neue Instanz der [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Klasse mit den angegebenen Breiten- und Höhenparametern. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Initialisieren Sie ein neues [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Objekt mit den bereitgestellten JPEG-Optionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Rufen Sie das Format des Bildes mühelos über diese Eigenschaft ab. |
| [getJpegOptions()](#getJpegOptions--) | Erhalten Sie einfachen Zugriff auf die JPEG-Optionen, die beim Erstellen oder Laden dieser [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Instanz verwendet werden. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Rufen Sie die Pixeltiefe des Bildes mühelos über diese Eigenschaft ab, um Einblicke in die Farbreichtum- oder Graustufen‑Darstellung zu erhalten. |
| [getComment()](#getComment--) | Verwalten Sie JPEG-Dateikommentare mit dieser Eigenschaft, sodass Sie beschreibende Anmerkungen zum Bild hinzufügen oder abrufen können. |
| [setComment(String value)](#setComment-java.lang.String-) | Verwalten Sie JPEG-Dateikommentare mit dieser Eigenschaft, sodass Sie beschreibende Anmerkungen zum Bild hinzufügen oder abrufen können. |
| [getJpegExifData()](#getJpegExifData--) | Liefert die Exif‑Instanz. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Verwalten Sie EXIF‑Daten mit dieser Eigenschaft, um Metadaten zum Bild hinzuzufügen oder abzurufen. |
| [getExifData()](#getExifData--) | Liefert Exif‑Daten; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Setzt Exif‑Daten; |
| [getHeight()](#getHeight--) | Rufen Sie mühelos die Höhe des Bildes mit dieser Eigenschaft ab. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Diese Eigenschaft gewährt Zugriff auf die horizontale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Diese Eigenschaft gewährt Zugriff auf die horizontale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll. |
| [getJfif()](#getJfif--) | Diese Eigenschaft ermöglicht den Zugriff auf oder die Änderung der JFIF‑Daten (JPEG File Interchange Format), die dem JPEG‑Bild zugeordnet sind. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Diese Eigenschaft ermöglicht den Zugriff auf oder die Änderung der JFIF‑Daten (JPEG File Interchange Format), die dem JPEG‑Bild zugeordnet sind. |
| [getRawDataFormat()](#getRawDataFormat--) | Diese Eigenschaft ruft das Rohdatenformat des Bildes ab, das angibt, wie die Bilddaten strukturiert und kodiert sind. |
| [getVerticalResolution()](#getVerticalResolution--) | Diese Eigenschaft verwaltet die vertikale Auflösung, ausgedrückt in Pixel pro Zoll, für das zugehörige [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Diese Eigenschaft verwaltet die vertikale Auflösung, ausgedrückt in Pixel pro Zoll, für das zugehörige [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getWidth()](#getWidth--) | Diese Eigenschaft ruft die Breite des Bildes ab, angegeben in Pixeln. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Das RGB‑Farbprofil für CMYK‑ und YCCK‑JPEG‑Bilder sorgt für eine genaue Farbumwandlung und -darstellung. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Das RGB‑Farbprofil für CMYK‑ und YCCK‑JPEG‑Bilder sorgt für eine genaue Farbumwandlung und -darstellung. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Das mit CMYK‑ und YCCK‑JPEG‑Bildern verbundene CMYK‑Farbprofil gewährleistet eine präzise Farbumwandlung und Treue. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Das mit CMYK‑ und YCCK‑JPEG‑Bildern verbundene CMYK‑Farbprofil gewährleistet eine präzise Farbumwandlung und Treue. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | Das RGBColorProfile ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses unerlässlich. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Das RGBColorProfile ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses unerlässlich. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | Das CMYK‑Farbprofil ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses entscheidend. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Das CMYK‑Farbprofil ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses entscheidend. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Ruft das Flag ab oder ändert es, das angibt, ob das eingebettete Farbprofil ignoriert wird. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Ruft das Flag ab oder ändert es, das angibt, ob das eingebettete Farbprofil ignoriert wird. |
| [getOriginalOptions()](#getOriginalOptions--) | Liefert die ursprünglichen Bildoptionen dieser [Image](../../com.aspose.imaging/image)-Instanz. |
| [removeMetadata()](#removeMetadata--) | Entfernt die Metadaten dieser Bildinstanz, indem die Werte `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) und `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) auf `null` gesetzt. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Legt die Auflösung für das angegebene [RasterImage](../../com.aspose.imaging/rasterimage) fest und gewährleistet genaue Skalierungs‑ und Druckfähigkeiten. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Laden Sie ein JPEG‑Bild aus einer Datei.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Führe einige Bildverarbeitungen durch.
    // Speichern Sie in einer anderen JPEG‑Datei.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


Die [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) Klasse wird mühelos initiiert, indem ihr Konstruktor mit dem angegebenen Pfadparameter aufgerufen wird. Dieser Konstruktor ermöglicht die nahtlose Erstellung von JPEG‑Bildern und sorgt für eine schnelle Integration in Ihre Projekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Initialisieren Sie ein JPEG‑Bildobjekt mit der [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)‑Klasse unter Verwendung eines Stream‑Parameters. Dieser Konstruktor vereinfacht die Arbeit mit JPEG‑Bildern und bietet einen unkomplizierten Ansatz, um sie mühelos in Ihre Projekte zu integrieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Initialisieren Sie eine neue Instanz der [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Klasse mit einem Rasterbild-Parameter. Dieser Konstruktor bietet eine bequeme Möglichkeit, JPEG‑Bilder direkt aus Rasterbildern zu erstellen und optimiert den Arbeitsablauf für die Arbeit mit JPEG‑Bildern in Ihren Anwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Pixel‑ und Palettendaten initialisiert werden sollen. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Erstellen Sie eine neue Instanz der [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Klasse mit den angegebenen Breiten‑ und Höhenparametern. Dieser Konstruktor ermöglicht es Ihnen, JPEG‑Bilder mit benutzerdefinierten Abmessungen zu erzeugen und bietet Ihnen Flexibilität bei der Verwaltung der Bildgrößen in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Initialisieren Sie ein neues [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Objekt mit den bereitgestellten JPEG‑Optionen. Dieser Konstruktor befähigt Sie, verschiedene Einstellungen für das JPEG‑Bild anzupassen, wie Kompressionsgrad, Qualität und weitere Parameter, und gewährt präzise Kontrolle über das resultierende Bildformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Die JPEG‑Optionen. |
| Breite | int | Bildbreite. |
| Höhe | int | Bildhöhe. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie das Format des Bildes mühelos über diese Eigenschaft ab. Sie liefert wertvolle Einblicke in das Dateiformat und unterstützt nahtlose Integration sowie Kompatibilitätsprüfungen über verschiedene Plattformen und Anwendungen hinweg.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Erhalten Sie einfachen Zugriff auf die während der Erstellung oder des Ladens dieser [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage)-Instanz verwendeten JPEG‑Optionen. Diese Eigenschaft liefert wertvolle Details zu den eingesetzten Einstellungen und befähigt Benutzer, Bildverarbeitungs‑Workflows effektiv zu verstehen und nachzuvollziehen. Ob Kompressionsstufen, Qualitätseinstellungen oder andere Parameter – diese Eigenschaft bietet wesentliche Einblicke für eine nahtlose Bildmanipulation.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//Die Ausgabe sieht folgendermaßen aus:
//Die Anzahl der Bits pro Kanal: 8
//Die maximal zulässige Größe für alle internen Puffer: 0
//Der Farbtyp: YCbCr
//Der Kompressionstyp: Baseline
//Die Bildqualität: 75
//Die Abtastung für Komponente 0: 1x1
//Die Abtastung für Komponente 1: 1x1
//Die Abtastung für Komponente 2: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Rufen Sie die Pixeltiefe des Bildes mühelos über diese Eigenschaft ab, um Einblicke in die Farbreichtum‑ oder Graustufen‑Darstellung zu erhalten. Ob es sich um ein lebendiges Foto oder eine monochrome Illustration handelt, diese Eigenschaft liefert entscheidende Informationen über die visuelle Komplexität des Bildes.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getComment() {#getComment--}
```
public String getComment()
```


Verwalten Sie JPEG‑Dateikommentare mit dieser Eigenschaft, die es Ihnen ermöglicht, beschreibende Anmerkungen zum Bild hinzuzufügen oder abzurufen. Ob Sie Bilder mit Metadaten versehen oder zusätzlichen Kontext anhängen – diese Eigenschaft bietet Flexibilität beim Organisieren und Kategorisieren Ihrer JPEG‑Dateien.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Verwalten Sie JPEG‑Dateikommentare mit dieser Eigenschaft, die es Ihnen ermöglicht, beschreibende Anmerkungen zum Bild hinzuzufügen oder abzurufen. Ob Sie Bilder mit Metadaten versehen oder zusätzlichen Kontext anhängen – diese Eigenschaft bietet Flexibilität beim Organisieren und Kategorisieren Ihrer JPEG‑Dateien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Liefert die Exif‑Instanz.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Verwalten Sie EXIF‑Daten mit dieser Eigenschaft, die es Ihnen ermöglicht, Metadaten zum Bild hinzuzufügen oder abzurufen. Ob Sie Informationen zu den Kameraeinstellungen extrahieren oder vorhandene Metadaten ändern – diese Eigenschaft bietet Flexibilität bei der Verwaltung des EXIF‑Datencontainers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Liefert Exif‑Daten;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//Die Ausgabe sieht folgendermaßen aus:
//Die allgemeinen EXIF‑Daten
//------------------------------------------
//Die EXIF‑Version: [B@163e4e87
//Die Kameraseriennummer: 7100536
//Der Farbraum: SRgb
//Die Helligkeit:
//Der Kontrast: Normal
//Das Gamma:
//Die Schärfe: 0
//Die Blende: 4.64(4643856 / 1000000)
//Der Belichtungsmodus: Manuell
//Die Belichtungskorrektur: 0.67(4 / 6)
//Die Belichtungszeit: 0.01(1 / 160)
//Die Brennweite: 145.00(1450 / 10)
//Die Auflösungseinheit der Bildebene: Cm
//Das Objektivmodell: 70.0 - 200.0 mm f/ 4.0
//Die Verschlusszeit: 7.32(7321928 / 1000000)
//Die JPEG EXIF-Daten
//------------------------------------------
//Der Kamerahersteller: NIKON CORPORATION
//Das Kameramodell: NIKON D5
//Die photometrische Interpretation: 0
//Der Künstler:
//Das Urheberrecht:
//Die Bildbeschreibung:
//Die Ausrichtung: TopLeft
//Die Software: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Setzt Exif‑Daten;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif-Daten; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Rufen Sie die Höhe des Bildes mühelos mit dieser Eigenschaft ab. Sie bietet schnellen Zugriff auf die vertikale Dimension des Bildes, sodass Sie seine Größe und das Seitenverhältnis effizient bestimmen können, ohne komplexe Berechnungen oder zusätzliche Methoden durchführen zu müssen.

**Returns:**
int - Die Bildhöhe in Pixeln.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Diese Eigenschaft gewährt Ihnen Zugriff auf die horizontale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll. Durch das Setzen oder Abrufen dieses Wertes können Sie die Auflösung des Bildes präzise steuern und sicherstellen, dass sie Ihren spezifischen Anforderungen an Qualität und Klarheit entspricht.

**Returns:**
double - Die horizontale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Horizontale und vertikale Auflösung des BmpImage abrufen
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 300.0
// Die vertikale Auflösung, in Pixel pro Zoll: 300.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 96.0
// Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Diese Eigenschaft gewährt Ihnen Zugriff auf die horizontale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll. Durch das Setzen oder Abrufen dieses Wertes können Sie die Auflösung des Bildes präzise steuern und sicherstellen, dass sie Ihren spezifischen Anforderungen an Qualität und Klarheit entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die horizontale Auflösung. |

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie könnten in Erwägung ziehen, die `setResolution`-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Diese Eigenschaft ermöglicht Ihnen den Zugriff auf oder die Änderung der JFIF (JPEG File Interchange Format)-Daten, die mit dem JPEG-Bild verknüpft sind. JFIF ist ein Standardformat zum Austausch von JPEG-komprimierten Bildern zwischen Computern und anderen Geräten. Durch das Abrufen oder Setzen dieser Eigenschaft können Sie mit den JFIF-Daten interagieren, die Informationen wie die Auflösung des Bildes, das Seitenverhältnis und das Vorschaubild enthalten können.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Diese Eigenschaft ermöglicht Ihnen den Zugriff auf oder die Änderung der JFIF (JPEG File Interchange Format)-Daten, die mit dem JPEG-Bild verknüpft sind. JFIF ist ein Standardformat zum Austausch von JPEG-komprimierten Bildern zwischen Computern und anderen Geräten. Durch das Abrufen oder Setzen dieser Eigenschaft können Sie mit den JFIF-Daten interagieren, die Informationen wie die Auflösung des Bildes, das Seitenverhältnis und das Vorschaubild enthalten können.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Diese Eigenschaft ruft das Rohdatenformat des Bildes ab, das angibt, wie die Bilddaten strukturiert und codiert sind. Das Verständnis des Rohdatenformats ist entscheidend für die effektive Verarbeitung oder Manipulation der Bilddaten. Es liefert Einblicke in die zugrunde liegende Darstellung des Bildes, etwa ob es komprimiert, in einem bestimmten Farbraum codiert oder in einem bestimmten Dateiformat gespeichert ist. Der Zugriff auf diese Eigenschaft ermöglicht Ihnen wertvolle Informationen über die Datenstruktur des Bildes zu erhalten, sodass Sie verschiedene Operationen oder Optimierungen durchführen können, die speziell auf sein Format zugeschnitten sind.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Diese Eigenschaft verwaltet die vertikale Auflösung, ausgedrückt in Pixel pro Zoll, für das zugehörige [RasterImage](../../com.aspose.imaging/rasterimage). Die Anpassung dieser Auflösung wirkt sich auf Größe und Qualität des Bildes aus, wenn es bei einer festen physischen Größe gedruckt oder angezeigt wird. Durch das Setzen dieser Eigenschaft steuern Sie, wie dicht die Pixel des Bildes vertikal angeordnet sind, was die Gesamtschärfe und Klarheit beeinflusst.

**Returns:**
double - Die vertikale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 72, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution‑Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Horizontale und vertikale Auflösung des BmpImage abrufen
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 300.0
// Die vertikale Auflösung, in Pixel pro Zoll: 300.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 96.0
// Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Diese Eigenschaft verwaltet die vertikale Auflösung, ausgedrückt in Pixel pro Zoll, für das zugehörige [RasterImage](../../com.aspose.imaging/rasterimage). Die Anpassung dieser Auflösung wirkt sich auf Größe und Qualität des Bildes aus, wenn es bei einer festen physischen Größe gedruckt oder angezeigt wird. Durch das Setzen dieser Eigenschaft steuern Sie, wie dicht die Pixel des Bildes vertikal angeordnet sind, was die Gesamtschärfe und Klarheit beeinflusst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die vertikale Auflösung. |

Hinweis: Standardmäßig hat dieser Wert immer 72, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution‑Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Diese Eigenschaft gibt die Breite des Bildes in Pixeln zurück. Sie liefert wesentliche Informationen über die Bildabmessungen und ermöglicht eine genaue Darstellung, Manipulation oder Anzeige der Bilddaten.

**Returns:**
int - Die Bildbreite in Pixeln.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Das RGB‑Farbprofil für CMYK‑ und YCCK‑JPEG‑Bilder sorgt für eine genaue Farbumwandlung und -darstellung. Es muss mit dem **CMYKColorProfile** kombiniert werden, um Konsistenz und Treue bei der Farbdarstellung zu gewährleisten. Diese Kombination ist für Anwendungen, die ein präzises Farbmanagement und die Reproduktion von Bildern erfordern, unerlässlich, damit die RGB‑Daten korrekt interpretiert und angezeigt werden.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Das RGB‑Farbprofil für CMYK‑ und YCCK‑JPEG‑Bilder sorgt für eine genaue Farbumwandlung und -darstellung. Es muss mit dem **CMYKColorProfile** kombiniert werden, um Konsistenz und Treue bei der Farbdarstellung zu gewährleisten. Diese Kombination ist für Anwendungen, die ein präzises Farbmanagement und die Reproduktion von Bildern erfordern, unerlässlich, damit die RGB‑Daten korrekt interpretiert und angezeigt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Das folgende Beispiel lädt ein PNG und speichert es als CMYK‑JPEG unter Verwendung eines benutzerdefinierten ICC‑Profils. Anschließend wird das CMYK‑JPEG geladen und wieder als PNG gespeichert. Die Farbumwandlung von RGB zu CMYK und von CMYK zu RGB erfolgt mithilfe benutzerdefinierter ICC‑Profile.
``` java
String dir = "c:\\temp\\";

// PNG laden und als CMYK‑JPEG speichern
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Benutzerdefinierte ICC‑Profile verwenden
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// CMYK‑JPEG laden und als PNG speichern
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Benutzerdefinierte ICC‑Profile verwenden
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Das mit CMYK‑ und YCCK‑JPEG‑Bildern verbundene CMYK‑Farbprofil gewährleistet eine präzise Farbumwandlung und Treue. Es arbeitet zusammen mit dem **RGBColorProfile**, um eine genaue Farbdarstellung über verschiedene Geräte und Anwendungen hinweg zu garantieren. Diese Kombination ist entscheidend, um Konsistenz bei der Farbdarstellung zu wahren und eine optimale Bildqualität zu erreichen.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Das mit CMYK‑ und YCCK‑JPEG‑Bildern verbundene CMYK‑Farbprofil gewährleistet eine präzise Farbumwandlung und Treue. Es arbeitet zusammen mit dem **RGBColorProfile**, um eine genaue Farbdarstellung über verschiedene Geräte und Anwendungen hinweg zu garantieren. Diese Kombination ist entscheidend, um Konsistenz bei der Farbdarstellung zu wahren und eine optimale Bildqualität zu erreichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Das folgende Beispiel lädt ein PNG und speichert es als CMYK‑JPEG unter Verwendung eines benutzerdefinierten ICC‑Profils. Anschließend wird das CMYK‑JPEG geladen und wieder als PNG gespeichert. Die Farbumwandlung von RGB zu CMYK und von CMYK zu RGB erfolgt mithilfe benutzerdefinierter ICC‑Profile.
``` java
String dir = "c:\\temp\\";

// PNG laden und als CMYK‑JPEG speichern
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Benutzerdefinierte ICC‑Profile verwenden
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// CMYK‑JPEG laden und als PNG speichern
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Benutzerdefinierte ICC‑Profile verwenden
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


Das **RGBColorProfile** ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses unerlässlich. In Kombination mit dem **CMYKColorProfile** stellt es sicher, dass die Farben korrekt wiedergegeben werden und bewahrt die Konsistenz über verschiedene Geräte und Anwendungen hinweg. Diese Kombination ist entscheidend, um die beabsichtigte Farbdarstellung zu erhalten und hochwertige Bildeausgaben zu erzielen.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


Das **RGBColorProfile** ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses unerlässlich. In Kombination mit dem **CMYKColorProfile** stellt es sicher, dass die Farben korrekt wiedergegeben werden und bewahrt die Konsistenz über verschiedene Geräte und Anwendungen hinweg. Diese Kombination ist entscheidend, um die beabsichtigte Farbdarstellung zu erhalten und hochwertige Bildeausgaben zu erzielen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


Das CMYK‑Farbprofil ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses von entscheidender Bedeutung. Es arbeitet Hand in Hand mit dem **RGBColorProfile**, um eine korrekte Farbdarstellung zu gewährleisten und Konsistenz sowie Qualität über verschiedene Geräte und Software hinweg zu erhalten. Diese Synchronisation ist wesentlich, um eine genaue und zuverlässige Farbdarstellung in den final gespeicherten Bildern zu erreichen.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


Das CMYK‑Farbprofil ist für die genaue Farbumwandlung von CMYK‑ und YCCK‑JPEG‑Bildern während des Speicherprozesses von entscheidender Bedeutung. Es arbeitet Hand in Hand mit dem **RGBColorProfile**, um eine korrekte Farbdarstellung zu gewährleisten und Konsistenz sowie Qualität über verschiedene Geräte und Software hinweg zu erhalten. Diese Synchronisation ist wesentlich, um eine genaue und zuverlässige Farbdarstellung in den final gespeicherten Bildern zu erreichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Ruft das Flag ab oder ändert es, das angibt, ob das eingebettete Farbprofil ignoriert wird. Durch Setzen dieses Flags können Benutzer festlegen, ob das Standard‑Farbprofil anstelle des eingebetteten verwendet werden soll. Diese Option bietet mehr Kontrolle über das Farbmanagement und erleichtert Anpassungen für Konsistenz und Kompatibilität über verschiedene Plattformen und Anwendungen hinweg.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Ruft das Flag ab oder ändert es, das angibt, ob das eingebettete Farbprofil ignoriert wird. Durch Setzen dieses Flags können Benutzer festlegen, ob das Standard‑Farbprofil anstelle des eingebetteten verwendet werden soll. Diese Option bietet mehr Kontrolle über das Farbmanagement und erleichtert Anpassungen für Konsistenz und Kompatibilität über verschiedene Plattformen und Anwendungen hinweg.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Liefert die ursprünglichen Bildoptionen dieser [Image](../../com.aspose.imaging/image)-Instanz.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Entfernt die Metadaten dieser Bildinstanz, indem die Werte `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) und `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) auf `null` gesetzt.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Legt die Auflösung für das angegebene [RasterImage](../../com.aspose.imaging/rasterimage) fest und sorgt für genaue Skalierungs‑ und Druckfähigkeiten. Diese Methode ermöglicht es Benutzern, die Bildauflösung an ihre spezifischen Anforderungen anzupassen, sei es für digitale Anzeige oder physische Reproduktion. Durch das Festlegen der Auflösung können Benutzer die Bildqualität optimieren und die Kompatibilität mit verschiedenen Ausgabegeräten und Medien sicherstellen, wodurch das gesamte visuelle Erlebnis und die Nutzbarkeit des Bildes verbessert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | double | Die horizontale Auflösung in Punkten pro Zoll des `RasterImage`. |
| dpiY | double | Die vertikale Auflösung in Punkten pro Zoll des `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Horizontale und vertikale Auflösung des BmpImage abrufen
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 300.0
// Die vertikale Auflösung, in Pixel pro Zoll: 300.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 96.0
// Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

