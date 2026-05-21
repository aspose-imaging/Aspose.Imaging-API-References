---
title: "WebPOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstellen Sie moderne WebP-Raster-Webbilder mit unserer API, die eine robuste Unterstützung für verlustfreie und verlustbehaftete Kompression sowie Alphakanäle und Animationsschleifen bietet."
type: docs
weight: 53
url: /de/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

Erstellen Sie moderne WebP-Raster-Webbilder mit unserer API, die eine robuste Unterstützung für verlustfreie und verlustbehaftete Kompression sowie Alphakanäle und Animationsschleifen bietet. Verbessern Sie Ihre Webinhalte mit dynamischen Visuals, während Sie die Dateigrößen optimieren, um schnellere Ladezeiten und ein besseres Benutzererlebnis zu erzielen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLossless()](#getLossless--) | Ruft den Wert ab oder legt ihn fest, der angibt, ob diese `WebPOptions` verlustfrei ist. |
| [setLossless(boolean value)](#setLossless-boolean-) | Ruft den Wert ab oder legt ihn fest, der angibt, ob diese `WebPOptions` verlustfrei ist. |
| [getQuality()](#getQuality--) | Ruft die Qualität ab oder legt sie fest. |
| [setQuality(float value)](#setQuality-float-) | Ruft die Qualität ab oder legt sie fest. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Ruft die Anzahl der Animationsschleifen ab oder legt sie fest. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Ruft die Anzahl der Animationsschleifen ab oder legt sie fest. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Ruft die Farbe des Animationshintergrunds ab oder legt sie fest. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Ruft die Farbe des Animationshintergrunds ab oder legt sie fest. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportieren Sie nur die ersten beiden Seiten. Diese Seiten werden als animierte Frames im ausgegebenen WEBP dargestellt.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


Ruft den Wert ab oder legt ihn fest, der angibt, ob diese `WebPOptions` verlustfrei ist.

**Returns:**
boolean - `true`, wenn verlustfrei; andernfalls `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Ruft den Wert ab oder legt ihn fest, der angibt, ob diese `WebPOptions` verlustfrei ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn verlustfrei; andernfalls `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Ruft die Qualität ab oder legt sie fest.

**Returns:**
float - Die Qualität.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Ruft die Qualität ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Qualität. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Ruft die Anzahl der Animationsschleifen ab oder legt sie fest.

**Returns:**
int - Die Anzahl der Animationsschleifen, 0 - unendlich.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Ruft die Anzahl der Animationsschleifen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Anzahl der Animationsschleifen, 0 - unendlich. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Ruft die Farbe des Animationshintergrunds ab oder legt sie fest.

**Returns:**
long - Die Farbe des Animationshintergrunds.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Ruft die Farbe des Animationshintergrunds ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Farbe des Animationshintergrunds. |

