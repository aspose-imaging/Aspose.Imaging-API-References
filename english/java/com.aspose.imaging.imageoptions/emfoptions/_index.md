---
title: EmfOptions
second_title: Aspose.Imaging for Java API Reference
description: The Emf options.
type: docs
weight: 18
url: /java/com.aspose.imaging.imageoptions/emfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.MetafileOptions](../../com.aspose.imaging.imageoptions/metafileoptions)
```
public class EmfOptions extends MetafileOptions
```

The Emf options.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfOptions()](#EmfOptions--) |  |
| [EmfOptions(float dpiX, float dpiY)](#EmfOptions-float-float-) | Initializes a new instance of the `EmfOptions` class. |
| [EmfOptions(float dpi)](#EmfOptions-float-) |  |
| [EmfOptions(EmfOptions emfOptions)](#EmfOptions-com.aspose.imaging.imageoptions.EmfOptions-) | Initializes a new instance of the `EmfOptions` class. |

## Example: The following example shows how to convert a multipage vector image to EMF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.emf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.EmfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. In fact, only one page will be converted because EMF is not a multi-page format.
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfOptions() {#EmfOptions--}
```
public EmfOptions()
```


### EmfOptions(float dpiX, float dpiY) {#EmfOptions-float-float-}
```
public EmfOptions(float dpiX, float dpiY)
```


Initializes a new instance of the `EmfOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | float |  |
| dpiY | float |  |

### EmfOptions(float dpi) {#EmfOptions-float-}
```
public EmfOptions(float dpi)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpi | float |  |

### EmfOptions(EmfOptions emfOptions) {#EmfOptions-com.aspose.imaging.imageoptions.EmfOptions-}
```
public EmfOptions(EmfOptions emfOptions)
```


Initializes a new instance of the `EmfOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| emfOptions | [EmfOptions](../../com.aspose.imaging.imageoptions/emfoptions) | The EMF options. |

