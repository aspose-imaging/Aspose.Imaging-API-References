---
title: "SvgImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Verwalten Sie Scalar Vector Graphics SVG-Bilddateien mit unserer API, die die Leistungsfähigkeit des XML-basierten Textformats für nahtlose Anpassung und Skalierbarkeit nutzt."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

Verwalten Sie Scalar Vector Graphics (SVG)-Bilddateien mit unserer API, die die Leistungsfähigkeit des XML‑basierten Textformats für nahtlose Anpassung und Skalierbarkeit nutzt. Laden Sie SVG‑Bilder einfach, rasterisieren Sie Vektorelemente und konvertieren Sie sie in andere Formate, während Sie die Komprimierungsstufen steuern, um Dateigröße und Qualität für Ihre Projekte zu optimieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Instanziiert ein neues Objekt der [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Klasse und verwendet den angegebenen Pfad, um das Bild zu finden und zu laden. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Erstellt eine neue Instanz der [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Klasse und lädt das Bild aus dem bereitgestellten Stream. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Instanziiert ein neues [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Objekt mit der angegebenen Breite und Höhe. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Erstellt eine neue Instanz der [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Klasse mit angegebenen SVG-Optionen, Bildbreite und Höhenparametern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isCached()](#isCached--) | Gibt einen booleschen Wert zurück, der angibt, ob die Daten des Objekts derzeit im Cache sind, wodurch zusätzliche Lesevorgänge entfallen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gibt die Bits‑pro‑Pixel‑Anzahl des Bildes zurück. |
| [getFileFormat()](#getFileFormat--) | Gibt das Dateiformat des Bildes zurück und liefert wichtige Metadaten für die Verarbeitung und Kompatibilitätsprüfungen. |
| [cacheData()](#cacheData--) | Cache die Daten und stelle sicher, dass keine weiteren Daten aus dem zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) geladen werden. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Skaliere das Bild, um die angegebenen Abmessungen zu erfüllen, wobei das Seitenverhältnis beibehalten wird. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet das angegebene Rechteck zu. |
| [rotate(float angle)](#rotate-float-) | Bild um die Mitte drehen. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Wendet eine angegebene Palette auf das Bild an, um Farbschemata für ästhetische oder funktionale Zwecke anzupassen. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Lade ein SVG-Bild aus einem Dateistream.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // Um SVG zu rasterisieren, müssen wir Rasterisierungsoptionen angeben.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
Das folgende Beispiel zeigt, wie komprimierte Bilder (*.emz, *.wmz, *.svgz) in ein Rasterformat konvertiert werden.
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Instanziiert ein neues Objekt der [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Klasse und verwendet den angegebenen Pfad, um das Bild zu finden und zu laden. Dieser Konstruktor erleichtert die Erstellung von SVG-Bildinstanzen aus externen Dateien und ermöglicht eine nahtlose Integration in Softwaresysteme und Workflows.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Erstellt eine neue Instanz der [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Klasse und lädt das Bild aus dem bereitgestellten Stream. Dieser Konstruktor ermöglicht das direkte Laden von SVG-Bildern aus Streams und erhöht die Flexibilität und Effizienz beim Umgang mit Bildressourcen in Softwareanwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Instanziiert ein neues [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Objekt mit der angegebenen Breite und Höhe. Dieser Konstruktor ermöglicht Entwicklern, SVG-Bilder mit vordefinierten Abmessungen zu erstellen, wodurch eine präzise Kontrolle über die Bildgröße während der Initialisierung erleichtert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Erstellt eine neue Instanz der [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)-Klasse mit angegebenen SVG-Optionen, Bildbreite und Höhenparametern. Dieser Konstruktor ermöglicht Entwicklern, SVG-Bilder mit benutzerdefinierten Optionen und Abmessungen zu initialisieren und bietet Flexibilität bei der Verwaltung von SVG-Inhalten und -Layout.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | Die SVG-Optionen. |
| Breite | int | Bildbreite. |
| Höhe | int | Bildhöhe. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Ruft einen booleschen Wert ab, der angibt, ob die Daten des Objekts derzeit im Cache gespeichert sind, wodurch zusätzliche Lesevorgänge entfallen. Diese Eigenschaft liefert Einblick in den aktuellen Cache-Status und optimiert Datenabruf- und Verarbeitungsabläufe für verbesserte Leistung und Effizienz.

**Returns:**
boolean – `true`, wenn die Daten des Objekts im Cache sind; andernfalls `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ruft die Bit‑pro‑Pixel‑Anzahl des Bildes ab. Es ist wichtig zu beachten, dass dieser Parameter nicht für Vektorbilder gilt, da sie nicht in Pixeln gemessen werden. Diese Eigenschaft liefert entscheidende Informationen über die Farbtiefe des Bildes und unterstützt bei Verarbeitungs‑ und Manipulationsaufgaben.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ruft das Dateiformat des Bildes ab und liefert wichtige Metadaten für die Verarbeitung und Kompatibilitätsprüfungen. Diese Eigenschaft ist entscheidend, um die geeigneten Dekodierungs‑ und Kodierungsstrategien für die effektive Handhabung der Bilddaten in verschiedenen Systemen und Anwendungen zu bestimmen.

**Returns:**
long - Dateiformat
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache die Daten und stelle sicher, dass keine weiteren Daten aus dem zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) geladen werden. Diese Optimierung verbessert die Leistung, indem redundante Datenabrufvorgänge eliminiert werden, was insbesondere in Szenarien vorteilhaft ist, die häufigen Zugriff auf die Bilddaten erfordern.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Skaliere das Bild, um die angegebenen Abmessungen zu erfüllen, wobei das Seitenverhältnis beibehalten wird. Diese Methode bietet eine bequeme Möglichkeit, die Bildgröße anzupassen, ohne die Proportionen zu verzerren, und sorgt für optimale Anzeige oder Speicherung gemäß den gewünschten Abmessungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Schneidet das angegebene Rechteck zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Bild um die Mitte drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Wendet eine angegebene Palette auf das Bild an, wodurch die Anpassung von Farbschemata für ästhetische oder funktionale Zwecke ermöglicht wird. Diese Methode bietet Flexibilität bei der Verwaltung von Farbpaletten, um verschiedenen Design‑ oder Anforderungsprofilen gerecht zu werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

