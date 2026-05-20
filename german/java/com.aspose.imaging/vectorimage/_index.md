---
title: "VectorImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Vektorbild ist die Basisklasse für alle Arten von Vektorbildern."
type: docs
weight: 117
url: /de/java/com.aspose.imaging/vectorimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.interfaces.IObjectWithSizeF](../../com.aspose.imaging.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

Das Vektorbild ist die Basisklasse für alle Arten von Vektorbildern.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändert die Größe auf die angegebene neue Breite. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Skaliert das Bild mit erweiterten Optionen. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet das angegebene Rechteck zu. |
| [rotate(float angle)](#rotate-float-) | Bild um die Mitte drehen. |
| [getSizeF()](#getSizeF--) | Ermittelt die Objektgröße in Zoll. |
| [getWidthF()](#getWidthF--) | Ermittelt die Objektbreite in Zoll. |
| [getHeightF()](#getHeightF--) | Ermittelt die Objekthöhe in Zoll. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ermittelt die Standard‑Bildoptionen. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Ermittelt die eingebetteten Bilder. |
| [removeBackground()](#removeBackground--) | Entfernt den Hintergrund. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Entfernt den Hintergrund. |

## Example: The following example shows how to export a multipage vector image to another format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\java\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Nur die ersten beiden Seiten exportieren
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


Ändert die Größe auf die angegebene neue Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Skaliert das Bild mit erweiterten Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Typ von Drehen&Spiegeln. |

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

### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


Ermittelt die Objektgröße in Zoll.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the object size, in inches.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Ermittelt die Objektbreite in Zoll.

**Returns:**
float - die Objektbreite, in Zoll.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Ermittelt die Objekthöhe in Zoll.

**Returns:**
float - die Objekthöhe, in Zoll.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

**Returns:**
int – die Bildbreite.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

**Returns:**
int – die Bildhöhe.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Ermittelt die Standard‑Bildoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | java.lang.Object[] | Die Argumente. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The default image options.
### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Ermittelt die eingebetteten Bilder.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - Array von Bildern

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


Entfernt den Hintergrund.

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Entfernt den Hintergrund.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Die Einstellungen. |

