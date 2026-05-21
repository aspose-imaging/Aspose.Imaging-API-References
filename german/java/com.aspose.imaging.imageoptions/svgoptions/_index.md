---
title: "SvgOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstellen Sie Scalar Vector Graphics SVG-Bilddateien mit unserer API, die vielseitige Optionen für Farbtypen und Komprimierungsstufen nutzt."
type: docs
weight: 45
url: /de/java/com.aspose.imaging.imageoptions/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public class SvgOptions extends ImageOptionsBase implements ICompressOptions
```

Erstellen Sie Scalar Vector Graphics (SVG)-Bilddateien mit unserer API, die vielseitige Optionen für Farbtypen und Komprimierungsstufen nutzt. Passen Sie Ihre SVG-Bilder nahtlos mit Präzision an und stellen Sie optimale Qualität und Kompatibilität für Ihre Designanforderungen sicher.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgOptions()](#SvgOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorType()](#getColorType--) | Ruft den Farbtyp für das SVG-Bild ab oder legt ihn fest. |
| [setColorType(int value)](#setColorType-int-) | Ruft den Farbtyp für das SVG-Bild ab oder legt ihn fest. |
| [getTextAsShapes()](#getTextAsShapes--) | Gibt einen Wert zurück, der angibt, ob Text als Formen gerendert werden muss. |
| [setTextAsShapes(boolean value)](#setTextAsShapes-boolean-) | Legt einen Wert fest, der angibt, ob Text als Formen gerendert werden muss. |
| [getCallback()](#getCallback--) | Gibt die Speicherstrategie für eingebettete Ressourcen von [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) wie Schriftarten, verschachtelte Raster zurück. |
| [setCallback(ISvgResourceKeeperCallback value)](#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-) | Legt die Speicherstrategie für eingebettete Ressourcen von [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) wie Schriftarten, verschachtelte Raster fest. |
| [getCompress()](#getCompress--) | Ruft einen Wert ab, der angibt, ob das Ausgabebild komprimiert werden muss. |
| [setCompress(boolean value)](#setCompress-boolean-) | Legt einen Wert fest, der angibt, ob das Ausgabebild komprimiert werden muss. |

## Example: The following example shows how to convert a multipage vector image to SVG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.svg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.SvgOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportiere nur die ersten beiden Seiten. Tatsächlich wird nur eine Seite konvertiert, weil SVG kein Mehrseitiges Format ist.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
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

### SvgOptions() {#SvgOptions--}
```
public SvgOptions()
```


### getColorType() {#getColorType--}
```
public int getColorType()
```


Ruft den Farbtyp für das SVG-Bild ab oder legt ihn fest.

**Returns:**
int - Der Typ der Farbe des SVG-Bildes.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ruft den Farbtyp für das SVG-Bild ab oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Typ der Farbe des SVG-Bildes. |

### getTextAsShapes() {#getTextAsShapes--}
```
public boolean getTextAsShapes()
```


Gibt einen Wert zurück, der angibt, ob Text als Formen gerendert werden muss.

Wert: `true`, wenn im Konvertierungsvorgang aller Text in SVG‑Formen umgewandelt wird; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob Text als Formen gerendert werden muss.
### setTextAsShapes(boolean value) {#setTextAsShapes-boolean-}
```
public void setTextAsShapes(boolean value)
```


Legt einen Wert fest, der angibt, ob Text als Formen gerendert werden muss.

Wert: `true`, wenn im Konvertierungsvorgang aller Text in SVG‑Formen umgewandelt wird; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob Text als Formen gerendert werden muss. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen, einschließlich WMF, zu laden.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text wird in Formen konvertiert.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Die Seitengröße.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Wenn ein eingebettetes EMF vorhanden ist, wird EMF gerendert; andernfalls wird WMF gerendert.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen einschließlich EMF zu laden.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text wird in Formen konvertiert.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Die Seitengröße.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Wenn ein eingebettetes EMF vorhanden ist, wird EMF gerendert; andernfalls wird WMF gerendert.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Setzen Sie den horizontalen Rand
    rasterizationOptions.setBorderX(50);

    // Setzen Sie den vertikalen Rand
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getCallback() {#getCallback--}
```
public ISvgResourceKeeperCallback getCallback()
```


Gibt die Speicherstrategie für eingebettete Ressourcen von [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) wie Schriftarten, verschachtelte Raster zurück.

**Returns:**
[ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) - the storing strategy for embedded resources of [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) such as fonts, nested rasters.
### setCallback(ISvgResourceKeeperCallback value) {#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-}
```
public void setCallback(ISvgResourceKeeperCallback value)
```


Legt die Speicherstrategie für eingebettete Ressourcen von [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) wie Schriftarten, verschachtelte Raster fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) | die Speicherstrategie für eingebettete Ressourcen von [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) wie Schriftarten, verschachtelte Raster. |

### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Ruft einen Wert ab, der angibt, ob das Ausgabebild komprimiert werden muss.

**Returns:**
boolean - ein Wert, der angibt, ob das Ausgabebild komprimiert werden muss.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Legt einen Wert fest, der angibt, ob das Ausgabebild komprimiert werden muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob das Ausgabebild komprimiert werden muss. |


**Example: The following example shows how to convert a svg images to svgz format**

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

