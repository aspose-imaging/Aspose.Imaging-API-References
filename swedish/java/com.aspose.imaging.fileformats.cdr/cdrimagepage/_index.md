---
title: "CdrImagePage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Cdr-bildsidan."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

Cdr-bildsidan.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParentImage()](#getParentImage--) | Hämtar föräldrabilden. |
| [getPageNumber()](#getPageNumber--) | Hämtar sidnumret. |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getFileFormat()](#getFileFormat--) | Hämtar ett värde för filformat. |
| [getCdrDocument()](#getCdrDocument--) | Hämtar CDR-dokumentet. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen. |
| [cacheData()](#cacheData--) | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Ställer in bildpaletten. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Hämtar föräldrabilden.

Värde: Föräldrabilden.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Hämtar sidnumret.

Värde: Sidnumret.

**Returns:**
int – sidnumret.
### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

**Returns:**
int - bildens bitar per pixel-antal.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar ett värde för filformat.

**Returns:**
long - ett värde för filformat
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Hämtar CDR-dokumentet.

Värde: CDR-dokumentet.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
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
public synchronized void cacheData()
```


Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer`.

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

