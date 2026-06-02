---
title: "VectorImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Vektorbilden är basklassen för alla typer av vektorbilder."
type: docs
weight: 117
url: /sv/java/com.aspose.imaging/vectorimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.interfaces.IObjectWithSizeF](../../com.aspose.imaging.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

Vektorbilden är basklassen för alla typer av vektorbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på den angivna nya bredden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar bildens storlek med utökade alternativ. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roterar, vänder eller roterar och vänder bilden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär den angivna rektangeln. |
| [rotate(float angle)](#rotate-float-) | Rotera bilden kring centrum. |
| [getSizeF()](#getSizeF--) | Hämtar objektets storlek i tum. |
| [getWidthF()](#getWidthF--) | Hämtar objektets bredd i tum. |
| [getHeightF()](#getHeightF--) | Hämtar objektets höjd i tum. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen för bilden. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Hämtar de inbäddade bilderna. |
| [removeBackground()](#removeBackground--) | Tar bort bakgrunden. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Tar bort bakgrunden. |

## Example: The following example shows how to export a multipage vector image to another format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\java\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna
    com.aspose.imaging.IMultipageImage multipageImage = image instanceof com.aspose.imaging.IMultipageImage ? (com.aspose.imaging.IMultipageImage)image : null;
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

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändrar storlek på den angivna nya bredden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar bildens storlek med utökade alternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Typ av rotera&vänd. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotera bilden kring centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


Hämtar objektets storlek i tum.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the object size, in inches.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Hämtar objektets bredd i tum.

**Returns:**
float – objektets bredd i tum.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Hämtar objektets höjd i tum.

**Returns:**
float – objektets höjd i tum.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

**Returns:**
int - bildens bredd.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

**Returns:**
int - bildens höjd.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämtar standardalternativen för bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The default image options.
### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Hämtar de inbäddade bilderna.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - Array av bilder

**Example: Support extracting embedded raster images from a vector image**

``` java
String inputFileName = "test.cdr";
try (Image image = com.aspose.imaging.Image.load(inputFileName))
{
    com.aspose.imaging.VectorImage vectorImage = ((com.aspose.imaging.VectorImage) image);
    EmbeddedImage[] images = vectorImage.getEmbeddedImages();
    for (int i = 0; i < images.length; i++)
    {
        String outFileName = String.format("image%d.png", i++);
        try
        {
            images[i].getImage().save(outFileName, new PngOptions());
        }
        finally
        {
            images[i].close();
        }
    }
}
```

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


Tar bort bakgrunden.

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Tar bort bakgrunden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Inställningarna. |

