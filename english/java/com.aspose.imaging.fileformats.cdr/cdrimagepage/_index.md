---
title: CdrImagePage
second_title: Aspose.Imaging for Java API Reference
description: The Cdr image page
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

The Cdr image page
## Methods

| Method | Description |
| --- | --- |
| [getParentImage()](#getParentImage--) | Gets the parent image. |
| [getPageNumber()](#getPageNumber--) | Gets the page number. |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [getCdrDocument()](#getCdrDocument--) | Gets the CDR document. |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Gets the parent image.

Value: The parent image.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Gets the page number.

Value: The page number.

**Returns:**
int - the page number.
### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

**Returns:**
int - the image bits per pixel count.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long - a value of file format
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Gets the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Gets the CDR document.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### cacheData() {#cacheData--}
```
public synchronized void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer`.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Sets the image palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

