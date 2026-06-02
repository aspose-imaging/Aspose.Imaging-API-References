---
title: "WebPOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa moderna WebP rasterwebbilder med vårt API som erbjuder robust stöd för förlustfri och förlustkomprimering samt alfakanaler och animationsslingor."
type: docs
weight: 53
url: /sv/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

Skapa moderna WebP rasterwebbilder med vårt API, som erbjuder robust stöd för förlustfri och förlustkomprimering samt alfakanaler och animationsslingor. Förbättra ditt webb-innehåll med dynamiska visuella element samtidigt som du optimerar filstorlekar för förbättrade laddningshastigheter och användarupplevelse.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLossless()](#getLossless--) | Hämtar eller anger ett värde som indikerar om detta `WebPOptions` är förlustfritt. |
| [setLossless(boolean value)](#setLossless-boolean-) | Hämtar eller anger ett värde som indikerar om detta `WebPOptions` är förlustfritt. |
| [getQuality()](#getQuality--) | Hämtar eller anger kvaliteten. |
| [setQuality(float value)](#setQuality-float-) | Hämtar eller anger kvaliteten. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Hämtar eller anger antalet animationsslingor. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Hämtar eller anger antalet animationsslingor. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Hämtar eller anger färgen på animationsbakgrunden. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Hämtar eller anger färgen på animationsbakgrunden. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som animerade ramar i den exporterade WEBP-filen.
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


Hämtar eller anger ett värde som indikerar om detta `WebPOptions` är förlustfritt.

**Returns:**
boolesk - `true` om förlustfri; annars `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `WebPOptions` är förlustfritt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om förlustfri; annars `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Hämtar eller anger kvaliteten.

**Returns:**
float - Kvaliteten.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Hämtar eller anger kvaliteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Kvaliteten. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Hämtar eller anger antalet animationsslingor.

**Returns:**
int - Antalet animationsslingor, 0 - oändlighet.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Hämtar eller anger antalet animationsslingor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Antalet animationsslingor, 0 - oändlighet. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Hämtar eller anger färgen på animationsbakgrunden.

**Returns:**
long - Färgen på animationsbakgrunden.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Hämtar eller anger färgen på animationsbakgrunden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Färgen på animationsbakgrunden. |

