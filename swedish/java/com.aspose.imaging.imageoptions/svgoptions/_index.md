---
title: "SvgOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa Scalar Vector Graphics SVG-bildfiler med vårt API som utnyttjar mångsidiga alternativ för färgtyper och komprimeringsnivåer."
type: docs
weight: 45
url: /sv/java/com.aspose.imaging.imageoptions/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public class SvgOptions extends ImageOptionsBase implements ICompressOptions
```

Skapa Scalar Vector Graphics (SVG) bildfiler med vårt API, som utnyttjar mångsidiga alternativ för färgtyper och komprimeringsnivåer. Anpassa dina SVG-bilder sömlöst med precision, vilket säkerställer optimal kvalitet och kompatibilitet för dina designbehov.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SvgOptions()](#SvgOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorType()](#getColorType--) | Hämtar eller anger färgtypen för SVG-bilden. |
| [setColorType(int value)](#setColorType-int-) | Hämtar eller anger färgtypen för SVG-bilden. |
| [getTextAsShapes()](#getTextAsShapes--) | Hämtar ett värde som indikerar om text måste renderas som former. |
| [setTextAsShapes(boolean value)](#setTextAsShapes-boolean-) | Ställer in ett värde som indikerar om text måste renderas som former. |
| [getCallback()](#getCallback--) | Hämtar lagringsstrategin för inbäddade resurser i [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) såsom teckensnitt, inbäddade rasterbilder. |
| [setCallback(ISvgResourceKeeperCallback value)](#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-) | Ställer in lagringsstrategin för inbäddade resurser i [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) såsom teckensnitt, inbäddade rasterbilder. |
| [getCompress()](#getCompress--) | Hämtar ett värde som indikerar om den utgående bilden måste komprimeras. |
| [setCompress(boolean value)](#setCompress-boolean-) | Ställer in ett värde som indikerar om utdata bilden måste komprimeras. |

## Example: The following example shows how to convert a multipage vector image to SVG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.svg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.SvgOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. Faktiskt kommer bara en sida att konverteras eftersom SVG inte är ett flersidigt format.
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


Hämtar eller anger färgtypen för SVG-bilden.

**Returns:**
int - Typen av färgen på SVG-bilden.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Hämtar eller anger färgtypen för SVG-bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Typen av färgen på SVG-bilden. |

### getTextAsShapes() {#getTextAsShapes--}
```
public boolean getTextAsShapes()
```


Hämtar ett värde som indikerar om text måste renderas som former.

Värde: `true` om all text omvandlas till SVG-former i konverteringen; annars `false`.

**Returns:**
boolean - ett värde som indikerar om text måste renderas som former.
### setTextAsShapes(boolean value) {#setTextAsShapes-boolean-}
```
public void setTextAsShapes(boolean value)
```


Ställer in ett värde som indikerar om text måste renderas som former.

Värde: `true` om all text omvandlas till SVG-former i konverteringen; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om text måste renderas som former. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla typer av bilder, inklusive WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text kommer att konverteras till former.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Bakgrundsfärgen på ritytan.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sidstorleken.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Om inbäddad emf finns, rendera emf; annars rendera wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla bildtyper inklusive EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text kommer att konverteras till former.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Bakgrundsfärgen på ritytan.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sidstorleken.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Om inbäddad emf finns, rendera emf; annars rendera wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Ställ in den horisontella marginalen
    rasterizationOptions.setBorderX(50);

    // Ställ in den vertikala marginalen
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


Hämtar lagringsstrategin för inbäddade resurser i [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) såsom teckensnitt, inbäddade rasterbilder.

**Returns:**
[ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) - the storing strategy for embedded resources of [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) such as fonts, nested rasters.
### setCallback(ISvgResourceKeeperCallback value) {#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-}
```
public void setCallback(ISvgResourceKeeperCallback value)
```


Ställer in lagringsstrategin för inbäddade resurser i [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) såsom teckensnitt, inbäddade rasterbilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) | lagringsstrategin för inbäddade resurser i [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) såsom teckensnitt, inbäddade rasterbilder. |

### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Hämtar ett värde som indikerar om den utgående bilden måste komprimeras.

**Returns:**
boolean - ett värde som indikerar om den utgående bilden måste komprimeras.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Ställer in ett värde som indikerar om utdata bilden måste komprimeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om den utgående bilden måste komprimeras. |


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

