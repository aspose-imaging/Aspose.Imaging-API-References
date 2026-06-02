---
title: "CmxImagePage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bilden av CMX-sidan."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

Bilden av CMX-sidan.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Initierar en ny instans av klassen [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Initierar en ny instans av klassen [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | Hämtar CMX-sidan. |
| [getFileFormat()](#getFileFormat--) | Hämtar ett värde för filformat. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [getWidthF()](#getWidthF--) | Hämtar objektets bredd i tum. |
| [getHeightF()](#getHeightF--) | Hämtar objektets höjd i tum. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen. |
| [cacheData()](#cacheData--) | Cache kan inte användas. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Ställer in bildpaletten. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Initierar en ny instans av klassen [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | CMX-sidan. |
| container | [Image](../../com.aspose.imaging/image) | Behållaren. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Initierar en ny instans av klassen [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | CMX-sidan. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Hämtar CMX-sidan.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar ett värde för filformat.

**Returns:**
long - ett värde för filformat
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

**Returns:**
int - bildens bitar per pixel-antal.
### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.

Värde: `true` om objektets data är cachade; annars `false`.

**Returns:**
boolean - ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.
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

Värde: Bildens bredd.

**Returns:**
int - bildens bredd.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

Värde: Bildens höjd.

**Returns:**
int - bildens höjd.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämtar standardalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache kan inte användas.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Läs in en bild från en CMX-fil.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Detta anrop cachelagrar endast standardsidan.
    image.cacheData();

    // Cachelagra alla sidor så att ingen ytterligare dataladdning utförs från den underliggande dataströmmen.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Ställer in bildpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

