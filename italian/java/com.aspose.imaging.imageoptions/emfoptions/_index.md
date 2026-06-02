---
title: "EmfOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni Emf."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.imageoptions/emfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.MetafileOptions](../../com.aspose.imaging.imageoptions/metafileoptions)
```
public class EmfOptions extends MetafileOptions
```

Le opzioni Emf.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfOptions()](#EmfOptions--) |  |
| [EmfOptions(float dpiX, float dpiY)](#EmfOptions-float-float-) | Inizializza una nuova istanza della classe `EmfOptions`. |
| [EmfOptions(float dpi)](#EmfOptions-float-) |  |
| [EmfOptions(EmfOptions emfOptions)](#EmfOptions-com.aspose.imaging.imageoptions.EmfOptions-) | Inizializza una nuova istanza della classe `EmfOptions`. |

## Example: The following example shows how to convert a multipage vector image to EMF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.emf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.EmfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. In realtà, verrà convertita solo una pagina perché EMF non è un formato multipagina.
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


Inizializza una nuova istanza della classe `EmfOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpiX | float |  |
| dpiY | float |  |

### EmfOptions(float dpi) {#EmfOptions-float-}
```
public EmfOptions(float dpi)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpi | float |  |

### EmfOptions(EmfOptions emfOptions) {#EmfOptions-com.aspose.imaging.imageoptions.EmfOptions-}
```
public EmfOptions(EmfOptions emfOptions)
```


Inizializza una nuova istanza della classe `EmfOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| emfOptions | [EmfOptions](../../com.aspose.imaging.imageoptions/emfoptions) | Le opzioni EMF. |

